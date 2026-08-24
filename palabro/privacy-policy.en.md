# Privacy Policy — PalaBro

**Last updated: 24 August 2026**

This policy explains what data the **PalaBro** application ("the app",
"we") — published by **MisCo Apps** — processes, and how. By using the
app you accept this policy.

## 1. Data controller

- **Controller:** MisCo Apps (individual publisher).
- **Contact:** miscoapps@gmail.com

## 2. Data we DO NOT collect

PalaBro **requires no registration or user account**. We do not collect
or store:

- Name, email, phone number, or any other personally identifying data.
- Passwords (there is no login system).
- Contact list, photos, precise location, microphone, or camera.
- Browsing history outside the app.
- Payment data: card number, billing address, or similar.

The only thing we keep on our own servers is **a technical record of each
purchase**, described in section 10. Everything else lives on your device.

Some third-party providers (Unity, Google) do process certain technical
data from your device when ads are shown, app usage is measured, crashes
are reported, or achievements are synced. This is detailed in sections 5
to 9.

## 3. Data stored locally on your device

All game information is stored **only on your device** using local
storage (Hive). It includes:

- Current level, completed levels, daily puzzle progress.
- App settings (music, sound effects, language, colorblind mode,
  notifications, vibration).
- Daily puzzle streak and the date of the last completed challenge.
- Coin balance and remaining hints.
- Your advertising consent decision (section 5).

This data is deleted if you uninstall the app or clear its data from
system settings.

## 4. Local notifications

If you enable notifications, the app schedules **local reminders** (at
8:00 PM local time) for the daily challenge using the operating system's
native API. They are not sent through external servers: your device
schedules and displays them. You can disable them at any time from the
app's Settings or from your system settings.

## 5. Advertising (Unity LevelPlay)

PalaBro shows ads to sustain development. Advertising is managed through
**Unity LevelPlay**, the mediation platform of **Unity Technologies**
(which includes **ironSource Ltd.**). For each ad slot, the mediation
decides which of the connected networks serves the ad; currently these
are **Unity Ads** and **ironSource Ads**. If other networks are connected
in the future, they will process data under their own policies.

To serve ads, the following data may be collected from your device:

- **Advertising identifier** (Advertising ID on Android, IDFA on iOS):
  a non-permanent code that you can reset or disable from your system
  settings.
- **Device information:** model, operating system, language, connection
  type, screen resolution.
- **IP address** (used for approximate country/region location).
- **Ad interactions:** impressions, clicks, viewing time.

