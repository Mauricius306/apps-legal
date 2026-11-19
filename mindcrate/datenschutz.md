---
layout: default
title: Datenschutzerklärung Mindcrate
---

# Datenschutzerklärung Mindcrate

**Stand:** 19. November 2026, siebte Fassung (Name und Kürzel, Mitteilungen bei Zuweisung, Projekt-Bereiche ergänzt)

[English version](privacy.html) (Übersetzung; maßgeblich ist diese deutsche Fassung)

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
**Cloudflare** ausgeliefert, E-Mails zum Konto verschickt **Brevo**. Verbindest du Mindcrate selbst mit **Claude** oder
**ChatGPT**, liest und ändert der gewählte Dienst deine Aufgaben – nur nach deiner
Zustimmung und bis du sie widerrufst. Schließt du **Mindcrate Plus** ab, kaufst du
über Apple oder im Browser über Paddle; die Käufe prüft **RevenueCat**. Es gibt keine Werbung, kein Tracking und
keine Auswertung deines Verhaltens.

## Welche Daten verarbeitet werden

### Konto

- E-Mail-Adresse
- Passwort – gespeichert wird nur ein Hash, nicht das Passwort selbst
- Zeitpunkte der Registrierung und der letzten Anmeldung

### Inhalte, die du eingibst

- Aufgaben mit Titel, Notizen, Status, Priorität, Frist, Wiederholung,
  Erinnerungseinstellungen (Plus), Reihenfolge und dem Weg, auf dem sie angelegt wurden (App, Web, Import,
  Claude, ChatGPT, Mail)
- Unteraufgaben
- in geteilten Projekten: Mitglieder, Zuständige (auch mehrere), wer erledigt hat
- freiwillig: dein Name und Kürzel (Mehr → Name und Kürzel)
- je Projekt freiwillig ein Bereich (z. B. Arbeit, Privat)
- Anhänge (Plus): Fotos und PDF-Dateien, die du selbst an eine Aufgabe hängst, mit
  Dateiname, Typ und Größe
- Projekte mit Name, Farbe, Priorität, Beschreibung und Reihenfolge
- Zeitpunkte des Anlegens, Änderns und Erledigens

Was du in Titel, Notizen und Projektbeschreibungen schreibst, bestimmst du selbst. Bitte trag dort
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
- Einstellungen: Sprache, Farbschema, Hell/Dunkel, Bedienhand, Ansicht und Sortierung
  der Liste, Erinnerungen, Morgen-Übersicht und Zahl am App-Symbol
- ein Zähler erledigter Aufgaben und ob schon nach einer Bewertung gefragt wurde
  (iPhone, siehe unten)
- im Browser: die Dateien der Web-App selbst (Service Worker), damit sie auch
  ohne Netz startet – keine Aufgaben, die liegen wie oben im lokalen Speicher
- die Fokus-Zeit je Aufgabe (Summe der abgeschlossenen Fokus-Minuten), nur
  zur Anzeige in der Aufgabe
- der Fokus-Timer: Einstellungen, aktuelle Phase, Restzeit, Zahl der Runden und
  die gewählte Aufgabe. Er wird **nicht** an den Server übertragen; es gibt
  keine Auswertung oder Statistik darüber.

Beim Abmelden entfernt die App die lokale Kopie vom Gerät. Ausnahme: Warten
noch Änderungen auf die Übertragung, bleiben sie (nach einem Hinweis) auf dem
Gerät, damit nichts verloren geht, und werden nach der nächsten Anmeldung
übertragen.

## Zweck und Rechtsgrundlage

- **Konto und Inhalte:** um dir die App bereitzustellen und deine Aufgaben
  zwischen deinen Geräten abzugleichen (Art. 6 Abs. 1 lit. b DSGVO).
- **Protokolle mit IP-Adresse:** für den sicheren Betrieb und um Missbrauch
  zu erkennen; berechtigtes Interesse nach Art. 6 Abs. 1 lit. f DSGVO.
- **Verbindung mit Claude oder ChatGPT:** nur, wenn du sie selbst einrichtest
  und zustimmst, um die Funktion bereitzustellen, die du angefordert hast
  (Art. 6 Abs. 1 lit. b DSGVO).
