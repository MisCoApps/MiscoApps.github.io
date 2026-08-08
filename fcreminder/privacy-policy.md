# Documento de Requisitos del Producto (PRD): Personal CRM App

## 1. Visión General del Producto
**Descripción:** Aplicación móvil (iOS y Android) diseñada como un "Personal CRM" (Customer Relationship Management personal) que ayuda a los usuarios a mantener el contacto regular con sus amigos, familiares o red profesional. 
**Objetivo Principal:** Mandar notificaciones automáticas y configurables a modo de recordatorio para llamar o mensajear a contactos específicos.
**Público Objetivo:** Profesionales enfocados en networking, expatriados que quieren mantener el contacto con su país de origen o cualquier persona que desee cuidar sus relaciones personales de forma metódica.

## 2. Alcance del Proyecto (Producto Mínimo Viable - MVP)
El MVP se enfocará en las funcionalidades core de recordatorios, operando de manera 100% local en el dispositivo del usuario para garantizar la privacidad y reducir los costes iniciales de infraestructura en la nube. 

**Fuera de alcance para el MVP:** 
- Sincronización en la nube y creación de cuentas de usuario.
- Analíticas avanzadas de red de contactos.

## 3. Requisitos Funcionales y Lógica de Negocio

### 3.1. Gestión y Sincronización de Contactos
- **Permisos:** La app solicitará permiso de lectura de la agenda nativa (`READ_CONTACTS` en Android, `Contacts` en iOS).
- **Importación Selectiva:** No se importará la agenda completa. El usuario seleccionará de una lista a qué personas quiere añadir a su Personal CRM.
- **Sincronización Unidireccional en Tiempo Real:** Si el usuario edita o borra un contacto en la app nativa de su teléfono, la aplicación debe buscar el ID único del contacto nativo y actualizar los datos (nombre, foto, número) cada vez que la app se abra.

### 3.2. Configuración de Recordatorios y Frecuencias
- **Agrupación:** El usuario podrá crear grupos (ej. "Familia", "Networking") y asignarles una frecuencia general (ej. "Cada 15 días").
- **Reglas Individuales:** El usuario podrá configurar frecuencias específicas por persona (ej. "Cada 7 días") o agendar un aviso para un día/hora concretos.
- **Gestión de Colisiones:** Si un contacto pertenece a un grupo y a la vez tiene una regla individual, el sistema debe fusionar la notificación. Al intentar crear una regla que solape, la app mostrará un *pop-up*: *"Este contacto ya tiene una recurrencia por el grupo X. ¿Deseas mantener ambas o que la individual reemplace a la del grupo?"*.
- **Fechas Fijas:** Posibilidad de añadir eventos fijos anuales, como cumpleaños o aniversarios.

### 3.3. Interacción, Notificaciones y Cierre de Ciclos
- **Acciones Rápidas (Deep Links):** Las notificaciones *push* incluirán dos botones nativos: "Llamar" y "Mandar WhatsApp". Al pulsarlos, se abrirá la aplicación correspondiente.
- **Snooze / Persistencia:** Si el usuario ignora un recordatorio, este no se descarta. La alerta se pospone y volverá a avisar al día siguiente hasta que el usuario interactúe.
- **Reinicio Automático (El Cierre del Bucle):**
  - **Android:** Se usará el permiso `READ_CALL_LOG` (sujeto a aprobación de Google Play) para detectar llamadas salientes a ese número y reiniciar el contador automáticamente.
  - **iOS/General:** Como iOS bloquea por *Sandboxing* la lectura del historial telefónico y de WhatsApp de terceros, el sistema asumirá que el contacto se ha realizado —y reiniciará el contador— **en el momento en que el usuario pulse el botón de "Llamar" o "WhatsApp"** desde la notificación o desde dentro de la propia app.

### 3.4. Ficha de Contacto (Perfil Extendido)
- **Notas Contextuales:** Campo de texto libre para que el usuario apunte de qué se habló en la última interacción (ej. *"Preguntar por su nuevo perro"*).
- **Historial de Interacciones:** Registro visual cronológico (*timeline*) donde la app guardará cuándo fue la última vez que se hizo tap en "Llamar/WhatsApp" o se marcó manualmente como contactado.

## 4. Arquitectura Técnica
- **Plataforma:** Desarrollo híbrido mediante **Flutter** o **React Native** para lanzar en iOS y Android compartiendo código base.
- **Almacenamiento Local (MVP):** Toda la base de datos de grupos, contadores y notas se guardará localmente en el dispositivo usando **SQLite** o **Realm**. 
- **Notificaciones:** Programación de notificaciones locales a través de los sistemas nativos (`UNUserNotificationCenter` en iOS, `WorkManager/AlarmManager` en Android). No se requiere servidor externo para *push notifications* en esta fase.

## 5. Monetización (Modelo Freemium)
La aplicación será de descarga gratuita con un muro de pago (*Paywall*) y publicidad para generar ingresos.

*   **Versión Free:** 
    *   Inclusión de banners de publicidad nativa (Google AdMob o similar).
    *   Límites funcionales: Máximo 2 grupos creados y límite de X contactos importados al Personal CRM.
*   **Versión Premium (Suscripción o Pago Único):**
    *   Eliminación total de anuncios.
    *   Contactos y grupos ilimitados.
    *   *Futuro:* Backup en la nube y sincronización multidispositivo.

## 6. Siguientes Pasos (Hoja de Ruta)
1.  **Wireframing/Diseño UX-UI:** Diseñar las pantallas principales (Dashboard de tareas de hoy, Lista de contactos, Ficha de contacto y Ajustes).
2.  **Validación de Permisos:** Revisar exhaustivamente las políticas vigentes de Google Play Store para la justificación del uso de `READ_CALL_LOG` en el *tracker* de Android.
3.  **Desarrollo MVP:** Iniciar la programación enfocándose primero en el almacenamiento local y la precisión del motor de notificaciones.
