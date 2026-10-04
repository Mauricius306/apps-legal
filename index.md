---
layout: default
title: Datenschutzerklärung
---

# Datenschutzerklärung

**Stand:** 4. Oktober 2026

Diese Erklärung gilt für die iPhone-App, auf die von ihrer Seite im App Store
verwiesen wird — im Folgenden „diese App".

## Verantwortlicher

```
Carl Maurice Pötter
Ravensberger Str. 51
42117 Wuppertal

E-Mail: mp.appstudio@gmail.com
```

## Alles bleibt auf deinem Gerät

Diese App hat keinen Server und kein Benutzerkonto. Es gibt keine
Registrierung, keine Anmeldung und keine Synchronisierung zwischen Geräten.
Deine Trainingsdaten liegen ausschließlich im geschützten Speicherbereich der
App auf deinem iPhone. Sie verlassen das Gerät nur, wenn du sie selbst
exportierst oder teilst.

Der Anbieter hat zu keinem Zeitpunkt Zugriff auf deine Trainingsdaten.

## Welche Daten gespeichert werden

Alles, was du selbst eingibst:

- Übungen mit Namen, Typ, Geräten, Muskelgruppen und Bewegungsmuster
- Workout-Vorlagen und ihre Zuordnung zu Wochentagen
- Trainingssitzungen mit Datum, Dauer, Pausen und allen erfassten Satzwerten
- Notizen zu einer Sitzung oder einem einzelnen Satz
- Einstellungen: verfügbare Hantelscheiben, Stangengewicht, Aufwärmschemata,
  Benchmark-Kategorie, Farbschema
- Dein Name, sofern du im Onboarding einen eingibst — er dient allein der
  Anrede in der App

Welche Messwerte pro Satz erfasst werden, legst du pro Übung selbst fest:
Wiederholungen, Gewicht (kg), Dauer (Sekunden), Distanz (Meter), Gerätestufen,
angestrebte und erreichte Anstrengung (Reps in Reserve) sowie **Puls in
Schlägen pro Minute**.

Kann die App beim Start einen Trainingsstand nicht lesen, legt sie vorher eine
unveränderte Sicherung davon auf dem Gerät ab. Sie dient allein der Rettung
deiner Daten und ist unter „Mehr → Daten" erreichbar.

### Gesundheitsdaten

Die Pulswerte, die du erfassen kannst, sind Gesundheitsdaten im Sinne von
Art. 4 Nr. 15 DSGVO. Dasselbe gilt für Werte, aus denen sich Schlüsse auf deine
körperliche Verfassung ziehen lassen — also auch für Trainingslasten,
Anstrengungsangaben und Notizen zu deinem Befinden.

Diese Daten werden ausschließlich lokal gespeichert und vom Anbieter nicht
verarbeitet. Die Erhebung ist freiwillig: Du entscheidest pro Übung, ob das
Puls-Feld überhaupt erfasst wird, und in keiner mitgelieferten Übung ist es
vorgegeben.

Diese App greift **nicht** auf Apple Health zu — sie liest dort nichts und
schreibt dort nichts hinein.

## Der Kauf von „Pro"

Der einmalige Kauf, der die zusätzlichen Funktionen freischaltet, läuft
vollständig über Apple: Apple verarbeitet die Zahlung, verwaltet die
Berechtigung an deiner Apple-ID und teilt dem Anbieter weder deinen Namen noch
deine Zahlungsdaten mit. Auf dem Gerät wird allein gespeichert, **dass** der
Kauf besteht; dafür gilt Apples Datenschutzerklärung.

## Die einzige Verbindung, die diese App von sich aus aufbaut

Diese App kann App-Aktualisierungen außerhalb des App Stores nachladen. Beim
Start wird dazu ein Server von Expo abgefragt. Übertragen werden dabei nur die
technischen Daten, die für die Zustellung des richtigen Update-Pakets nötig
sind: die IP-Adresse des Geräts, die Plattform, die Laufzeit-Version der App
und der konfigurierte Kanal. **Trainingsdaten werden dabei nicht übertragen.**

Empfänger ist Expo (Expo Project, 650 Mission St, San Francisco, CA, USA); die
Übermittlung erfolgt in die USA. Rechtsgrundlage ist das berechtigte Interesse
an der Auslieferung von Fehlerbehebungen (Art. 6 Abs. 1 lit. f DSGVO). Was Expo
dabei erhebt und wie lange es gespeichert wird, steht in Expos eigener
Datenschutzerklärung: <https://expo.dev/privacy>

