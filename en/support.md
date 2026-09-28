# StartWork help

> [Deutsch](../support) · [Français](../fr/support) · [Português](../pt/support) · [Español](../es/support)

StartWork logs working time to Jira. The app runs on your device and talks
only to **your own** Jira instance.

**Contact:** [info@iamnotadev.xyz](mailto:info@iamnotadev.xyz)
Usually answered within a few days, in English or German.

To help you faster, please include: the app version, whether you use Jira
Cloud or Jira Server/Data Center, and the exact wording of the error message.

---

## Frequently asked questions

### Which Jira versions are supported?

Jira Cloud (`…atlassian.net`) as well as Jira Server and Data Center. With
Cloud you sign in with your email and an API token; with Server and Data
Center with a personal access token.

### Where do I get a token?

**Jira Cloud:** at <https://id.atlassian.com/manage-profile/security/api-tokens>.

**Jira Server / Data Center:** in your Jira under *Profile → Personal Access
Tokens*. If that item is missing, your Jira administrators have switched it
off — then only a request to them helps.

### The app says my ticket doesn't exist.

Either the key is wrong, or your account isn't allowed to see the issue. You
can check both by opening the ticket in Jira itself.

### I can't log time on a ticket.

If the ticket is in a status such as “closed” or “done”, Jira blocks logging
time. That can't be bypassed in Jira itself either — pick an open ticket.

### We use Tempo. Does it work?

Yes. StartWork writes a standard Jira worklog, and Tempo reads those
worklogs. **But:** if your company requires Tempo fields (*Work
Attributes*), they stay empty. Whether that is enough depends on your setup.

### What happens to my data?

It stays on the device. There is no server of the provider, no account and
no analytics. Details are in the [privacy policy](./).

### How do I delete everything?

*Gear icon → Delete all data on this device.* This removes credentials, your
own tiles and the entire history. Time already logged in Jira is not affected
— it lives on the Jira server.

### What does “Polish” do?

The button sends your worklog comment to Anthropic and gets a factual
wording back. It is **off** by default and needs two things: your own
Anthropic key and your explicit consent. Without both, nothing leaves the
device. You can withdraw consent at any time under the gear icon.

### Which languages does the app speak?

English, German, French, Portuguese and Spanish. It follows your iPhone's
language; under the gear icon you can choose explicitly.

---

Jira is a trademark of Atlassian, Tempo a trademark of Tempo ehf. StartWork
is not affiliated with these companies.
