---
layout: default
title: Datenschutzerklärung Mindcrate
---

# Datenschutzerklärung Mindcrate

**Stand:** 11. November 2026 (Fokus-Timer, Web-App bei Cloudflare, Verbindung mit Claude/ChatGPT, Google Kalender ergänzt)

Diese Erklärung gilt für **Mindcrate**, eine Aufgaben-App für iPhone und als
Web-App im Browser. Für die anderen Apps des Anbieters gilt die
[allgemeine Datenschutzerklärung](../index.html).

## Verantwortlicher

```
Carl Maurice Pötter
Ravensberger Str. 51
42117 Wuppertal

E-Mail: mp.appstudio@gmail.com
```

## Kurz gesagt

Mindcrate speichert deine Aufgaben in einer Datenbank, damit sie auf iPhone und
Computer gleich sind. Dafür brauchst du ein Konto mit E-Mail-Adresse und
Passwort. Die Datenbank betreibt der Dienstleister **Supabase**, die Daten
liegen in einem Rechenzentrum in **Frankfurt am Main**. Die Web-App wird über
**Cloudflare** ausgeliefert. Verbindest du Mindcrate selbst mit **Claude** oder
**ChatGPT**, liest und ändert der gewählte Dienst deine Aufgaben – nur nach deiner
Zustimmung und bis du sie widerrufst. Es gibt keine Werbung, kein Tracking und
keine Auswertung deines Verhaltens.

## Welche Daten verarbeitet werden

### Konto

- E-Mail-Adresse
- Passwort – gespeichert wird nur ein Hash, nicht das Passwort selbst
- Zeitpunkte der Registrierung und der letzten Anmeldung

### Inhalte, die du eingibst

- Aufgaben mit Titel, Notizen, Status, Priorität, Frist, Wiederholung,
  Reihenfolge und dem Weg, auf dem sie angelegt wurden (App, Web, Import,
  Claude, ChatGPT)
- Unteraufgaben
- Projekte mit Name, Farbe und Reihenfolge
- Zeitpunkte des Anlegens, Änderns und Erledigens

Was du in Titel und Notizen schreibst, bestimmst du selbst. Bitte trag dort
keine Daten anderer Menschen ein, die du nicht weitergeben darfst.

### Technische Daten beim Abgleich

Bei jeder Verbindung zur Datenbank fallen technisch die IP-Adresse deines
Geräts, Zeitpunkt und Art der Anfrage an. Supabase protokolliert diese Angaben
für den Betrieb und die Sicherheit des Dienstes und löscht die Protokolle nach
kurzer Zeit.

### Auf deinem Gerät

Damit die App auch ohne Netz funktioniert und keine Eingabe verloren geht,
liegen auf dem Gerät (iPhone: App-Speicher, Browser: lokaler Speicher):

- deine Anmeldung (Sitzungsschlüssel)
- eine Kopie deiner Aufgaben, Unteraufgaben und Projekte
- Änderungen, die noch nicht übertragen sind
- Einstellungen: Farbschema, Hell/Dunkel, Bedienhand, Ansicht und Sortierung
  der Liste
- der Fokus-Timer: Einstellungen, aktuelle Phase, Restzeit, Zahl der Runden und
  die gewählte Aufgabe. Er wird **nicht** an den Server übertragen; es gibt
  keine Auswertung oder Statistik darüber.

Nach dem Abmelden bleibt die lokale Kopie auf dem Gerät, bis du dich wieder
anmeldest oder die App löschst bzw. die Website-Daten im Browser entfernst.

## Zweck und Rechtsgrundlage

- **Konto und Inhalte:** um dir die App bereitzustellen und deine Aufgaben
  zwischen deinen Geräten abzugleichen (Art. 6 Abs. 1 lit. b DSGVO).
- **Protokolle mit IP-Adresse:** für den sicheren Betrieb und um Missbrauch
  zu erkennen; berechtigtes Interesse nach Art. 6 Abs. 1 lit. f DSGVO.
- **Verbindung mit Claude oder ChatGPT:** nur, wenn du sie selbst einrichtest
  und zustimmst, um die Funktion bereitzustellen, die du angefordert hast
  (Art. 6 Abs. 1 lit. b DSGVO).

## Empfänger: Supabase

Datenbank, Anmeldung und Abgleich in Echtzeit laufen über **Supabase Pte.
Ltd.**, 65 Chulia Street #38-02/03, OCBC Centre, Singapur 049513, als
Auftragsverarbeiter nach Art. 28 DSGVO. Die Daten werden in der Region
Frankfurt am Main (EU) gespeichert. Für Zugriffe aus Ländern außerhalb der EU,
etwa im Rahmen von Wartung und Support durch Supabase, gelten die
Standardvertragsklauseln der EU-Kommission (Art. 46 Abs. 2 lit. c DSGVO), die
Teil des Auftragsverarbeitungsvertrags von Supabase sind:
<https://supabase.com/legal/dpa>

