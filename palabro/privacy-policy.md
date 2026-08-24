# Política de Privacidad — PalaBro

**Última actualización: 24 de agosto de 2026**

Esta política explica qué datos trata la aplicación **PalaBro** ("la
aplicación", "nosotros"), publicada por **MisCo Apps**, y cómo lo hace.
Al usar la aplicación aceptas esta política.

## 1. Responsable del tratamiento

- **Responsable:** MisCo Apps (publisher individual).
- **Contacto:** miscoapps@gmail.com

## 2. Datos que NO recogemos

PalaBro **no requiere registro ni cuenta de usuario**. No recogemos ni
almacenamos:

- Nombre, email, teléfono ni otros datos de identificación personal.
- Contraseñas (no hay sistema de login).
- Listado de contactos, fotos, ubicación precisa, micrófono o cámara.
- Historial de navegación fuera de la aplicación.
- Datos de pago: número de tarjeta, dirección de facturación o similares.

En servidores propios solo guardamos **un registro técnico de cada compra**,
descrito en la sección 10. Todo lo demás vive en tu dispositivo.

Algunos proveedores externos (Unity, Google) sí tratan ciertos datos técnicos
de tu dispositivo cuando se muestran anuncios, se mide el uso de la aplicación,
se informa de fallos o se sincronizan los logros. Se detalla en las secciones
5 a 9.

## 3. Datos que se almacenan localmente en tu dispositivo

Toda la información de juego se guarda **únicamente en tu dispositivo**
mediante almacenamiento local (Hive). Incluye:

- Nivel actual, niveles completados, progreso del puzzle diario.
- Configuración de la aplicación (música, efectos, idioma, modo
  daltónico, notificaciones, vibración).
- Racha del puzzle diario y fecha del último reto completado.
- Saldo de monedas y número de pistas restantes.
- Tu decisión sobre el consentimiento publicitario (sección 5).

Estos datos se eliminan si desinstalas la aplicación o borras sus datos
desde los ajustes del sistema.

## 4. Notificaciones locales

Si activas las notificaciones, la aplicación programa **recordatorios
locales** (a las 20:00 hora local) para el reto diario usando la API
nativa del sistema operativo. No se envían a través de servidores
externos: tu dispositivo las programa y las muestra. Puedes desactivarlas
en cualquier momento desde Ajustes de la aplicación o desde la
configuración del sistema.

## 5. Anuncios (Unity LevelPlay)

PalaBro muestra anuncios para sostener el desarrollo. La publicidad se
gestiona con **Unity LevelPlay**, la plataforma de mediación de **Unity
Technologies** (que incluye a **ironSource Ltd.**). La mediación decide, en
cada hueco publicitario, cuál de las redes conectadas sirve el anuncio;
actualmente son **Unity Ads** e **ironSource Ads**. Si en el futuro se
conectan otras redes, tratarán los datos conforme a sus propias políticas.

Para servir los anuncios pueden recogerse los siguientes datos de tu
dispositivo:

- **Identificador publicitario** (Advertising ID en Android, IDFA en
  iOS): un código no permanente que puedes resetear o desactivar desde
  los ajustes del sistema.
- **Información del dispositivo:** modelo, sistema operativo, idioma,
  tipo de conexión, resolución de pantalla.
- **Dirección IP** (para localización aproximada por país/región).
- **Interacciones con los anuncios:** impresiones, clics, tiempo de
  visualización.

Estos datos los recogen y procesan Unity y la red que sirve cada anuncio,
no nosotros. Información y controles de Unity para jugadores:
[https://unity.com/legal/game-player-and-app-user-privacy-policy](https://unity.com/legal/game-player-and-app-user-privacy-policy)
y [https://unity.com/legal/privacy-policy](https://unity.com/legal/privacy-policy).

### Anuncios personalizados vs no personalizados

- **En el Espacio Económico Europeo, Reino Unido y Suiza:** la primera
  vez que abres la aplicación te mostramos **nuestro propio diálogo de
  consentimiento**, donde eliges si aceptas anuncios personalizados. Tu
  decisión se guarda **en tu dispositivo** y se transmite a la plataforma
  publicitaria como una señal de sí/no, que esta propaga a las redes que
  sirven los anuncios. Puedes cambiarla en cualquier momento desde
  **Ajustes de la aplicación → "Gestionar consentimiento"**.
- **Rechazar no elimina los anuncios:** pasan a ser **no personalizados**,
  es decir, se seleccionan sin usar tu identificador publicitario para
  construir un perfil de intereses. Rechazar también desactiva la
  analítica de uso descrita en la sección 7.
- **En iOS:** además del consentimiento anterior, iOS solicita permiso
  para rastreo entre apps (App Tracking Transparency). Si lo deniegas,
  los anuncios serán no personalizados.
- **Resto del mundo:** se sirven anuncios personalizados por defecto,
  con la opción de optar por no recibirlos desde los ajustes
  publicitarios del sistema operativo o desde el diálogo de Ajustes.

## 6. Anuncios recompensados

La aplicación ofrece anuncios opcionales que puedes ver voluntariamente
para obtener monedas, una pista extra o recuperar una racha diaria
perdida. Estos anuncios son **iniciados por ti** (nunca forzados) y
siguen las mismas reglas descritas en la sección 5.

## 7. Analítica de uso (Firebase Analytics)

Para entender cómo se juega y decidir qué mejorar, la aplicación utiliza
**Firebase Analytics**, un servicio de Google LLC. Se registran eventos de
uso agregados, como:

- Inicio y finalización de un nivel, y si era el reto diario.
- Finalización de la campaña, uso o salto del tutorial, uso de pistas.
- Compras realizadas y primer arranque de la aplicación.
- El idioma activo de la aplicación.

Estos eventos se asocian a un **identificador de instalación pseudónimo**
generado por Firebase, no a tu identidad, y desaparece al desinstalar la
aplicación. No se registra el contenido de tus partidas ni ningún dato
que permita identificarte.

**La recogida está condicionada al consentimiento** descrito en la
sección 5: si lo rechazas, la analítica se desactiva. También está
desactivada en las versiones de desarrollo. Más información:
[https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy).

## 8. Informes de fallos (Firebase Crashlytics)

Para detectar y corregir errores, la aplicación utiliza **Firebase
Crashlytics**, un servicio de Google LLC. Cuando la aplicación sufre un
fallo o un error grave, Crashlytics recoge de forma automática:

- El **registro técnico del fallo** (stack trace) y el estado de la
  aplicación en ese momento.
- **Información del dispositivo:** modelo, fabricante, versión del
  sistema operativo, idioma, memoria y almacenamiento disponibles.
- La **versión de la aplicación** y el tiempo transcurrido hasta el
  fallo.
- Un **identificador de instalación** generado por Crashlytics, no
  vinculado a tu identidad y que se elimina al desinstalar la aplicación.

Estos datos se usan **únicamente** para diagnosticar y corregir errores;
no se emplean con fines publicitarios ni se venden a terceros. La
recogida está desactivada en las versiones de desarrollo.

## 9. Logros (Google Play Juegos)

La aplicación ofrece un sistema de **logros** que puedes sincronizar de
forma **opcional** con **Google Play Juegos** (servicio de Google LLC).
Esta conexión es **voluntaria**: solo se activa si inicias sesión en Play
Juegos desde la aplicación. Si lo haces, Google trata tu identificador de
jugador de Play Juegos para guardar y mostrar tus logros. Si no inicias
sesión, los logros se guardan únicamente en tu dispositivo. Puedes
gestionar o desvincular tu cuenta desde la aplicación de Google Play
Juegos o desde los ajustes de tu cuenta de Google. Política de Google:
[https://policies.google.com/privacy](https://policies.google.com/privacy).

## 10. Compras dentro de la aplicación

La aplicación incluye **compras opcionales de paquetes de monedas**. El
cobro lo procesa íntegramente **Google Play** (Android) o la **App Store**
(iOS), conforme a sus respectivas políticas: **nosotros no recibimos ni
almacenamos datos de pago** (tarjeta, titular, dirección de facturación).

Para comprobar que una compra es legítima y para evitar acreditarla dos
veces, la aplicación envía el **comprobante que emite la tienda** a una
función en la nube nuestra (Firebase Cloud Functions). Guardamos un
registro de canje que contiene:

- El **identificador de la transacción** emitido por la tienda.
- El **producto comprado** y la cantidad de monedas acreditadas.
- La **plataforma** (Android/iOS) y la **fecha**.

Ese registro **no contiene tu nombre, tu email ni tu cuenta**, y es el
**único dato que guardamos en servidores propios**. Se conserva mientras
la aplicación siga publicada, porque es lo que impide que una misma
compra se acredite repetidamente.

## 11. Menores

PalaBro **no está dirigida a menores de 13 años**. No recogemos
deliberadamente datos personales de menores. Si crees que un menor nos
ha proporcionado datos, contacta con nosotros y los eliminaremos.

## 12. Tus derechos (GDPR / RGPD)

Como usuario en la Unión Europea, Reino Unido o Suiza, tienes derecho a:

- **Acceso:** saber qué datos tenemos sobre ti. En nuestro caso, solo el
  registro de compras de la sección 10; todo lo demás es local o lo
  tratan los proveedores citados.
- **Rectificación:** corregir datos inexactos.
- **Supresión ("derecho al olvido"):** desinstala la aplicación o borra
  sus datos desde los ajustes del sistema; eso elimina todo lo que se
  almacena localmente. Para el registro de compras, escríbenos.
- **Oposición y limitación del tratamiento:** revoca el consentimiento
  publicitario desde **Ajustes de la aplicación → "Gestionar
  consentimiento"**, restablece o limita tu identificador publicitario
  desde el sistema operativo, o desinstala la aplicación.
- **Portabilidad:** no aplicable en la práctica, ya que tu progreso vive
  en tu dispositivo y no lo almacenamos.
- **Presentar una reclamación:** ante la Agencia Española de Protección
  de Datos ([aepd.es](https://www.aepd.es)) o la autoridad equivalente
  de tu país.

Para ejercer cualquier derecho, escríbenos a **miscoapps@gmail.com**.

## 13. Transferencias internacionales

Los proveedores citados pueden tratar datos fuera del Espacio Económico
Europeo:

- **Unity Technologies** (Estados Unidos) e **ironSource Ltd.** (Israel),
  para la publicidad. Israel cuenta con una decisión de adecuación de la
  Comisión Europea; para Estados Unidos, Unity se apoya en cláusulas
  contractuales tipo y marcos de transferencia equivalentes.
- **Google LLC** (Estados Unidos), para Analytics, Crashlytics y Play
  Juegos, con cláusulas contractuales tipo aprobadas por la Comisión
  Europea.

El registro de compras de la sección 10 se almacena en **Firestore, en la
región europea**.

## 14. Seguridad

Toda la información de juego se guarda localmente en tu dispositivo
usando los mecanismos de almacenamiento estándar del sistema operativo.
La comunicación con los servicios de publicidad, analítica, informes de
fallos, Play Juegos y validación de compras se realiza mediante HTTPS.
La función de validación de compras exige un token de integridad de la
aplicación (Firebase App Check), y el registro de canjes no es accesible
desde clientes.

## 15. Cambios en esta política

Podemos actualizar esta política puntualmente. La fecha de "Última
actualización" al inicio refleja la versión vigente. Cambios
significativos se anunciarán en la próxima actualización de la
aplicación.

## 16. Contacto

Para cualquier pregunta sobre esta política o sobre el tratamiento de
tus datos, escríbenos a:

**miscoapps@gmail.com**