- **Mail an Mindcrate:** nur, wenn du dir eine Adresse erzeugst; für dich
  Art. 6 Abs. 1 lit. b DSGVO, für Daten Dritter in weitergeleiteten Mails siehe
  den Abschnitt „Mail an Mindcrate“.

## Empfänger: Supabase

Datenbank, Anmeldung und Abgleich in Echtzeit laufen über **Supabase Pte.
Ltd.**, 65 Chulia Street #38-02/03, OCBC Centre, Singapur 049513, als
Auftragsverarbeiter nach Art. 28 DSGVO. Die Daten werden in der Region
Frankfurt am Main (EU) gespeichert. Für Zugriffe aus Ländern außerhalb der EU,
etwa im Rahmen von Wartung und Support durch Supabase, gelten die
Standardvertragsklauseln der EU-Kommission (Art. 46 Abs. 2 lit. c DSGVO), die
Teil des Auftragsverarbeitungsvertrags von Supabase sind:
<https://supabase.com/legal/dpa>

E-Mails zur Bestätigung der Adresse, zum Ändern der Adresse oder zum
Zurücksetzen des Passworts löst Supabase aus; verschickt werden sie über Brevo
(nächster Abschnitt). Der Link darin öffnet die Web-App.

## Empfänger: Brevo (E-Mails zum Konto)

Die E-Mails zu deinem Konto (Adresse bestätigen, Adresse ändern, Passwort
zurücksetzen; auf Wunsch Mitteilungen bei Zuweisung) verschickt **Brevo SAS**, 17 rue de Salneuve, 75017 Paris,
Frankreich (deutsche Niederlassung: Brevo GmbH, Köpenicker Str. 126, 10179
Berlin), als Auftragsverarbeiter nach Art. 28 DSGVO. Dafür erhält Brevo deine
E-Mail-Adresse und den Inhalt der jeweiligen Mail mit dem Link; Brevo
protokolliert Zustellung, Zeitpunkt und technische Rückmeldungen (z. B.
unzustellbar). Brevo erfasst bei diesen Mails außerdem technisch, ob sie
geöffnet und ob Links darin angeklickt werden (Zählpixel, Weiterleitung der
Links über Brevo); im genutzten Tarif lässt sich das nicht abschalten.
Mindcrate wertet diese Angaben nicht aus. Es gibt keine Newsletter und keine
Werbung. Die Verarbeitung findet in der EU statt. Rechtsgrundlage ist die Erfüllung des Nutzungsvertrags (Art. 6 Abs. 1
lit. b DSGVO). Datenschutz bei Brevo: <https://www.brevo.com/legal/privacypolicy/>,
Auftragsverarbeitung (Teil der Nutzungsbedingungen): <https://www.brevo.com/legal/termsofuse/>

## Empfänger: Cloudflare (Web-App)

Die Dateien der Web-App liefert **Cloudflare, Inc.**, 101 Townsend Street,
San Francisco, CA 94107, USA, über den Dienst Cloudflare Workers aus. Beim Aufruf
fallen dort technisch IP-Adresse, Zeitpunkt, aufgerufene Adresse und
Browserkennung an; Cloudflare verarbeitet sie für Auslieferung und Schutz vor
Angriffen. Deine Aufgaben laufen **nicht** über Cloudflare, sondern direkt
zwischen Browser und Supabase. Cloudflare ist unter dem EU-US Data Privacy
Framework zertifiziert (Art. 45 DSGVO); zusätzlich gelten die
Standardvertragsklauseln im Auftragsverarbeitungsvertrag:
<https://www.cloudflare.com/dpa/>. Rechtsgrundlage ist das berechtigte Interesse
an einer sicheren und schnellen Bereitstellung (Art. 6 Abs. 1 lit. f DSGVO).

### Sicherheitsprüfung bei Anmeldung und Registrierung

Um automatisierte Registrierungen und Anmeldeversuche abzuwehren, kann beim
Anmelden, Registrieren und Zurücksetzen des Passworts **Cloudflare Turnstile**
(Cloudflare, Inc., Anschrift oben) eingebunden sein. Turnstile prüft im Browser
bzw. in einem eingebetteten Browserfenster der App technische Merkmale des
Geräts und Browsers (z. B. IP-Adresse, Browserkennung, Bildschirmgröße) und
gibt der App ein Prüfzeichen, das Supabase bestätigt. Turnstile setzt nach
Angabe von Cloudflare keine Cookies zu Werbezwecken und verwendet die Daten
nicht für Werbung. Rechtsgrundlage ist das berechtigte Interesse am Schutz der
Konten und des Dienstes vor Missbrauch (Art. 6 Abs. 1 lit. f DSGVO). Datenschutz
bei Cloudflare: <https://www.cloudflare.com/turnstile-privacy-policy/>

