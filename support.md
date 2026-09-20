# Hilfe zu StartWork

StartWork bucht Arbeitszeit in Jira. Die App läuft auf deinem Gerät und
spricht ausschließlich mit **deiner eigenen** Jira-Instanz.

**Kontakt:** [info@iamnotadev.xyz](mailto:info@iamnotadev.xyz)
Antwort in der Regel innerhalb weniger Tage. Schreib gern auf Deutsch oder
Englisch.

Damit dir schneller geholfen ist, nenne bitte: die Fassung der App, ob du
Jira Cloud oder Jira Server/Data Center benutzt, und den Wortlaut der
Fehlermeldung.

---

## Häufige Fragen

### Welche Jira-Versionen werden unterstützt?

Jira Cloud (`…atlassian.net`) sowie Jira Server und Data Center. Bei Cloud
meldest du dich mit E-Mail und API-Token an, bei Server und Data Center mit
einem persönlichen Zugriffstoken.

### Woher bekomme ich ein Token?

**Jira Cloud:** unter <https://id.atlassian.com/manage-profile/security/api-tokens>.

**Jira Server / Data Center:** in deinem Jira unter *Profil → Persönliche
Zugriffstokens*. Fehlt der Punkt, hat ihn deine Jira-Verwaltung
abgeschaltet — dann hilft nur eine Anfrage dort.

### Die App sagt, es gebe mein Ticket nicht.

Entweder stimmt der Schlüssel nicht, oder dein Konto darf den Vorgang nicht
sehen. Beides prüfst du, indem du das Ticket in Jira selbst aufrufst.

### Auf ein Ticket lässt sich nichts buchen.

Steht das Ticket in einem Status wie „geschlossen" oder „erledigt", sperrt
Jira das Protokollieren von Zeit. Das lässt sich auch in Jira selbst nicht
umgehen — nimm einen offenen Vorgang.

### Wir benutzen Tempo. Funktioniert das?

Ja. StartWork schreibt ein normales Jira-Worklog, und Tempo liest diese
Worklogs mit. **Aber:** Verlangt deine Firma Tempo-Pflichtfelder
(*Work Attributes*), bleiben die leer. Ob das genügt, entscheidet eure
Einrichtung.

### Was passiert mit meinen Daten?

Sie bleiben auf dem Gerät. Es gibt keinen Server des Anbieters, kein Konto
und keine Analyse. Einzelheiten stehen in der
[Datenschutzerklärung](./).

### Wie lösche ich alles?

*Zahnrad → Alle Daten auf diesem Gerät löschen.* Das entfernt Zugangsdaten,
eigene Kacheln und den gesamten Verlauf. Bereits in Jira gebuchte Zeiten
bleiben davon unberührt — die liegen auf dem Jira-Server.

### Was macht „Kundentauglich formulieren"?

Der Knopf schickt deinen Buchungskommentar an Anthropic und bekommt eine
sachliche Formulierung zurück. Er ist ab Werk **aus** und verlangt zweierlei:
einen eigenen Anthropic-Schlüssel und deine ausdrückliche Zustimmung. Ohne
beides verlässt nichts das Gerät. Widerrufen kannst du jederzeit im Zahnrad.

---

Jira ist eine Marke von Atlassian, Tempo eine Marke von Tempo ehf.
StartWork steht in keiner Verbindung zu diesen Unternehmen.