E-Mails zur Bestätigung der Adresse oder zum Zurücksetzen des Passworts
verschickt ebenfalls Supabase.

## Empfänger: Cloudflare (Web-App)

Die Dateien der Web-App liefert **Cloudflare, Inc.**, 101 Townsend Street,
San Francisco, CA 94107, USA, über den Dienst Cloudflare Pages aus. Beim Aufruf
fallen dort technisch IP-Adresse, Zeitpunkt, aufgerufene Adresse und
Browserkennung an; Cloudflare verarbeitet sie für Auslieferung und Schutz vor
Angriffen. Deine Aufgaben laufen **nicht** über Cloudflare, sondern direkt
zwischen Browser und Supabase. Cloudflare ist unter dem EU-US Data Privacy
Framework zertifiziert (Art. 45 DSGVO); zusätzlich gelten die
Standardvertragsklauseln im Auftragsverarbeitungsvertrag:
<https://www.cloudflare.com/dpa/>. Rechtsgrundlage ist das berechtigte Interesse
an einer sicheren und schnellen Bereitstellung (Art. 6 Abs. 1 lit. f DSGVO).

## Verbindung mit Claude oder ChatGPT (freiwillig)

Du kannst Mindcrate als Connector in **Claude** (Anthropic) oder **ChatGPT**
(OpenAI) eintragen. Ohne dein Zutun passiert das nie.

- **Anmeldung:** Der Dienst leitet dich zur Zustimmungsseite von Mindcrate. Dort
  siehst du, wer zugreifen will und was erlaubt ist. Erst mit „Zulassen" erhält
  der Dienst einen Zugangsschlüssel, ausgestellt von Supabase. Dein Passwort
  bekommt der Dienst nicht.
- **Was der Dienst darf:** Aufgaben und Projekte lesen, Aufgaben anlegen,
  ändern und als erledigt markieren. **Löschen kann er nichts**, an Konto und
  Passwort kommt er nicht.
- **Welche Daten fließen:** Fragst du den Dienst nach deinen Aufgaben, gehen
  die abgefragten Inhalte (Titel, Notizen, Status, Priorität, Frist, Projekt)
  an ihn. Neue Aufgaben werden mit der Herkunft „Claude" bzw. „ChatGPT"
  gespeichert.
- **Verantwortung:** Was Anthropic bzw. OpenAI mit diesen Inhalten tun, richtet
  sich nach deinem Vertrag mit dem jeweiligen Dienst und dessen
  Datenschutzerklärung; der Anbieter von Mindcrate hat darauf keinen Einfluss.
  Beide Unternehmen sitzen in den USA.
- **Widerruf:** jederzeit in der App unter *Mehr → Verknüpfungen → Trennen*.
  Danach ist der Schlüssel ungültig. Verbundene Dienste und den Zeitpunkt der
  Zustimmung speichert Supabase, bis du sie trennst.

## Google Kalender anzeigen (nur lesend)

Der Kalender-Tab kann Termine aus einem Google Kalender anzeigen. Diese
Funktion ist derzeit nur für das Konto des Anbieters freigeschaltet; für alle
anderen Konten ist sie ohne Wirkung.

- **Quelle:** die private iCal-Adresse des Kalenders. Sie liegt ausschließlich
  als Geheimnis auf dem Server (Supabase, Frankfurt), nie in der App.
- **Ablauf:** Eine Server-Funktion ruft die Adresse bei Google ab, wertet die
  Termine aus und gibt nur **Titel, Tag und Uhrzeiten** an die App weiter. Ort,
  Beschreibung und Teilnehmer bleiben auf dem Server und werden verworfen.
- **Speicherung:** Termine werden nicht in der Datenbank gespeichert. Der
  Server hält die Abfrage höchstens fünf Minuten im Arbeitsspeicher. Auf dem
  Gerät liegt eine Kopie der zuletzt geladenen Termine (etwa zwei Monate
  zurück, vier voraus), damit der Kalender auch ohne Netz etwas zeigt.
- **Google:** Beim Abruf der Adresse erhält Google die Anfrage vom Server von
  Supabase, nicht von deinem Gerät. Für den Kalender selbst gilt die
  Datenschutzerklärung von Google.
- **Rechtsgrundlage:** Bereitstellung der angeforderten Funktion
  (Art. 6 Abs. 1 lit. b DSGVO).