## Sicherung der Server-Daten

Damit Inhalte bei einem technischen Fehler nicht verloren gehen, wird die
Datenbank einmal pro Woche gesichert: deine Inhalte (Aufgaben, Unteraufgaben,
Projekte und Einstellungen auf dem Server) sowie dein Konto (E-Mail-Adresse,
Passwort-Hash, Zeitstempel). Sitzungen und Anmelde-Tokens werden nicht gesichert,
Dateien von Anhängen ebenfalls nicht (nur ihr Name, Typ und ihre Größe).
Die Sicherung wird vor dem Speichern **verschlüsselt**; öffnen kann sie nur der
Anbieter mit einem Schlüssel, der nicht beim Speicherdienst liegt.

Gespeichert wird die verschlüsselte Datei bei **GitHub, Inc.**, 88 Colin P. Kelly
Jr. Street, San Francisco, CA 94107, USA, im privaten Bereich des Anbieters
(GitHub Actions). GitHub sieht nur die verschlüsselte Datei. GitHub ist unter dem
EU-US Data Privacy Framework zertifiziert (Art. 45 DSGVO). Jede Sicherung wird
nach **60 Tagen** automatisch gelöscht. Rechtsgrundlage ist das berechtigte
Interesse, deine Inhalte vor Verlust zu schützen (Art. 6 Abs. 1 lit. f DSGVO),
und die Erfüllung des Nutzungsvertrags (Art. 6 Abs. 1 lit. b DSGVO).

## Mindcrate Plus (Abo, freiwillig)

Mindcrate Plus ist ein Abo, das du in der iPhone-App oder im Browser abschließen kannst. Es
schaltet „Tag planen“, die Verbindung mit Claude und ChatGPT und Mail an
Mindcrate frei. Ohne Plus bleibt die übrige App vollständig nutzbar.

- **Kauf in der iPhone-App** läuft über **Apple** (App Store). Zahlungsdaten erhält
  der Anbieter nicht; es gilt die Datenschutzerklärung von Apple.
- **Prüfung der Käufe:** **RevenueCat, Inc.**, 1032 E Brandon Blvd #3003, Brandon,
  FL 33511, USA, prüft im Auftrag des Anbieters die Kaufbelege von Apple und teilt
  mit, ob Plus aktiv ist (Auftragsverarbeiter nach Art. 28 DSGVO). Dafür erhält
  RevenueCat deine Konto-ID bei Mindcrate (eine zufällige Kennung, nicht deine
  E-Mail-Adresse), den Kaufverlauf zu Mindcrate Plus (Produkt, Zeitpunkte,
  Ablauf, Probezeit, Land) sowie technisch IP-Adresse, Gerätetyp und
  App-Version. Für die Übermittlung in die USA gelten die
  Standardvertragsklauseln der EU-Kommission (Art. 46 Abs. 2 lit. c DSGVO) im
  Auftragsverarbeitungsvertrag: <https://www.revenuecat.com/dpa>.
  RevenueCat wird erst eingerichtet, wenn du angemeldet bist.
- **Kauf im Browser:** Kaufst du Plus im Browser, verkauft es **Paddle.com
  Market Limited**, 30 Old Bailey, London EC4M 7AU,
  Vereinigtes Königreich, als eigenverantwortlicher Händler (Merchant of Record).
  Paddle verarbeitet dafür deine Zahlungs- und Rechnungsdaten (Name, E-Mail,
  Land, Postleitzahl, Zahlungsmittel) nach seiner eigenen Datenschutzerklärung:
  <https://www.paddle.com/legal/privacy>. An Paddle übergeben wird zusätzlich
  deine Konto-ID bei Mindcrate, damit der Kauf deinem Konto zugeordnet wird.
  Für das Vereinigte Königreich gilt ein Angemessenheitsbeschluss der
  EU-Kommission (Art. 45 DSGVO). RevenueCat erhält von Paddle den Kaufverlauf
  wie oben beschrieben.
