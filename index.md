# Datenschutzerklärung — StartWork

Stand 14.09.2026 · Information nach Art. 13 DSGVO

> **Noch zu vervollständigen:** Die ladungsfähige Anschrift fehlt. Sie ist nach
> § 5 DDG Pflicht und wird ohnehin für den DSA-Händlerstatus bei Apple gebraucht,
> sobald die App Geld kostet.

## Der Kern in drei Sätzen

StartWork läuft auf deinem Gerät. Der Anbieter dieser App **erhebt, speichert
und empfängt keinerlei Daten von dir** — es gibt keinen Server des Anbieters,
kein Konto, keine Analyse, kein Tracking, keine Werbe-Kennungen.

Daten verlassen dein Gerät nur an Ziele, die **du selbst bestimmst**.

## 1. Verantwortlicher

```
Philip Müller
[Anschrift — vor der Einreichung bei Apple einzutragen]
```

## 2. Was auf dem Gerät gespeichert wird

| Daten | Wo | Zweck |
|---|---|---|
| Adresse deiner Jira-Instanz, E-Mail (nur bei Cloud), Einstellungen | Gerätespeicher (iOS: UserDefaults) | damit du sie nicht jedes Mal eingeben musst |
| Jira-Zugriffstoken, KI-Schlüssel | **Schlüsselbund des Geräts** (iOS: Keychain) | Anmeldung an deiner Jira-Instanz |
| Deine Zeitbuchungen (Ticket, Dauer, Kommentar, Zeitpunkt) | Gerätespeicher | Tagesüberblick und Vortage-Ansicht |

Nichts davon wird an den Anbieter übertragen. **Rechtsgrundlage:** Art. 6
Abs. 1 lit. b DSGVO — ohne diese Daten kann die App ihren Zweck nicht
erfüllen.

## 3. Wohin Daten gehen

### 3.1 Deine Jira-Instanz

Beim Buchen sendet StartWork Ticketschlüssel, Dauer, Startzeit und deinen
Kommentar an **den Jira-Server, den du selbst eingetragen hast**. Zum Anmelden
wird dein Token mitgeschickt, beim Nachschlagen eines Tickets dessen Schlüssel.

Wer diesen Server betreibt und was dort geschieht, bestimmt **nicht** der
Anbieter dieser App — in aller Regel ist es dein Arbeitgeber oder Atlassian.
Für diese Verarbeitung ist der Betreiber der Instanz verantwortlich.

### 3.2 Anthropic (optional, nur mit deiner Einwilligung)

Die Funktion „Kundentauglich formulieren" sendet **deinen Buchungskommentar
sowie Ticketschlüssel und Ticketbezeichnung** an Anthropic
(`api.anthropic.com`, Vereinigte Staaten), wo der Text verarbeitet und
umformuliert zurückgegeben wird.

Das geschieht **ausschließlich**, wenn du

1. einen eigenen Anthropic-Schlüssel hinterlegt hast **und**
2. der Übermittlung in einem eigenen Dialog ausdrücklich zugestimmt hast **und**
3. diesen Knopf tatsächlich benutzt.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO (Einwilligung). Die
Übermittlung in die USA erfolgt auf Grundlage der Vertragsbeziehung zwischen
dir und Anthropic — du benutzt deinen eigenen Zugang.

**Widerruf:** jederzeit im Zahnrad, ohne Angabe von Gründen und ohne dass die
übrige App eingeschränkt wäre. Ein Widerruf wirkt für die Zukunft.

Anthropics eigene Datenschutzhinweise: <https://www.anthropic.com/legal/privacy>

### 3.3 Sonst nichts

Keine Analysedienste, keine Abstürzberichte, keine Werbenetzwerke, keine
Schriftarten oder Skripte von fremden Servern. Die App enthält keine
Bestandteile, die eine Verbindung ohne dein Zutun aufbauen.

## 4. Speicherdauer

So lange, bis du sie löschst. Es gibt keine automatische Löschung.

**Alles löschen:** Zahnrad → „Alle Daten auf diesem Gerät löschen". Das
entfernt Zugangsdaten, KI-Schlüssel, eigene Kacheln und die gesamte
Buchungshistorie. Wird die App entfernt, geht alles mit.

Bereits **in Jira gebuchte Zeiten** bleiben davon unberührt — die liegen auf
dem Server deiner Instanz und müssen dort gelöscht werden.

## 5. Deine Rechte

Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit und
Widerspruch (Art. 15–21 DSGVO) sowie Beschwerde bei einer Aufsichtsbehörde
(Art. 77 DSGVO).

In der Praxis gilt: Da der Anbieter **keine** Daten über dich hat, kann er
weder Auskunft geben noch etwas löschen. Alle Daten liegen auf deinem Gerät
und unter deiner Kontrolle. Für Daten in deiner Jira-Instanz wende dich an
deren Betreiber.

## 6. Kinder

Die App richtet sich an Berufstätige und nicht an Kinder.

## 7. Änderungen

Bei Änderungen wird das Datum oben angepasst. Wesentliche Änderungen an der
Datenübermittlung erfordern eine neue Einwilligung.
