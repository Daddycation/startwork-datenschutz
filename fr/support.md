# Aide StartWork

> [Deutsch](../support) · [English](../en/support) · [Português](../pt/support) · [Español](../es/support)

StartWork saisit le temps de travail dans Jira. L'app fonctionne sur votre
appareil et ne communique qu'avec **votre propre** instance Jira.

**Contact :** [info@iamnotadev.xyz](mailto:info@iamnotadev.xyz)
Réponse en général sous quelques jours. Vous pouvez écrire en français ; la
réponse arrive en anglais ou en allemand.

Pour être aidé plus vite, indiquez : la version de l'app, si vous utilisez
Jira Cloud ou Jira Server/Data Center, et le texte exact du message d'erreur.

---

## Questions fréquentes

### Quelles versions de Jira sont prises en charge ?

Jira Cloud (`…atlassian.net`) ainsi que Jira Server et Data Center. Avec
Cloud, vous vous connectez avec votre e-mail et un jeton d'API ; avec Server
et Data Center, avec un jeton d'accès personnel.

### Où obtenir un jeton ?

**Jira Cloud :** sur <https://id.atlassian.com/manage-profile/security/api-tokens>.

**Jira Server / Data Center :** dans votre Jira, sous *Profil → Personal
Access Tokens*. Si cette entrée manque, vos administrateurs Jira l'ont
désactivée — seule une demande auprès d'eux peut aider.

### L'app dit que mon ticket n'existe pas.

Soit la clé est erronée, soit votre compte n'a pas le droit de voir ce
ticket. Vous pouvez vérifier les deux en ouvrant le ticket dans Jira.

### Je ne peux pas saisir de temps sur un ticket.

Si le ticket est dans un statut comme « fermé » ou « terminé », Jira bloque
la saisie de temps. Ce n'est pas contournable dans Jira non plus — choisissez
un ticket ouvert.

### Nous utilisons Tempo. Est-ce que ça marche ?

Oui. StartWork écrit une saisie de temps Jira standard, et Tempo lit ces
saisies. **Mais :** si votre entreprise impose des champs Tempo (*Work
Attributes*), ils restent vides. Que cela suffise dépend de votre
configuration.

### Que deviennent mes données ?

Elles restent sur l'appareil. Il n'y a ni serveur du fournisseur, ni compte,
ni statistiques. Les détails sont dans la
[politique de confidentialité](./).

### Comment tout supprimer ?

*Icône d'engrenage → Effacer toutes les données de cet appareil.* Cela
supprime les identifiants, vos propres tuiles et tout l'historique. Le temps
déjà saisi dans Jira n'est pas concerné — il se trouve sur le serveur Jira.

### Que fait « Peaufiner » ?

Le bouton envoie votre commentaire de saisie à Anthropic et reçoit en retour
une formulation factuelle. Il est **désactivé** par défaut et nécessite deux
choses : votre propre clé Anthropic et votre consentement explicite. Sans les
deux, rien ne quitte l'appareil. Vous pouvez retirer votre consentement à
tout moment via l'icône d'engrenage.

### Quelles langues l'app parle-t-elle ?

Français, anglais, allemand, portugais et espagnol. Elle suit la langue de
votre iPhone ; sous l'icône d'engrenage, vous pouvez en choisir une
explicitement.

---

Jira est une marque d'Atlassian, Tempo une marque de Tempo ehf. StartWork
n'est pas affilié à ces entreprises.