- **Berechtigung:** Ob und bis wann Plus aktiv ist, speichert Supabase (Frankfurt)
  zu deinem Konto, damit Plus auf allen deinen Geräten gilt.
- **Rechtsgrundlage:** Erfüllung des Abo-Vertrags (Art. 6 Abs. 1 lit. b DSGVO);
  Aufbewahrung von Kaufdaten, soweit Handels- und Steuerrecht es verlangen
  (Art. 6 Abs. 1 lit. c DSGVO).
- **Kündigen:** bei Apple (Einstellungen → dein Name → Abonnements) bzw. über den
  Link in der Kaufbestätigung von Paddle.
  Beim Löschen deines Kontos wird die Berechtigung bei Supabase gelöscht; ein
  laufendes Abo bei Apple kündigt das nicht.

## Geteilte Projekte (freiwillig)

Du kannst ein Projekt mit anderen Menschen teilen. Dazu erzeugst du einen
Einladungscode (14 Tage gültig) und gibst ihn oder den Link selbst weiter;
Mindcrate verschickt nichts. Wer mit dem Code beitritt, wird Mitglied.

- **Wer was sieht:** Alle Personen eines geteilten Projekts sehen und bearbeiten
  dessen Aufgaben, Unteraufgaben und Anhänge, sehen, wem eine Aufgabe zugewiesen
  ist und wer sie erledigt hat, und sehen die **E-Mail-Adressen** der anderen
  Personen im Projekt sowie deren Name und Kürzel, falls hinterlegt. Andere
  Projekte und Aufgaben bleiben privat. Neue Aufgaben in einem geteilten Projekt
  sind zunächst der Person zugewiesen, die sie anlegt.
- **Mitteilung bei Zuweisung:** Weist dir jemand eine Aufgabe zu, bekommst du
  eine Mitteilung aufs iPhone und, wenn du es einschaltest, eine E-Mail.
  Einstellbar unter Mehr → Mitteilungen (iPhone standardmäßig an, E-Mail aus).
  Details unter „Push-Mitteilungen bei Zuweisung“.
- **Verlassen und entfernen:** Mitglieder können jederzeit austreten, der
  Besitzer kann Mitglieder entfernen und Einladungen beenden. Aufgaben, die ein
  Mitglied im Projekt angelegt hat, bleiben dann im Projekt und gehören dem
  Besitzer.
- **Schutz vor Raten:** Fehlgeschlagene Beitrittsversuche werden mit deiner
  Konto-ID und der Uhrzeit für einen Tag gespeichert und begrenzt.
- **Rechtsgrundlage:** Erfüllung des Nutzungsvertrags (Art. 6 Abs. 1 lit. b
  DSGVO) – du entscheidest, mit wem du teilst. Für die Inhalte, die du in ein
  geteiltes Projekt schreibst, und für die Weitergabe der Einladung bist du
  gegenüber den anderen selbst verantwortlich.

## Push-Mitteilungen bei Zuweisung (iPhone, nur in geteilten Projekten)

Sobald du in einem geteilten Projekt bist, fragt die iPhone-App, ob sie dir
Mitteilungen senden darf. Erlaubst du es, speichert Mindcrate ein
**Gerätekennzeichen** (Expo-Push-Token, höchstens 5 Geräte je Konto) und die
Sprache des Geräts bei Supabase. Weist dir jemand eine Aufgabe zu, schickt der
Server über den **Expo-Push-Dienst** von **650 Industries, Inc.** (Expo),
Palo Alto, USA, an den Push-Dienst von Apple: Titel der Aufgabe, Projektname
und Name (oder der Teil vor dem @ der Mail-Adresse) der Person, die zuweist.
Expo verarbeitet diese Angaben nur zur Zustellung als Auftragsverarbeiter; die
Übermittlung in die USA stützt sich auf das EU-US Data Privacy Framework bzw.
Standardvertragsklauseln. Datenschutz bei Expo: <https://expo.dev/privacy>

- **Per E-Mail (freiwillig, standardmäßig aus):** Schaltest du „Zuweisungen per
  E-Mail“ ein, geht dieselbe Mitteilung als Mail über Brevo (siehe oben) an
  deine Konto-Adresse.
