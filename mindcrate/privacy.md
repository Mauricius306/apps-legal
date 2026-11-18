---
layout: default
title: Mindcrate Privacy Policy
---

# Mindcrate Privacy Policy

**Last updated:** 18 November 2026 (sixth version: Mindcrate Plus added)

This is an English translation for convenience. The
[German version](datenschutz.html) is the legally binding one.

This policy applies to **Mindcrate**, a task app for iPhone and a web app in the
browser. The provider's other apps are covered by the
[general privacy policy](../index.html) (German).

## Controller

```
Carl Maurice Pötter
Ravensberger Str. 51
42117 Wuppertal
Germany

Email: mp.appstudio@gmail.com
```

## In short

Mindcrate stores your tasks in a database so they are the same on your iPhone
and your computer. You need an account with an email address and a password.
The database is run by the service provider **Supabase**; the data is stored
in a data centre in **Frankfurt am Main, Germany**. The web app is delivered
via **Cloudflare**, and account emails are sent by **Brevo**. If you connect
Mindcrate to **Claude** or **ChatGPT** yourself, the chosen service reads and
changes your tasks – only with your consent and until you revoke it. If you take
out **Mindcrate Plus**, you buy through Apple or, in the browser, through Paddle; purchases are verified by
**RevenueCat**. There are no ads, no tracking and no analysis of your behaviour.

## What data is processed

### Account

- Email address
- Password – only a hash is stored, never the password itself
- Time of registration and of the last sign-in

### Content you enter

- Tasks with title, notes, status, priority, due date, recurrence, reminder
  settings (Plus), order and
  the way they were created (app, web, import, Claude, ChatGPT, mail)
- Subtasks
- Projects with name, colour, priority, description and order
- Times of creation, change and completion

You decide what you write in titles, notes and project descriptions. Please do
not enter data about other people that you are not allowed to share.

### Technical data during sync

Every connection to the database technically involves your device's IP
address and the time and type of the request. Supabase logs this information
to run and secure the service and deletes the logs after a short time.

### On your device

So that the app works offline and no input is lost, the following is stored
on the device (iPhone: app storage, browser: local storage):

- your sign-in (session key)
- a copy of your tasks, subtasks and projects
- changes that have not been sent yet
- settings: language, colour scheme, light/dark, handedness, list view and
  sorting, reminders, morning summary and the number on the app icon
- a counter of completed tasks and whether you have already been asked for a
  rating (iPhone, see below)
- in the browser: the files of the web app itself (service worker), so it also
  starts offline – no tasks; those are in local storage as above
- the focus time per task (total of completed focus minutes), only for display
  in the task
- the focus timer: settings, current phase, remaining time, number of rounds
  and the selected task. It is **not** sent to the server; there is no
  analysis or statistics about it.

When you sign out, the app removes the local copy from the device. Exception:
if changes are still waiting to be sent, they stay on the device (after a
notice) so nothing is lost, and are sent after your next sign-in.

## Purpose and legal basis

- **Account and content:** to provide the app and sync your tasks between your
  devices (Art. 6(1)(b) GDPR).
- **Logs with IP address:** for secure operation and to detect abuse;
  legitimate interest under Art. 6(1)(f) GDPR.
- **Connection to Claude or ChatGPT:** only if you set it up and consent
  yourself, to provide the function you requested (Art. 6(1)(b) GDPR).
- **Mail to Mindcrate:** only if you create an address; for you Art. 6(1)(b)
  GDPR, for third-party data in forwarded emails see the section
  “Mail to Mindcrate”.

## Recipient: Supabase

Database, sign-in and real-time sync run on **Supabase Pte. Ltd.**, 65 Chulia
Street #38-02/03, OCBC Centre, Singapore 049513, as a processor under
Art. 28 GDPR. The data is stored in the Frankfurt am Main region (EU). For
access from countries outside the EU, for example for maintenance and support
by Supabase, the EU Commission's Standard Contractual Clauses apply
(Art. 46(2)(c) GDPR), which are part of Supabase's data processing agreement:
<https://supabase.com/legal/dpa>

Emails to confirm your address, change your address or reset your password
are triggered by Supabase and sent via Brevo (next section). The link in them
opens the web app.

## Recipient: Brevo (account emails)

The emails about your account (confirm address, change address, reset
password) are sent by **Brevo SAS**, 17 rue de Salneuve, 75017 Paris, France
(German branch: Brevo GmbH, Köpenicker Str. 126, 10179 Berlin), as a processor
under Art. 28 GDPR. Brevo receives your email address and the content of the
respective email with the link; Brevo logs delivery, time and technical
responses (e.g. undeliverable). For these emails Brevo also technically records
whether they are opened and whether links in them are clicked (tracking pixel,
links redirected via Brevo); this cannot be switched off in the plan used.
Mindcrate does not evaluate this information. There are no newsletters and no
advertising. Processing takes place in the EU. The legal basis is the
performance of the terms of use (Art. 6(1)(b) GDPR). Privacy at Brevo:
<https://www.brevo.com/legal/privacypolicy/>, data processing (part of the
terms of use): <https://www.brevo.com/legal/termsofuse/>