### Was nicht stattfindet

- **Keine Push-Nachrichten.** Diese App holt kein Push-Token. Die Mitteilung
  zum Pausen-Timer wird ausschließlich lokal auf dem Gerät geplant.
- **Keine Analyse, kein Tracking, keine Werbung, keine Absturzberichte.** Es ist
  keine entsprechende Bibliothek enthalten, es werden keine Nutzungsprofile
  erstellt und keine Werbe-Identifier gelesen.
- **Die Live Activity überträgt nichts.** Der Pausen-Timer und der nächste Satz
  auf dem Sperrbildschirm und in der Dynamic Island laufen vollständig auf dem
  Gerät. Die Sekunden zählt iOS selbst aus zwei Zeitstempeln herunter. Beendest
  oder verwirfst du das Training, verschwindet die Anzeige; nach einem Absturz
  räumt die App beim nächsten Start auf.

Unabhängig von dieser App erhebt Apple eigene Daten, wenn du eine App aus dem
App Store lädst, und stellt Entwicklern aggregierte Absturzstatistiken bereit.
Darauf hat der Anbieter dieser App keinen Einfluss; dafür gilt die
Datenschutzerklärung von Apple.

## Wann Daten das Gerät verlassen — immer nur auf dein Auslösen

**Backup exportieren** („Mehr → Daten"): Dein vollständiger Bestand als
JSON-Datei oder als Textcode. Die Datei wird in einen temporären Ordner
geschrieben, über das iOS-Teilen-Fenster übergeben und danach wieder gelöscht.
Wohin sie geht — AirDrop, Mail, iCloud Drive, eine andere App — entscheidest du
im Teilen-Fenster. Der Export enthält alle oben genannten Daten, einschließlich
der Pulswerte und deines Namens. Der Anbieter erfährt davon nichts.

**Plan teilen** („Mehr → Daten"): Nur die von dir gewählten Workout-Vorlagen
und die Übungen, die sie brauchen — keine Trainingssitzungen, keine Pulswerte,
keinen Namen, keine Einstellungen, keinen Wochenplan.

**Zwischenablage:** An drei Stellen schreibt die App Text in die Zwischenablage
— den Backup-Code, den Prompt des Plan-Generators und, im Entwicklerbereich,
den Rohzustand als JSON. Was in der Zwischenablage liegt, kann von anderen Apps
gelesen werden; iOS fragt bei einem Einfügeversuch in der Regel um Erlaubnis.

**Trainingsplan mit KI erstellen:** Die App kopiert einen vorformulierten Text
in die Zwischenablage. Dieser Text ist eine feste Vorlage und enthält **keine
deiner Daten**. Welchen KI-Dienst du damit benutzt, entscheidest du; die App
nennt nur Beispiele und öffnet selbst keinen Dienst und keine Internetseite.
Was du dort eingibst, gibst du dort ein — dafür gilt die Datenschutzerklärung
dieses Dienstes.

**Links in Notizen:** Schreibst du eine Internetadresse in eine Notiz, wird sie
als Link dargestellt. Tippst du darauf, geht der Aufruf an den Betreiber der
aufgerufenen Seite.

**Datei importieren:** Die App liest nur die eine Datei, die du im
iOS-Dateifenster auswählst, und greift auf keine anderen zu.

**Entwicklerbereich:** In der aus dem App Store geladenen Fassung ist er
**nicht erreichbar**. In Testfassungen über TestFlight schaltet siebenmaliges
Tippen auf die Versionsnummer im Mehr-Tab einen Bereich mit Diagnose,
Rohdaten, Testdaten und Wartung frei. Er sendet nichts; die einzige Stelle, an
der dort Daten herausgehen können, ist das Kopieren des Rohzustands in die
Zwischenablage.

## Berechtigungen

| Berechtigung     | Wofür                                                                 | Wann gefragt                          |
| ---------------- | --------------------------------------------------------------------- | ------------------------------------- |
| **Mitteilungen** | Hinweis, wenn der Pausen-Timer abläuft und die App im Hintergrund ist | Beim ersten Start eines Pausen-Timers |

Das ist die einzige Berechtigung. Diese App fragt **nicht** nach Kamera,
Mikrofon, Fotos, Standort, Kontakten, Kalender, Bluetooth, Bewegungsdaten oder
Apple Health. Verweigerst du die Mitteilungen, funktioniert die App vollständig
weiter — der Timer läuft dann nur, solange die App im Vordergrund ist.

Für die Live Activity fragt die App keine Berechtigung an. Ob Live-Aktivitäten
erscheinen, steuerst du in den iOS-Einstellungen der App.

## Speicherdauer und Löschung

Die Daten bleiben auf deinem Gerät, bis du sie löschst. Es gibt keine
automatische Löschung und keine Aufbewahrung beim Anbieter.

- **Einzelne Einträge:** direkt in der App
- **Alles:** „Mehr → Daten → App zurücksetzen", mit zweistufiger Bestätigung
- **Vollständig:** die App vom Gerät löschen. iOS entfernt dabei den gesamten
  Speicherbereich der App, einschließlich des Bereichs für die Live Activity

### iPhone-Backup

**Die Trainingsdaten sind Teil des iPhone-Backups**, sofern du ein Backup
nutzt. Das ist eine bewusste Einstellung dieser App: Ohne sie wäre dein Bestand
nach einer Wiederherstellung oder einem Gerätewechsel leer.

- **Bei einem iCloud-Backup** liegt eine Kopie in deinem iCloud-Konto. Apple
  verschlüsselt iCloud-Backups bei der Übertragung und bei der Speicherung. Mit
  aktiviertem „Erweiterter Datenschutz" ist das Backup
  Ende-zu-Ende-verschlüsselt und nur deine Geräte können es entschlüsseln; ohne
  diese Einstellung verwaltet Apple die Schlüssel mit. Verantwortlich für dieses
  Backup ist Apple.
- **Bei einem Backup auf einen Rechner** liegt die Kopie dort. Ist das Backup in
  der Finder- bzw. iTunes-Einstellung verschlüsselt, ist auch diese Kopie
  verschlüsselt.
- **Der Anbieter dieser App hat auf keine dieser Kopien Zugriff.**

Das betrifft alle Daten, also auch die Pulswerte und deinen Namen. Willst du
das nicht, kannst du die App in den iPhone-Einstellungen unter „Apple-ID →
iCloud → Backup" von der Sicherung ausnehmen — dann ist der Bestand allerdings
nach einem Gerätewechsel weg, und dein einziger Weg zurück ist ein Export.

## Deine Rechte

Dir stehen nach DSGVO die Rechte auf Auskunft (Art. 15), Berichtigung
(Art. 16), Löschung (Art. 17), Einschränkung (Art. 18), Datenübertragbarkeit
(Art. 20) und Widerspruch (Art. 21) zu, außerdem das Recht auf Beschwerde bei
einer Aufsichtsbehörde (Art. 77).

Zuständig ist die **Landesbeauftragte für Datenschutz und Informationsfreiheit
Nordrhein-Westfalen**:

```
Landesbeauftragte für Datenschutz und Informationsfreiheit
Nordrhein-Westfalen
Postfach 20 04 44
40102 Düsseldorf

Hausadresse: Kavalleriestr. 2–4, 40213 Düsseldorf
Telefon: 0211 38424-0
E-Mail: poststelle@ldi.nrw.de
```

Quelle der Anschrift: [ldi.nrw.de — Impressum](https://www.ldi.nrw.de/impressum),
abgerufen am 4. Oktober 2026.

In der Praxis bedeutet das hier:

- **Auskunft und Datenübertragbarkeit** übst du selbst aus — der Export unter
  „Mehr → Daten" gibt dir deinen vollständigen Bestand in einem offenen,
  maschinenlesbaren Format (JSON).
- **Berichtigung und Löschung** ebenso: jeder Eintrag ist in der App
  bearbeitbar und löschbar.
- Für Anfragen, die die Update-Prüfung bei Expo betreffen, wende dich an die
  oben genannte Kontaktadresse.

## Kinder

Diese App richtet sich nicht an Kinder.

## Änderungen dieser Erklärung

Ändert sich an der Datenverarbeitung etwas — insbesondere, falls eine
Synchronisierung, ein Konto, ein iCloud-Backup oder eine Auswertung hinzukommt
— wird diese Erklärung vor der Veröffentlichung der betreffenden Version
angepasst.

---

[Support](support.html)