- **Warteschlange:** Auf dem Server wird je Mitteilung nur vermerkt, wer, welche
  Aufgabe, von wem und wann – nach 7 Tagen gelöscht.
- **Abschalten:** Mehr → Mitteilungen, oder in den iPhone-Einstellungen.
  Abmelden löscht das Gerätekennzeichen; Konto löschen löscht alles.
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Funktion geteilter Projekte),
  für das Gerätekennzeichen deine Einwilligung über die iOS-Abfrage (§ 25 Abs. 1
  TDDDG).

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

## Kalender anzeigen (nur lesend)

Der Kalender-Tab kann Termine aus bis zu fünf eigenen Kalendern anzeigen
(Google Kalender, iCloud, Outlook). Du verbindest sie selbst unter
Mehr → Kalender; ohne verbundenen Kalender passiert nichts.

- **Quelle:** die private iCal-Adresse je Kalender, die du einfügst, und ein
  Name, den du vergibst. Beides wird in Supabase (Frankfurt) zu deinem Konto
  gespeichert. Die App kann die Adresse danach **nicht mehr auslesen** –
  gelesen wird sie nur von der Server-Funktion, die die Termine abruft.
  Angenommen werden nur Adressen der genannten Anbieter.
- **Ablauf:** Die Server-Funktion ruft die Adresse beim Anbieter ab, wertet die
  Termine aus und gibt nur **Titel, Tag und Uhrzeiten** an die App weiter. Ort,
  Beschreibung und Teilnehmer bleiben auf dem Server und werden verworfen.
- **Speicherung:** Termine werden nicht in der Datenbank gespeichert. Der
  Server hält die Abfrage höchstens fünf Minuten im Arbeitsspeicher. Auf dem
  Gerät liegt eine Kopie der zuletzt geladenen Termine (etwa zwei Monate
  zurück, vier voraus), damit der Kalender auch ohne Netz etwas zeigt.
- **Löschen:** Entfernst du einen Kalender, wird seine Adresse sofort
  gelöscht. Beim Löschen des Kontos werden alle Kalender-Einträge mitgelöscht.
- **Anbieter des Kalenders:** Beim Abruf erhält Google, Apple bzw. Microsoft
  die Anfrage vom Server von Supabase, nicht von deinem Gerät. Für den Kalender
  selbst gilt die Datenschutzerklärung des jeweiligen Anbieters.
- **Rechtsgrundlage:** Bereitstellung der angeforderten Funktion
  (Art. 6 Abs. 1 lit. b DSGVO).

Andere Empfänger gibt es nicht. Der Anbieter verkauft keine Daten und gibt sie
nicht weiter.

## Mail an Mindcrate (freiwillig)

Unter *Mehr → Mail an Mindcrate* kannst du dir eine persönliche, geheime
E-Mail-Adresse erzeugen. Eine Mail an diese Adresse wird zur Aufgabe in deinem
Eingang. Ohne erzeugte Adresse findet nichts davon statt.

- **Was gespeichert wird:** der Betreff (als Titel), Name und Adresse des
  Absenders und der Text der Mail (als Notiz, höchstens 10 000 Zeichen).
  Anhänge werden verworfen, Bilder und Formatierung nicht übernommen.
- **Weg der Mail:** Die Mail geht an **Cloudflare Email Routing** (Cloudflare,
  Inc., Anschrift oben). Ein Programm bei Cloudflare (Email Worker) zerlegt sie
  und reicht die genannten Angaben an Supabase weiter, wo die Aufgabe angelegt
  wird. Cloudflare speichert nach eigener Angabe keine Mailinhalte; dabei fallen
  technisch Absender- und Empfängeradresse, Zeitpunkt und die beteiligten
  Mailserver an. Übermittlung in die USA wie im Abschnitt zu Cloudflare
  beschrieben.
- **Daten Dritter:** Leitest du eine Mail weiter, enthält sie oft Name, Adresse
  und Text einer anderen Person. Diese verarbeiten wir in deinem Auftrag, damit
  du die Mail als Aufgabe erledigen kannst; Rechtsgrundlage ist das berechtigte
  Interesse an der Organisation deiner Aufgaben (Art. 6 Abs. 1 lit. f DSGVO).
  Bitte leite nur Mails weiter, die du dafür verwenden darfst.