## Recipient: Cloudflare (web app)

The files of the web app are delivered by **Cloudflare, Inc.**, 101 Townsend
Street, San Francisco, CA 94107, USA, via Cloudflare Workers. When the app is
loaded, Cloudflare technically receives IP address, time, requested address
and browser identifier; Cloudflare processes them for delivery and protection
against attacks. Your tasks do **not** pass through Cloudflare but go directly
between browser and Supabase. Cloudflare is certified under the EU-US Data
Privacy Framework (Art. 45 GDPR); in addition, the Standard Contractual Clauses
in its data processing agreement apply: <https://www.cloudflare.com/dpa/>. The
legal basis is the legitimate interest in secure and fast delivery
(Art. 6(1)(f) GDPR).

### Security check at sign-in and registration

To block automated registrations and sign-in attempts, **Cloudflare
Turnstile** (Cloudflare, Inc., address above) may be included when you sign
in, register or reset your password. Turnstile checks technical features of
the device and browser (e.g. IP address, browser identifier, screen size) in
the browser or in a browser window embedded in the app, and gives the app a
token that Supabase verifies. According to Cloudflare, Turnstile does not set
advertising cookies and does not use the data for advertising. The legal basis
is the legitimate interest in protecting accounts and the service from abuse
(Art. 6(1)(f) GDPR). Privacy at Cloudflare:
<https://www.cloudflare.com/turnstile-privacy-policy/>

## Backup of server data

So that content is not lost in case of a technical failure, the database is
backed up once a week: your content (tasks, subtasks, projects and settings on
the server) and your account (email address, password hash, timestamps).
Sessions and sign-in tokens are not backed up. The backup is **encrypted**
before it is stored; only the provider can open it, with a key that is not
held by the storage service.

The encrypted file is stored with **GitHub, Inc.**, 88 Colin P. Kelly Jr.
Street, San Francisco, CA 94107, USA, in the provider's private area (GitHub
Actions). GitHub only sees the encrypted file. GitHub is certified under the
EU-US Data Privacy Framework (Art. 45 GDPR). Each backup is deleted
automatically after **60 days**. The legal basis is the legitimate interest in
protecting your content from loss (Art. 6(1)(f) GDPR) and the performance of
the terms of use (Art. 6(1)(b) GDPR).

## Mindcrate Plus (subscription, optional)

Mindcrate Plus is a subscription you can take out in the iPhone app or in the browser. It unlocks
“Plan your day”, the connection to Claude and ChatGPT and Mail to Mindcrate.
Without Plus, the rest of the app remains fully usable.

- **Purchase in the iPhone app** is handled by **Apple** (App Store). The provider
  does not receive payment data; Apple's privacy policy applies.
- **Purchase verification:** **RevenueCat, Inc.**, 1032 E Brandon Blvd #3003,
  Brandon, FL 33511, USA, verifies Apple's purchase receipts on behalf of the
  provider and reports whether Plus is active (processor under Art. 28 GDPR).
  RevenueCat receives your Mindcrate account ID (a random identifier, not your
  email address), the purchase history for Mindcrate Plus (product, times,
  expiry, trial, country) and, technically, IP address, device type and app
  version. For the transfer to the USA, the EU Commission's Standard Contractual
  Clauses (Art. 46(2)(c) GDPR) in the data processing agreement apply:
  <https://www.revenuecat.com/dpa>. RevenueCat is only set up once you are
  signed in.
- **Purchase in the browser:** If you buy Plus in the browser, it is sold by
  **Paddle.com Market Limited**, 30 Old Bailey, London EC4M 7AU,
  United Kingdom, as an independent seller (merchant of record). Paddle processes
  your payment and billing data (name, email, country, postcode, payment method)
  under its own privacy policy: <https://www.paddle.com/legal/privacy>. Your
  Mindcrate account ID is also passed to Paddle so the purchase is linked to
  your account. An EU adequacy decision applies to the United Kingdom
  (Art. 45 GDPR). RevenueCat receives the purchase history from Paddle as
  described above.
- **Entitlement:** Whether and until when Plus is active is stored with your
  account in Supabase (Frankfurt) so Plus works on all your devices.
- **Legal basis:** performance of the subscription contract (Art. 6(1)(b) GDPR);
  retention of purchase data where commercial and tax law require it
  (Art. 6(1)(c) GDPR).
