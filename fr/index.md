# Politique de confidentialité — StartWork

État au 28 septembre 2026 · Informations selon l'art. 13 du RGPD

> Cette traduction est fournie pour votre commodité. Seule la
> [version allemande](https://daddycation.github.io/startwork-datenschutz/)
> fait foi.
>
> [English](https://daddycation.github.io/startwork-datenschutz/en/) · [Português](https://daddycation.github.io/startwork-datenschutz/pt/) · [Español](https://daddycation.github.io/startwork-datenschutz/es/)

## L'essentiel en trois phrases

StartWork fonctionne sur votre appareil. Le fournisseur de cette app
**ne collecte, ne stocke et ne reçoit aucune donnée vous concernant** — il n'y
a ni serveur du fournisseur, ni compte, ni statistiques, ni suivi, ni
identifiant publicitaire.

Les données ne quittent votre appareil que vers des destinations **que vous
choisissez vous-même**.

## 1. Responsable du traitement

```
Philip Müller
Theaterstraße 27
09111 Chemnitz
Allemagne

E-mail : info@iamnotadev.xyz
```

En vertu du règlement européen sur les services numériques (DSA), ces mêmes
coordonnées figurent comme informations sur le commerçant sur la page de
l'app dans l'App Store. C'est obligatoire pour une app payante et ne peut pas
être désactivé.

## 2. Ce qui est enregistré sur l'appareil

| Données | Où | Finalité |
|---|---|---|
| Adresse de votre instance Jira, e-mail (Cloud uniquement), réglages | Stockage de l'appareil (iOS : UserDefaults) | pour ne pas avoir à les saisir à chaque fois |
| Jeton d'accès Jira, clé IA | **Trousseau de l'appareil** (iOS : Keychain) | connexion à votre instance Jira |
| Vos saisies de temps (ticket, durée, commentaire, heure) | Stockage de l'appareil | vue du jour et des jours précédents |

Rien de tout cela n'est transmis au fournisseur. **Base juridique :**
art. 6, par. 1, point b) du RGPD — sans ces données, l'app ne peut pas
remplir sa fonction.

## 3. Où vont les données

### 3.1 Votre instance Jira

Lorsque vous saisissez du temps, StartWork envoie la clé du ticket, la durée,
l'heure de début et votre commentaire **au serveur Jira que vous avez
vous-même indiqué**. Votre jeton est envoyé pour la connexion ; lors de la
recherche d'un ticket, sa clé est envoyée.

Qui exploite ce serveur et ce qui s'y passe **n'est pas** déterminé par le
fournisseur de cette app — le plus souvent, c'est votre employeur ou
Atlassian. L'exploitant de l'instance est responsable de ce traitement.

### 3.2 Anthropic (facultatif, uniquement avec votre consentement)

La fonction « Peaufiner » envoie **votre commentaire de saisie avec la clé et
le titre du ticket** à Anthropic (`api.anthropic.com`, États-Unis), où le
texte est traité et renvoyé reformulé.

Cela se produit **uniquement** si vous

1. avez enregistré votre propre clé Anthropic **et**
2. avez expressément accepté le transfert dans une fenêtre distincte **et**
3. utilisez effectivement ce bouton.

**Base juridique :** art. 6, par. 1, point a) du RGPD (consentement). Le
transfert vers les États-Unis a lieu sur la base de la relation contractuelle
entre vous et Anthropic — vous utilisez votre propre accès.

**Retrait :** à tout moment via l'icône d'engrenage, sans justification et
sans restreindre le reste de l'app. Le retrait vaut pour l'avenir.

Politique de confidentialité d'Anthropic :
<https://www.anthropic.com/legal/privacy>

### 3.3 Rien d'autre

Pas de statistiques, pas de rapports de plantage, pas de réseaux
publicitaires, pas de polices ni de scripts provenant de serveurs tiers.
L'app ne contient aucun composant qui ouvre une connexion sans action de
votre part.

## 4. Durée de conservation

Jusqu'à ce que vous les supprimiez. Il n'y a pas de suppression automatique.

**Tout supprimer :** icône d'engrenage → « Effacer toutes les données de cet
appareil ». Cela supprime les identifiants, la clé IA, vos propres tuiles et
tout l'historique des saisies. Si l'app est supprimée, tout disparaît avec
elle.

Le temps **déjà saisi dans Jira** n'est pas concerné — il se trouve sur le
serveur de votre instance et doit y être supprimé.

## 5. Vos droits

Accès, rectification, effacement, limitation, portabilité et opposition
(art. 15 à 21 du RGPD), ainsi que le droit d'introduire une réclamation
auprès d'une autorité de contrôle (art. 77 du RGPD).

En pratique : le fournisseur ne détenant **aucune** donnée vous concernant,
il n'y a rien à communiquer ni à supprimer. Toutes les données se trouvent
sur votre appareil, sous votre contrôle. Pour les données de votre instance
Jira, adressez-vous à son exploitant.

## 6. Enfants

L'app s'adresse aux professionnels, pas aux enfants.

## 7. Modifications

La date en haut de page est mise à jour lorsque cette politique change. Toute
modification importante des transferts de données nécessite un nouveau
consentement.