Andere Empfänger gibt es nicht. Der Anbieter verkauft keine Daten und gibt sie
nicht weiter.

## Was nicht stattfindet

- **Keine Werbung, kein Tracking, keine Analyse.** Es ist keine
  entsprechende Bibliothek enthalten.
- **Keine Cookies zu Werbe- oder Analysezwecken.** Die Web-App nutzt nur den
  lokalen Speicher des Browsers für die oben genannten Zwecke, die für den
  Betrieb nötig sind.
- **Keine Push-Nachrichten vom Server, kein Standort, keine Kontakte, kein
  Zugriff auf den Kalender des Geräts, keine Kamera.**
- **Keine Weitergabe an KI-Dienste ohne dich.** Nur ein Dienst, den du selbst
  verbindest, bekommt Zugriff (siehe oben).

### Fokus-Timer

- **Mitteilungen:** Beim ersten Start des Timers fragt die App, ob sie dir
  Mitteilungen senden darf. Sie plant damit **auf dem Gerät** eine Mitteilung
  für das Ende der Fokus- oder Pausenzeit. Es geht dafür nichts an einen
  Server. Lehnst du ab, läuft der Timer trotzdem.
- **iOS-Fokus („Nicht stören"):** Schaltest du es ein, öffnet die App beim
  Start einer Fokus-Phase die Kurzbefehle-App von iOS und übergibt ihr den
  Namen des Kurzbefehls und die Minuten bis zum Phasenende. Was der
  Kurzbefehl tut, legst du selbst fest; die App liest von dort nichts zurück.
- **Live Activity:** Läuft der Timer, zeigt das iPhone Restzeit, Phase und den
  Titel der gewählten Aufgabe auf dem Sperrbildschirm und in der Dynamic
  Island. Dafür legt die App diese Angaben in einem geschützten Speicherbereich
  ab, den nur die App und ihre Erweiterung lesen. Die Anzeige läuft vollständig
  auf dem Gerät. Ob Live-Aktivitäten erscheinen, steuerst du in den
  iOS-Einstellungen der App. Beachte: Auf dem Sperrbildschirm ist der
  Aufgabentitel auch ohne Entsperren sichtbar.

### Links in Notizen

Schreibst du eine Internetadresse in eine Notiz, wird sie als Link
dargestellt. Tippst du darauf, öffnet sich die Seite im Browser; dann gilt
die Datenschutzerklärung ihres Betreibers.

## Speicherdauer und Löschung

Deine Inhalte bleiben gespeichert, bis du sie löschst. Erledigte Aufgaben
wandern nach sieben Tagen ins Archiv, werden dabei aber nicht gelöscht.

- **Einzelne Aufgaben, Unteraufgaben, Projekte:** direkt in der App löschen.
  Die Löschung wird beim nächsten Abgleich auf dem Server ausgeführt.
- **Konto vollständig löschen:** in der App unter *Mehr → Konto löschen* oder
  per E-Mail an die oben genannte Adresse. Mit dem Konto werden alle Aufgaben,
  Unteraufgaben und Projekte sowie die Freigaben für Claude oder ChatGPT
  gelöscht; die App entfernt außerdem die Kopie dieser Daten vom Gerät.

Sicherungskopien beim Dienstleister können gelöschte Daten noch für kurze
Zeit enthalten, bis sie im normalen Ablauf überschrieben werden.

## Deine Rechte

Dir stehen nach DSGVO die Rechte auf Auskunft (Art. 15), Berichtigung
(Art. 16), Löschung (Art. 17), Einschränkung (Art. 18), Datenübertragbarkeit
(Art. 20) und Widerspruch (Art. 21) zu. Schreib dafür an die oben genannte
Adresse.

Du kannst dich außerdem bei einer Aufsichtsbehörde beschweren (Art. 77).
Zuständig ist die **Landesbeauftragte für Datenschutz und
Informationsfreiheit Nordrhein-Westfalen**:

```
Landesbeauftragte für Datenschutz und Informationsfreiheit
Nordrhein-Westfalen
Postfach 20 04 44
40102 Düsseldorf

Hausadresse: Kavalleriestr. 2–4, 40213 Düsseldorf
Telefon: 0211 38424-0
E-Mail: poststelle@ldi.nrw.de
```

## Kinder

Diese App richtet sich nicht an Kinder.

## Änderungen dieser Erklärung

Ändert sich an der Datenverarbeitung etwas – etwa wenn die Kalender-Anzeige
für weitere Konten geöffnet wird oder die App Termine in den Kalender
schreibt –, wird diese Erklärung vor der betreffenden Version angepasst.

---

[Support](support.html) · [Impressum](../impressum.html) · [Datenschutzerklärung der anderen Apps](../index.html)