This data is collected and processed by Unity and the network serving
each ad, not by us. Unity's information and controls for players:
[https://unity.com/legal/game-player-and-app-user-privacy-policy](https://unity.com/legal/game-player-and-app-user-privacy-policy)
and [https://unity.com/legal/privacy-policy](https://unity.com/legal/privacy-policy).

### Personalized vs non-personalized ads

- **In the European Economic Area, the United Kingdom, and Switzerland:**
  the first time you open the app we show **our own consent dialog**,
  where you choose whether to accept personalized ads. Your decision is
  stored **on your device** and passed to the advertising platform as a
  yes/no signal, which it forwards to the networks serving the ads. You
  can change it at any time from **Settings → "Manage consent"** in the
  app.
- **Declining does not remove ads:** they become **non-personalized**,
  meaning they are selected without using your advertising identifier to
  build an interest profile. Declining also disables the usage analytics
  described in section 7.
- **On iOS:** in addition to the above consent, iOS requests permission
  for cross-app tracking (App Tracking Transparency). If denied, ads
  will be non-personalized.
- **Rest of the world:** personalized ads are served by default, with
  the option to opt out from your operating system's ad settings or from
  the app's Settings dialog.

## 6. Rewarded ads

The app offers optional ads you may watch voluntarily to gain coins, an
extra hint, or recover a lost daily streak. These ads are
**user-initiated** (never forced) and follow the same rules described in
section 5.

## 7. Usage analytics (Firebase Analytics)

To understand how the game is played and decide what to improve, the app
uses **Firebase Analytics**, a service provided by Google LLC. Aggregated
usage events are recorded, such as:

- Starting and completing a level, and whether it was the daily challenge.
- Completing the campaign, completing or skipping the tutorial, using hints.
- Purchases made and the app's first launch.
- The app's active language.

These events are tied to a **pseudonymous installation identifier**
generated by Firebase, not to your identity, and it disappears when you
uninstall the app. The contents of your games are not recorded, nor is
any data that could identify you.

**Collection is conditional on the consent** described in section 5: if
you decline, analytics is disabled. It is also disabled in development
builds. More information:
[https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy).

## 8. Crash reporting (Firebase Crashlytics)

To detect and fix errors, the app uses **Firebase Crashlytics**, a
service provided by Google LLC. When the app suffers a crash or a
serious error, Crashlytics automatically collects:

- The **technical crash log** (stack trace) and the app's state at that
  moment.
- **Device information:** model, manufacturer, OS version, language,
  available memory and storage.
- The **app version** and the time elapsed until the crash.
- An **installation identifier** generated by Crashlytics, not linked to
  your identity, removed when you uninstall the app.

This data is used **solely** to diagnose and fix errors; it is not used
for advertising purposes and is not sold to third parties. Collection is
disabled in development builds.

## 9. Achievements (Google Play Games)

The app offers an **achievements** system that you may **optionally**
sync with **Google Play Games** (a service provided by Google LLC). This
connection is **voluntary**: it is only enabled if you sign in to Play
Games from the app. If you do, Google processes your Play Games player
identifier to store and display your achievements. If you do not sign
in, achievements are stored only on your device. You can manage or
unlink your account from the Google Play Games app or from your Google
account settings. Google's policy:
[https://policies.google.com/privacy](https://policies.google.com/privacy).

## 10. In-app purchases

The app includes **optional coin pack purchases**. Payment is processed
entirely by **Google Play** (Android) or the **App Store** (iOS) under
their respective policies: **we neither receive nor store payment data**
(card, cardholder, billing address).

To verify that a purchase is legitimate and to avoid crediting it twice,
the app sends the **receipt issued by the store** to a cloud function of
ours (Firebase Cloud Functions). We store a redemption record containing:

- The **transaction identifier** issued by the store.
- The **product purchased** and the number of coins credited.
- The **platform** (Android/iOS) and the **date**.

That record **contains no name, email, or account of yours**, and it is
the **only data we keep on our own servers**. It is retained for as long
as the app remains published, because it is what prevents the same
purchase from being credited repeatedly.

## 11. Children

PalaBro **is not directed at children under 13**. We do not knowingly
collect personal data from children. If you believe a child has provided
us with data, contact us and we will delete it.

## 12. Your rights (GDPR)

As a user in the European Union, the United Kingdom, or Switzerland, you
have the right to:

- **Access:** know what data we hold about you. In our case, only the
  purchase record in section 10; everything else is local or processed
  by the providers listed above.
- **Rectification:** correct inaccurate data.
- **Erasure ("right to be forgotten"):** uninstall the app or clear its
  data from system settings; that removes everything stored locally. For
  the purchase record, contact us.
- **Objection and restriction of processing:** withdraw advertising
  consent from **Settings → "Manage consent"** in the app, reset or limit
  your advertising identifier from your operating system, or uninstall
  the app.
- **Portability:** not applicable in practice, since your progress lives
  on your device and we do not store it.
- **Lodge a complaint:** with the Spanish Data Protection Agency
  ([aepd.es](https://www.aepd.es)) or the equivalent authority in your
  country.

To exercise any right, write to us at **miscoapps@gmail.com**.

## 13. International transfers

The providers listed above may process data outside the European
Economic Area:

- **Unity Technologies** (United States) and **ironSource Ltd.**
  (Israel), for advertising. Israel holds an adequacy decision from the
  European Commission; for the United States, Unity relies on standard
  contractual clauses and equivalent transfer frameworks.
- **Google LLC** (United States), for Analytics, Crashlytics, and Play
  Games, under standard contractual clauses approved by the European
  Commission.

The purchase record in section 10 is stored in **Firestore, in the
European region**.

## 14. Security

All game information is stored locally on your device using the
operating system's standard storage mechanisms. Communication with the
advertising, analytics, crash reporting, Play Games, and purchase
validation services uses HTTPS. The purchase validation function
requires an app integrity token (Firebase App Check), and the redemption
record is not accessible from clients.

## 15. Changes to this policy

We may update this policy from time to time. The "Last updated" date at
the top reflects the current version. Significant changes will be
announced in the next app update.

## 16. Contact

For any question about this policy or about how your data is processed,
write to us at:

**miscoapps@gmail.com**