- **Wer die Adresse kennt,** kann dir Aufgaben schicken. Du kannst jederzeit
  eine neue Adresse erzeugen (die alte gilt dann nicht mehr) oder die Funktion
  abschalten; die Adresse wird dabei gelöscht. Angelegte Aufgaben bleiben, bis
  du sie löschst.
- Missbrauchsschutz: höchstens 30 Mails je Adresse und Stunde, Mails über 1 MB
  und an unbekannte Adressen werden abgewiesen.

## Was nicht stattfindet

- **Keine Werbung, kein Tracking, keine Analyse.** Es ist keine
  entsprechende Bibliothek enthalten.
- **Keine Cookies zu Werbe- oder Analysezwecken.** Die Web-App nutzt nur den
  lokalen Speicher des Browsers für die oben genannten Zwecke, die für den
  Betrieb nötig sind.
- **Keine Push-Nachrichten vom Server** außer bei Zuweisung in geteilten
  Projekten (siehe oben), **kein Standort, keine Kontakte, kein
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

### Erinnerungen und Zahl am App-Symbol (iPhone)

Schaltest du unter *Mehr → Benachrichtigungen* Erinnerungen ein, plant die App
für Aufgaben mit Frist und Uhrzeit **auf dem Gerät** Mitteilungen (Titel der
Aufgabe und Uhrzeit). Die Zahl am App-Symbol zeigt, wie viele Aufgaben heute
fällig oder überfällig sind. Beides berechnet das Gerät selbst; es gibt keinen
Push-Server. Standardmäßig ist beides aus. Beachte: Mitteilungen können je
nach iOS-Einstellung auf dem Sperrbildschirm sichtbar sein.

### Widget „Mindcrate Heute“ (iPhone)

Legst du das Widget auf den Homescreen oder Sperrbildschirm, schreibt die App
die heute fälligen und überfälligen Aufgaben (Titel, Uhrzeit, Projektfarbe) in
einen gemeinsamen Speicher von App und Widget **auf dem Gerät**
(App-Gruppe). Nichts davon geht an einen Server. Auf dem Sperrbildschirm sind
die Titel auch ohne Entsperren sichtbar. Hakst du im Widget etwas ab, merkt es
sich das auf dem Gerät, bis die App es übernimmt. Nach dem Abmelden zeigt das
Widget keine Titel mehr.

### Teilen-Menü (iPhone)

Über *Teilen → In Mindcrate* kannst du Text oder einen Link aus einer anderen App
als Aufgabe übernehmen. Die Erweiterung reicht den geteilten Inhalt über den
gemeinsamen Speicher auf dem Gerät an die App weiter; dort wird er wie eine
selbst eingetippte Aufgabe gespeichert und abgeglichen. Bei Links übernimmt
iOS dabei den Seitentitel der geteilten Seite.

### Morgen-Übersicht (iPhone)

Auf Wunsch zeigt eine Mitteilung morgens, wie viele Aufgaben an dem Tag
anstehen. Auch sie plant das Gerät selbst; es geht nichts an einen Server.
Standardmäßig ist sie aus.

### Bewertung im App Store (iPhone)

Nach 50 erledigten Aufgaben, frühestens eine Woche nach dem ersten Start, fragt
die App **einmal** über das Fenster von Apple nach einer Bewertung. Ob und wie
du bewertest, erfährt die App nicht; die Bewertung verarbeitet Apple.

### Anhänge (Plus)

An eine Aufgabe kannst du Fotos und PDF-Dateien hängen (höchstens 10 MB je Datei,
100 MB insgesamt). Auf dem iPhone wählst du ein Foto über die Fotoauswahl von
Apple oder eine Datei aus „Dateien“; die App sieht nur, was du auswählst, und
nutzt die Kamera nicht. Die Datei liegt in einem nicht öffentlichen Speicher bei
Supabase (Frankfurt). Sehen und öffnen kann sie nur, wer die Aufgabe sehen darf;
zum Öffnen erzeugt die App einen Link, der nach 10 Minuten verfällt.
Rechtsgrundlage ist die Erfüllung des Nutzungsvertrags (Art. 6 Abs. 1 lit. b DSGVO).
Entfernst du einen Anhang, wird die Datei sofort gelöscht. Wird die Aufgabe
endgültig gelöscht, löscht ein wöchentlicher Aufräumlauf ihre Dateien.