- **Cancel** with Apple (Settings → your name → Subscriptions) or via the link in
  Paddle's purchase confirmation. Deleting
  your account deletes the entitlement in Supabase; it does not cancel an active
  subscription with Apple.

## Connection to Claude or ChatGPT (optional)

You can add Mindcrate as a connector in **Claude** (Anthropic) or **ChatGPT**
(OpenAI). This never happens without your action.

- **Sign-in:** The service sends you to Mindcrate's consent page. There you see
  who wants access and what is allowed. Only after “Allow” does the service
  receive an access key, issued by Supabase. The service does not get your
  password.
- **What the service may do:** read tasks and projects, create, change and
  complete tasks. **It cannot delete anything**, and it has no access to your
  account or password.
- **Which data flows:** If you ask the service about your tasks, the requested
  content (title, notes, status, priority, due date, project) goes to it. New
  tasks are stored with the origin “Claude” or “ChatGPT”.
- **Responsibility:** What Anthropic or OpenAI do with this content depends on
  your contract with the respective service and its privacy policy; the
  provider of Mindcrate has no influence on this. Both companies are based in
  the USA.
- **Revocation:** anytime in the app under *More → Connections → Disconnect*.
  The key is then invalid. Supabase stores connected services and the time of
  consent until you disconnect them.

## Showing calendars (read-only)

The calendar tab can show events from up to five of your own calendars
(Google Calendar, iCloud, Outlook). You connect them yourself under
More → Calendars; without a connected calendar nothing happens.

- **Source:** the private iCal address of each calendar that you paste, and a
  name you choose. Both are stored with your account in Supabase (Frankfurt).
  Afterwards the app **cannot read the address back** – only the server
  function that fetches the events reads it. Only addresses of the providers
  named above are accepted.
- **Process:** The server function fetches the address from the provider,
  parses the events and passes only **title, day and times** to the app.
  Location, description and attendees stay on the server and are discarded.
- **Storage:** Events are not stored in the database. The server keeps a
  request in memory for at most five minutes. The device keeps a copy of the
  most recently loaded events (about two months back, four ahead) so the
  calendar shows something offline.
- **Deletion:** If you remove a calendar, its address is deleted immediately.
  Deleting the account deletes all calendar entries as well.
- **Calendar provider:** When fetching, Google, Apple or Microsoft receive the
  request from Supabase's server, not from your device. The calendar itself is
  covered by the respective provider's privacy policy.
- **Legal basis:** providing the requested function (Art. 6(1)(b) GDPR).

There are no other recipients. The provider does not sell or share data.

## Mail to Mindcrate (optional)

Under *More → Mail to Mindcrate* you can create a personal, secret email
address. An email to this address becomes a task in your inbox. Without a
created address none of this happens.

- **What is stored:** the subject (as title), name and address of the sender
  and the text of the email (as a note, at most 10,000 characters).
  Attachments are discarded; images and formatting are not taken over.
- **Path of the email:** The email goes to **Cloudflare Email Routing**
  (Cloudflare, Inc., address above). A program at Cloudflare (Email Worker)
  parses it and passes the information above to Supabase, where the task is
  created. According to Cloudflare, no email content is stored; sender and
  recipient address, time and the mail servers involved are processed
  technically. Transfer to the USA as described in the Cloudflare section.
- **Third-party data:** If you forward an email, it often contains another
  person's name, address and text. We process these on your behalf so you can
  handle the email as a task; the legal basis is the legitimate interest in
  organising your tasks (Art. 6(1)(f) GDPR). Please only forward emails you
  are allowed to use for this.
- **Anyone who knows the address** can send you tasks. You can create a new
  address at any time (the old one then stops working) or switch the function
  off; the address is deleted. Tasks already created remain until you delete
  them.
- Abuse protection: at most 30 emails per address and hour; emails over 1 MB
  and emails to unknown addresses are rejected.

## What does not happen

- **No ads, no tracking, no analytics.** No such library is included.
- **No cookies for advertising or analytics.** The web app only uses the
  browser's local storage for the purposes above, which are necessary to run
  it.
- **No push messages from a server, no location, no contacts, no access to the
  device calendar, no camera.**
- **No sharing with AI services without you.** Only a service you connect
  yourself gets access (see above).

### Focus timer

- **Notifications:** When you start the timer for the first time, the app asks
  whether it may send you notifications. It uses them to schedule a
  notification **on the device** for the end of the focus or break time.
  Nothing is sent to a server. If you decline, the timer still runs.
- **iOS Focus (“Do Not Disturb”):** If you switch it on, the app opens the iOS
  Shortcuts app when a focus phase starts and passes it the name of the
  shortcut and the minutes until the end of the phase. You decide what the
  shortcut does; the app reads nothing back from it.
