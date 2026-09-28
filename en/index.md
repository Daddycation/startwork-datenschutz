# Privacy Policy — StartWork

As of 28 September 2026 · Information under Art. 13 GDPR

> This is a translation for convenience. The
> [German version](https://daddycation.github.io/startwork-datenschutz/)
> is the legally binding one.
>
> [Français](https://daddycation.github.io/startwork-datenschutz/fr/) · [Português](https://daddycation.github.io/startwork-datenschutz/pt/) · [Español](https://daddycation.github.io/startwork-datenschutz/es/)

## The core in three sentences

StartWork runs on your device. The provider of this app **collects, stores
and receives no data from you whatsoever** — there is no server of the
provider, no account, no analytics, no tracking, no advertising identifiers.

Data leaves your device only for destinations **you choose yourself**.

## 1. Controller

```
Philip Müller
Theaterstraße 27
09111 Chemnitz
Germany

Email: info@iamnotadev.xyz
```

Under the EU Digital Services Act, the same details appear as trader
information on the app's App Store product page. This is mandatory for a
paid app and cannot be turned off.

## 2. What is stored on the device

| Data | Where | Purpose |
|---|---|---|
| Address of your Jira instance, email (Cloud only), settings | Device storage (iOS: UserDefaults) | so you don't have to enter them every time |
| Jira access token, AI key | **Device Keychain** (iOS: Keychain) | signing in to your Jira instance |
| Your time entries (ticket, duration, comment, time) | Device storage | daily overview and previous-days view |

None of this is transmitted to the provider. **Legal basis:** Art. 6(1)(b)
GDPR — without this data the app cannot fulfil its purpose.

## 3. Where data goes

### 3.1 Your Jira instance

When you log time, StartWork sends the ticket key, duration, start time and
your comment to **the Jira server you entered yourself**. Your token is sent
to sign in; when looking up a ticket, its key is sent.

Who operates that server and what happens there is **not** determined by the
provider of this app — usually it is your employer or Atlassian. The operator
of the instance is responsible for that processing.

### 3.2 Anthropic (optional, only with your consent)

The “Polish” feature sends **your worklog comment together with the ticket
key and ticket title** to Anthropic (`api.anthropic.com`, United States),
where the text is processed and returned rephrased.

This happens **only** if you

1. have stored your own Anthropic key **and**
2. have explicitly agreed to the transfer in a separate dialog **and**
3. actually use that button.

**Legal basis:** Art. 6(1)(a) GDPR (consent). The transfer to the USA takes
place on the basis of the contractual relationship between you and
Anthropic — you use your own access.

**Withdrawal:** at any time under the gear icon, without giving reasons and
without restricting the rest of the app. A withdrawal takes effect for the
future.

Anthropic's own privacy notice: <https://www.anthropic.com/legal/privacy>

### 3.3 Nothing else

No analytics, no crash reports, no advertising networks, no fonts or scripts
from third-party servers. The app contains no components that open a
connection without your action.

## 4. Retention

Until you delete it. There is no automatic deletion.

**Delete everything:** gear icon → “Delete all data on this device”. This
removes credentials, the AI key, your own tiles and the entire history of
entries. If the app is removed, everything goes with it.

Time **already logged in Jira** is not affected — it lives on your
instance's server and has to be deleted there.

## 5. Your rights

Access, rectification, erasure, restriction, data portability and objection
(Art. 15–21 GDPR), as well as the right to lodge a complaint with a
supervisory authority (Art. 77 GDPR).

In practice: since the provider holds **no** data about you, there is
nothing to disclose and nothing to delete. All data lives on your device
and under your control. For data in your Jira instance, contact its
operator.

## 6. Children

The app is aimed at working professionals, not at children.

## 7. Changes

The date at the top is updated when this policy changes. Material changes
to data transfers require new consent.