### Daten exportieren

Unter *Mehr → Daten exportieren* erzeugt die App auf dem Gerät eine Datei
(JSON oder CSV) mit deinen Projekten, Aufgaben und Unteraufgaben; Anhänge sind
nicht enthalten, du kannst sie einzeln öffnen und speichern. Im Browser
wird sie heruntergeladen, auf dem iPhone über das Teilen-Menü ausgegeben. Wohin
sie geht, entscheidest du; die App sendet sie nirgendwohin.

### Sicherung zurückspielen

Unter *Mehr → Sicherung zurückspielen* liest die App eine zuvor exportierte
JSON-Datei, die du auswählst, und legt daraus nur an, was in deinem Konto fehlt.
Die Datei selbst wird nicht hochgeladen, nur die daraus angelegten Einträge wie
bei jeder anderen Eingabe.

### Problem melden

*Mehr → Problem melden* öffnet dein Mailprogramm mit einer vorbereiteten
E-Mail an die oben genannte Adresse. Sie enthält App-Version, Gerätetyp,
Systemversion, den Stand des Abgleichs und die letzte Fehlermeldung, aber
keine Aufgaben. Gesendet wird nur, was du selbst abschickst.

### Schutz vor Missbrauch

Die Server-Funktionen (Verbindung mit Claude/ChatGPT, Kalender, Konto löschen)
zählen für etwa eine Minute im Arbeitsspeicher, wie viele Anfragen ein Konto
stellt, und bremsen bei zu vielen. Gespeichert wird dabei nichts. Außerdem gelten
je Konto Obergrenzen (5 000 Aufgaben, 200 Projekte, 100 Schritte je Aufgabe,
Notizen bis 20 000 Zeichen), damit ein einzelnes Konto den Dienst nicht für alle
anderen auslastet.

### Links in Notizen

Schreibst du eine Internetadresse in eine Notiz, wird sie als Link
dargestellt. Tippst du darauf, öffnet sich die Seite im Browser; dann gilt
die Datenschutzerklärung ihres Betreibers.

## Speicherdauer und Löschung

Deine Inhalte bleiben gespeichert, bis du sie löschst. Erledigte Aufgaben
wandern nach sieben Tagen ins Archiv, werden dabei aber nicht gelöscht.

- **Aufgaben** kommen beim Löschen zuerst in den **Papierkorb** und lassen sich
  dort 30 Tage wiederherstellen. Danach – oder sofort über „Endgültig löschen“
  bzw. „Papierkorb leeren“ – werden sie endgültig gelöscht, samt Unteraufgaben
  und Anhängen (die Dateien spätestens nach einer Woche).
- **Unteraufgaben und Projekte:** direkt in der App löschen. Die Löschung wird
  beim nächsten Abgleich auf dem Server ausgeführt.
- Erledigte Aufgaben, die älter als 90 Tage sind, lädt die App erst auf Wunsch
  („Älteres Archiv laden“); auf dem Server bleiben sie bis zur Löschung.
- **Konto vollständig löschen:** in der App unter *Mehr → Konto löschen* oder
  per E-Mail an die oben genannte Adresse. Mit dem Konto werden alle Aufgaben,
  Unteraufgaben, Anhänge (samt Dateien) und Projekte, die Adresse für Mail an Mindcrate, die
  Plus-Berechtigung sowie die Freigaben für Claude oder ChatGPT gelöscht; die App entfernt außerdem die Kopie dieser Daten vom Gerät.
  Aufgaben in Projekten, die andere mit dir geteilt haben, gehen vorher an deren
  Besitzer über; Mitglieder deiner geteilten Projekte behalten ihre eigenen
  Aufgaben daraus.

Gelöschte Daten können noch in den verschlüsselten wöchentlichen Sicherungen
enthalten sein (siehe „Sicherung der Server-Daten“) und verschwinden dort
spätestens nach 60 Tagen.

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

Ändert sich an der Datenverarbeitung etwas – etwa wenn die App Termine in den
Kalender schreibt oder Kalender über eine Google-Anmeldung verbindet –, wird
diese Erklärung vor der betreffenden Version angepasst.

---

[Support](support.html) · [Impressum](../impressum.html) · [Datenschutzerklärung der anderen Apps](../index.html)