- **Live Activity:** While the timer runs, the iPhone shows remaining time,
  phase and the title of the selected task on the lock screen and in the
  Dynamic Island. For this the app stores this information in a protected
  storage area that only the app and its extension can read. The display runs
  entirely on the device. Whether Live Activities appear is controlled in the
  app's iOS settings. Note: on the lock screen the task title is visible
  without unlocking.

### Reminders and number on the app icon (iPhone)

If you switch on reminders under *More → Notifications*, the app schedules
notifications **on the device** for tasks with a due date and time (task title
and time). The number on the app icon shows how many tasks are due or overdue
today. The device calculates both itself; there is no push server. Both are off
by default. Note: depending on your iOS settings, notifications may be visible
on the lock screen.

### “Mindcrate Heute” widget (iPhone)

If you place the widget on the home or lock screen, the app writes the tasks
due today and overdue (title, time, project colour) to storage shared by app
and widget **on the device** (app group). None of it goes to a server. On the
lock screen the titles are visible without unlocking. After signing out, the
widget no longer shows titles.

### Share sheet (iPhone)

Via *Share → Mindcrate* you can take over text or a link from another app as a
task. The extension passes the shared content to the app through the shared
storage on the device; there it is saved and synced like a task you typed.
For links, iOS takes over the page title of the shared page.

### Morning summary (iPhone)

If you want, a notification in the morning shows how many tasks are due that
day. The device schedules it itself; nothing goes to a server. It is off by
default.

### App Store rating (iPhone)

After 50 completed tasks, at the earliest one week after the first launch, the
app asks **once** for a rating using Apple's dialog. The app does not learn
whether or how you rate; Apple processes the rating.

### Export data

Under *More → Export data* the app creates a file (JSON or CSV) on the device
with your projects, tasks and subtasks. In the browser it is downloaded, on
the iPhone it is offered via the share sheet. You decide where it goes; the
app sends it nowhere.

### Restore backup

Under *More → Restore backup* the app reads a previously exported JSON file
that you select and creates only what is missing in your account. The file
itself is not uploaded, only the entries created from it, like any other
input.

### Report a problem

*More → Report a problem* opens your mail app with a prepared email to the
address above. It contains app version, device type, system version, sync
state and the last error message, but no tasks. Only what you send yourself is
sent.

### Abuse protection

The server functions (connection to Claude/ChatGPT, calendar, account
deletion) count in memory for about one minute how many requests an account
makes and slow down when there are too many. Nothing is stored. In addition,
per-account limits apply (5,000 tasks, 200 projects, 100 steps per task, notes
up to 20,000 characters) so that a single account cannot overload the service
for everyone else.

### Links in notes

If you write a web address in a note, it is shown as a link. If you tap it,
the page opens in the browser; the privacy policy of its operator then
applies.

## Retention and deletion

Your content is stored until you delete it. Completed tasks move to the
archive after seven days but are not deleted.

- **Tasks** go to the **trash** first when deleted and can be restored there
  for 30 days. After that – or immediately via “Delete permanently” or “Empty
  trash” – they are deleted permanently, including subtasks.
- **Subtasks and projects:** delete them directly in the app. The deletion is
  carried out on the server at the next sync.
- Completed tasks older than 90 days are only loaded by the app on request
  (“Load older archive”); on the server they remain until deleted.
- **Delete your account completely:** in the app under *More → Delete account*
  or by email to the address above. Together with the account, all tasks,
  subtasks and projects, the address for Mail to Mindcrate, the Plus
  entitlement and the permissions for Claude or ChatGPT are deleted; the app also removes the copy of this data
  from the device.

Deleted data may still be contained in the encrypted weekly backups (see
“Backup of server data”) and disappears from them after 60 days at the latest.

## Your rights

Under the GDPR you have the right of access (Art. 15), rectification
(Art. 16), erasure (Art. 17), restriction (Art. 18), data portability
(Art. 20) and objection (Art. 21). Write to the address above.

You can also lodge a complaint with a supervisory authority (Art. 77). The
competent authority is the **State Commissioner for Data Protection and
Freedom of Information of North Rhine-Westphalia**:

```
Landesbeauftragte für Datenschutz und Informationsfreiheit
Nordrhein-Westfalen
Postfach 20 04 44
40102 Düsseldorf
Germany

Street address: Kavalleriestr. 2–4, 40213 Düsseldorf
Phone: +49 211 38424-0
Email: poststelle@ldi.nrw.de
```

## Children

This app is not directed at children.

## Changes to this policy

If anything changes in the data processing – for example if the app writes
events to the calendar or connects calendars via a Google sign-in – this
policy will be updated before the respective version.

---

[Support](support.html) · [Imprint](../impressum.html) (German) · [Datenschutzerklärung (German, binding)](datenschutz.html)
