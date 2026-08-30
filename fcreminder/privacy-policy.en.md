# Privacy Policy — Friendly Contact Reminder

**Last updated: 30 August 2026**

This policy explains what data the **Friendly Contact Reminder** application ("the
app", "we") published by **MisCo Apps** processes, and how. By using the app
you accept this policy.

## 1. Data controller

- **Controller:** MisCo Apps (individual publisher).
- **Contact:** miscoapps@gmail.com

## 2. Summary: we never receive your data

The app **has no servers of its own**, requires no registration or account, and
contains no advertising and no advertising trackers. **Your
contacts, your reminders, your conversation history, your labels and your notes
never reach us**: we do not receive them, we do not see them, and we could not
recover them even if we wanted to.

We do receive two technical, anonymous things about the app itself: the **crash
reports** in section 11 and some **usage statistics** in section 12 that tell us
which features get used and which do not. Neither carries your data — they count
**what broke** and **which button was tapped**, never who you contact or what you
wrote — both are anonymous, and both are turned off by the same switch:
**Settings → Help → "Help improve the app"**.

By default, all of it also **stays inside your phone**. There are five
exceptions, and all five are your decision:

1. **The backup file** (section 6): if you use it, your data is written to the
   destination you choose.
2. **Automatic backup to Google Drive** (section 7): if you enable it, your
   data is uploaded **to your own Drive account**. Not to ours: we have none.
3. **The Premium subscription** (section 10): to know whether your subscription
   is still active we use an external provider, which means an anonymous
   identifier and your purchase status do leave the device.
4. **Crash reports** (section 11): if the app closes on its own or something
   breaks inside it, a technical report about **that failure** is sent so we can
   fix it. You can turn them off at any time in **Settings → Help → "Help
   improve the app"**.
5. **Usage statistics** (section 12): which features get used and which do not,
   as anonymous counters. They are turned off by **the same switch** as crash
   reports.

The first two send data **somewhere that belongs to you**; the last three
involve a third party acting on our behalf.

## 3. Data we do NOT collect

Friendly Contact Reminder **requires no registration or user account**. We do not collect
or store on any system of ours:

- Name, email, phone number or any other personally identifying data.
- Passwords (there is no login system).
- Your contact list, or any data derived from it.
- The content of your reminders, notes or conversation history.
- Location, microphone or camera (the app does not request these permissions).
- Advertising identifiers, since we show no ads.
- Card or payment data (see section 10).

⚠️ This means **we** do not collect them. If you enable backups (sections 6 and
7), that data does leave your device, but it goes **to a destination of yours**
— a file you store, or your own Google Drive account — never to a system of
ours. Neither the crash reports in section 11 nor the usage statistics in
section 12 contain anything from this list.

## 4. Access to your contacts

The app requests the **contacts** permission (`READ_CONTACTS` on Android,
Contacts access on iOS) because it is its core function: reminding you to get in
touch with the people you choose.

- **When it is requested:** only when you tap **Import contact**. If you decline,
  the rest of the app keeps working.
- **What is read:** for the contacts you import, we read the name, phone numbers
  and emails (with their labels), the thumbnail photo and the dates associated
  with the contact (birthdays and anniversaries), in order to create reminders.
- **Where it is stored:** in a local database on your device (Isar). **It is not
  transmitted to any system of ours**, nor to the provider in section 10.
- **What is NOT done:** we do not read your call log or your messages. The app
  does not declare those permissions.
- **How to revoke it:** from your operating system settings, at any time. You can
  also unlink a specific contact from within the app, which deletes its data from
  local storage without touching your phone's address book.

## 5. Data stored locally on your device

All of this information is stored **only on your device**. It includes:

- The contacts you have imported and their data (see section 4).
- Your reminders: frequency, fixed dates, whether they avoid weekends.
- The conversation history you record (type, date and notes).
- The labels you create and which contacts they are assigned to.
- App settings (theme, language, notification times, first day of the week,
  favourite messaging app, haptics, notifications enabled).
- If you connect Drive backup, **the email address of that Google account**, so
  the app can show you in Settings which account you are using. It is stored on
  your phone and **is not transmitted anywhere** (see section 7).

This data is deleted if you uninstall the app or clear its data from your system
settings.

## 6. Backup to a file

The app can generate a **backup file** (`.crmbak` extension) so you do not lose
your information when changing phones or reinstalling. This is a **free**
feature, available whether or not you have Premium.

- **What it contains:** your imported contacts, your reminders, your conversation
  history, your labels and your settings — that is, everything described in
  sections 4 and 5.
- **It also includes the device model** that generated it ("Pixel 8") so you can
  tell one backup from another. **The name you gave your phone is not included**,
  precisely because it usually contains a person's name.
- **Where it goes:** to the destination you choose in the system dialog. The app
  does not send it anywhere on its own.
- **We never receive it** and have no way to read it.

⚠️ **Important: the file is compressed, but NOT encrypted.** Anyone holding that
file can read its contents with the right tools. Treat it as you would an export
of your address book: if you email it, upload it to a shared service or leave it
in an accessible folder, that data is within reach of anyone who can reach that
location. Store it somewhere only you can get to.

Restoring a backup **replaces** whatever data is in the app at that moment; it
does not merge it.

## 7. Automatic backup to Google Drive (Premium)

With **Premium**, you can connect your Google account so that the backup
described in section 6 **is saved automatically to your own Google Drive**. It
is optional and stays off unless you turn it on.

**What permissions we request, and why:**

- The app requests **a single Google permission: `drive.file`**. That permission
  grants access **only to the files the app itself creates**. We cannot see,
  list or open any other file in your Drive — neither the ones you already had
  nor the ones you create later with other applications.
- **We do not ask you to sign in with Google and we do not access your profile**,
  so we never receive your public name, your photo, your gender or your date of
  birth.
- The **email address** shown in Settings is obtained from the Drive API itself,
  solely to show you which account you connected, and it is stored **only on
  your phone** (section 5).

**How the backup works:**

- It is uploaded **at most once a day**, and only **if your data has changed**
  since the last backup.
- The **3 most recent backups** are kept in the app's own folder inside your
  Drive; when a new one is uploaded, the oldest is deleted.
- **The data goes to your account, not ours.** We have no access to your Drive
  or to the backups it contains. Google's processing of it is governed by the
  [Google Privacy Policy](https://policies.google.com/privacy).
- The uploaded file is the same one described in section 6, with the same
  warning: **it is compressed, not encrypted**.

**How to disconnect it:** from the app's **Settings**, at any time. You can also
revoke access from your Google account at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).
Disconnecting does not delete backups already in your Drive: you can remove them
yourself from Drive whenever you want (section 15).

**Limited Use of Google API data:** Friendly Contact Reminder's use of information
received from Google APIs adheres to the [Google API Services User Data
Policy](https://developers.google.com/terms/api-services-user-data-policy),
including its **Limited Use** requirements. Specifically: that data is used only
to provide the backup feature, it is **not transferred to third parties**, it is
**not used for advertising purposes**, and **no human reads it**.

## 8. Local notifications

The app schedules **local reminders** using the operating system's native API,
at the time you configure. They do not pass through any external server: your
own device schedules and displays them. The notification may include the
contact's name and thumbnail photo, read from the phone's local storage.

You can disable them at any time from the app's **Settings** or from your system
settings.

On Android, the app may ask for the **alarms and reminders** permission so that
notifications arrive at exactly the time you chose. It is optional: without it,
reminders still work, but the system may delay them.

## 9. Third-party apps (calls and messaging)

From a contact's detail screen you can start a **call** or open a conversation in
**WhatsApp, Telegram, Viber, WeChat, LINE, SMS or your email client**. At that
moment the operating system hands the phone number or email address to the app
you chose, and from then on **that app's privacy policy** applies, not ours.

We do not send anything to those apps on our own initiative, nor do we know
whether you end up using them: you always initiate the action.

## 10. Premium subscription (RevenueCat)

The app offers an optional **Premium subscription**. Payment is handled entirely
by **Google Play** (or Apple's **App Store** on iOS) under their own policies:
**we never receive or process card or payment data**.

To know whether your subscription is still active (renewals, cancellations,
trial period, expiry) we use **RevenueCat, Inc.**, a specialised provider acting
as a **data processor** on our behalf.

**What is sent to RevenueCat:**

- An **anonymous identifier generated by the app** on installation. It is not
  your name, your email or your Google account: it is a random code that only
  serves to recognise that installation.
- The **status of your subscription and your purchase history** within the app:
  which plan you have, when it renews, whether it is active or expired.
- **Basic technical device data** (model, operating system, app version, store
  country), needed to process the purchase.

**What is NEVER sent to RevenueCat:** your contacts, your reminders, your
conversation history, your labels or your notes. Nothing described in sections 4
and 5 reaches this provider, not even if you use the backups in sections 6 and 7.

- **Purpose:** solely so the app knows whether to grant you access to Premium
  features, and for aggregate subscription statistics.
- **Legal basis (GDPR):** performance of the subscription contract (art. 6(1)(b)).
  If you never open the Premium section, this collection still happens at app
  startup, since it is necessary to check whether you have access.
- **Retention:** for as long as your record exists in RevenueCat. You can ask us
  to delete it (section 15).
- **It is not sold or shared with third parties for advertising purposes.** There
  are no RevenueCat integrations with ad networks or third-party analytics tools.
- RevenueCat's privacy policy:
  [revenuecat.com/privacy](https://www.revenuecat.com/privacy/)

## 11. Crash reports (Firebase Crashlytics)

When the app closes unexpectedly or something breaks inside it, a **technical
report about that failure** is sent to **Firebase Crashlytics**, a service run by
**Google Ireland Limited** acting as a **data processor** on our behalf. It
serves one purpose: letting us find out that something broke on a phone we do
not have in front of us, so we can fix it.

**What is sent:**

- The **error type and the technical stack trace** of the point in the program
  where it happened.
- **Device and app data**: model, operating system version, app version, device
  language and country.
- The **state of the device at that moment**: available memory and storage,
  screen orientation, whether the app was in the foreground and how long it had
  been open.
- A **random identifier generated by Crashlytics** for that installation, which
  tells us whether the same failure hits many people or hits one person a
  thousand times. It is not your name, your email or your Google account, and we
  cannot link it to you.

**What is never sent:** your contacts, their names, phone numbers or email
addresses, your reminders, your conversation history, your labels or your notes.
A crash report describes **the state of the program**, not your data, and the app
never includes any of it in what it sends.

- **Purpose:** finding and fixing errors, and knowing how many people each one
  affects so we can prioritise. It is not used to profile you, to advertise to
  you, or to measure your use of the app.
- **Legal basis (GDPR):** legitimate interest (art. 6(1)(f)) in keeping the app
  working and secure. Since that interest is ours and not yours, the switch below
  lets you object without giving any reason.
- **How to turn it off:** **Settings → Help → "Help improve the app"**. Reports
  stop being sent immediately; nothing needs restarting or updating.
- **Retention:** Google deletes the reports **after 90 days**.
- Google's privacy policy:
  [policies.google.com/privacy](https://policies.google.com/privacy) · data
  collected by Crashlytics:
  [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

## 12. Usage statistics (Firebase Analytics)

To know which parts of the app actually get used — and which nobody cares about
— we send **anonymous counters** to **Firebase Analytics**, a service of
**Google Ireland Limited** acting as a **data processor** on our behalf.

**What is sent:**

- That a **specific action** happened, identified by a fixed name we write
  ourselves: for example *"a contact was imported"*, *"a conversation was
  logged"*, *"the calendar was opened"* or *"the subscription screen was
  opened"*. It is a counter: the action and nothing else.
- **Device and app data**: model, operating system version, app version,
  language and approximate country inferred from the connection.
- A **random identifier generated by Analytics** for that installation, used so
  the same person is not counted a thousand times. It is not your name, your
  email or your Google account, and we cannot link it to you. If you clear the
  app's data or reinstall it, that identifier **is replaced by a new one**.
- Whether or not you have the Premium subscription, as a plain *yes/no*.

**What is NEVER sent:** your contacts, their names, phone numbers or emails,
your reminders, your conversation history, your labels or your notes. The action
names are a closed list written by us; nothing you type into the app goes in
there.

**There are no advertising identifiers either.** The app **expressly removes**
the advertising ID permission that libraries of this kind usually bring along,
and disables ad personalisation signals. There are no ads, no campaign
attribution and no profiling.

- **Why:** to decide what to improve and what to drop, and to understand where
  people get stuck. It is always read **in aggregate**, never person by person,
  because there is no person to look at.
- **Legal basis (GDPR):** legitimate interest (art. 6(1)(f)) in improving the
  app. Since that interest is ours and not yours, the switch on the next line is
  your right to object.
- **How to turn it off:** **Settings → Help → "Help improve the app"**, the same
  switch that turns off crash reports. Once off, nothing is sent, immediately; no
  restart or update needed.
- **How long it is kept:** **14 months** from that installation's last activity.
  After that, Google deletes the data automatically.
- Google's privacy policy:
  [policies.google.com/privacy](https://policies.google.com/privacy) · data
  collected by Analytics:
  [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

## 13. Children

Friendly Contact Reminder is **not directed at children under 13**. We do not knowingly
collect personal data from children. If you believe a child has provided us with
data, contact us and we will delete it.

## 14. Your rights (GDPR / UK GDPR)

As a user in the European Union, the United Kingdom or Switzerland, you have the
right to:

- **Access:** know what data we hold about you. Outside your device only three
  things are processed on our behalf: the **subscription record** in section 10,
  the **crash reports** in section 11 and the **usage statistics** in section 12;
  write to us and we will tell you exactly what the first one contains. We cannot
  hand you "yours" for the other two, because they are not tied to your identity
  (see section 15). The backups in sections 6 and 7 are in your hands, not ours.
- **Rectification:** you can edit or correct any data from within the app. The
  subscription record contains nothing you could rectify (it is a random
  identifier and your purchase status).
- **Erasure ("right to be forgotten"):** uninstalling the app or clearing its
  data from system settings removes everything stored locally, including
  imported contacts; your phone's address book is unaffected. To also delete the
  subscription record and the Drive backups, see **section 15**.
- **Objection and restriction of processing:** revoke the contacts or
  notifications permission from your operating system settings, disconnect Drive
  backup from Settings, and turn off crash reports and usage statistics in
  **Settings → Help → "Help improve the app"**. That switch is, specifically,
  your right to object to the only two kinds of processing we carry out under
  legitimate interest.
- **Portability:** the backup file in section 6 is, precisely, a complete export
  of your data in a machine-readable format. You can also request the
  subscription record from us.
- **Lodge a complaint:** with the Spanish Data Protection Agency
  ([aepd.es](https://www.aepd.es)) or the equivalent authority in your country.

To exercise any right, write to **miscoapps@gmail.com**.

## 15. How to request deletion of your data

**On your device:** uninstall the app or clear its data from system settings.
That immediately and permanently removes everything described in sections 4 and
5. Your phone's address book is unaffected.

**Backup files (section 6):** they are wherever you saved them, so you delete
them yourself, like any other file.

**Backups in Google Drive (section 7):** disconnect the account from
**Settings** and delete the app's folder from your Google Drive. They live in
your account, so deletion is entirely under your control and you do not need to
ask us.

**The subscription record (section 10):** write to **miscoapps@gmail.com** with
the subject *"Data deletion"*. We will delete your RevenueCat record **within a
maximum of 30 days** and confirm it by email. You do not need to give us any
personal data to request it.

**Crash reports (section 11):** ⚠️ we have to be honest here: **reports from one
specific person cannot be deleted**. They are not tied to your identity but to a
random installation identifier we cannot link to you, so there is no way to look
up "yours". What you can do is **turn them off in Settings**, and they stop being
sent immediately; any already sent are deleted automatically after 90 days.

**Usage statistics (section 12):** same case, same honesty. Google **does** allow
deleting the data of one specific installation, but only if you know the random
identifier Analytics assigned to it — and that identifier is shown to nobody:
you cannot see it and we cannot know which one is yours. What does work: **turn
them off in Settings** (nothing is sent from that moment on) and **clear the
app's data or reinstall it** — that replaces the identifier with a new one and
orphans the old one for good. Whatever was already sent is deleted on its own
**after 14 months**.

⚠️ Note that deleting that record **does not cancel your subscription**:
subscriptions are managed and cancelled from your Google Play (or Apple)
account, not from here. If you delete the record while a subscription is active,
the app may stop recognising your Premium access until you use the **Restore
purchases** option.

## 16. International transfers

The provider described in section 10 (**RevenueCat, Inc.**) is based in the
**United States**, so the data in that section is transferred outside the
European Economic Area. The transfer relies on the safeguards provided by the
GDPR for such cases (European Commission standard contractual clauses and/or the
EU–US Data Privacy Framework).

The **crash reports** (section 11) and the **usage statistics** (section 12) are
processed by **Google Ireland Limited**, but may be stored and processed on
**Google LLC** servers in the **United States** and in other countries where
Google operates, under the same GDPR safeguards (standard contractual clauses
and/or the EU–US Data Privacy Framework).

If you enable **Google Drive** backup (section 7), your data is stored on
**Google's** infrastructure, which may also process it outside the EEA under its
own safeguards. That transfer is made **by you, to your own account**: we
neither take part in it nor receive anything.

**No other data is transferred:** if you do not use backups, everything
described in sections 4 and 5 stays on your device.

## 17. Security

Information stored on your device uses the operating system's standard storage
mechanisms, protected by the app isolation it guarantees.

The data in sections 10, 11 and 12 travels **encrypted in transit** (HTTPS/TLS) to
the relevant provider's servers, and the same applies to the Google Drive upload
in section
7. As there is no user account or password belonging to the app, there are no
credentials of ours that could be compromised.

⚠️ **The backup file is not encrypted** (sections 6 and 7): it is compressed,
which is not the same thing. Its security depends on where you store it.

## 18. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top
reflects the current version. Significant changes will be announced in the next
app update.

## 19. Contact

For any questions about this policy or about how your data is processed, write
to us at:

**miscoapps@gmail.com**
