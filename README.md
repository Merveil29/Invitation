# Invitation

Invitation HTML pour un événement.

## À propos

Ce dépôt contient une page d'invitation (`invitation.html`) à ouvrir dans un navigateur.

## Configuration

Pour que les confirmations soient envoyées sur votre numéro WhatsApp, vous devez configurer le numéro dans le fichier `invitation.html`.

### Étape 1 : Ouvrir le fichier
Ouvrez `invitation.html` dans un éditeur de texte.

### Étape 2 : Modifier le numéro WhatsApp
Recherchez cette ligne (vers la ligne 1056) :

```js
const WHATSAPP_NUMBER = '+229 VOTRE_NUMERO_ICI';
```

Remplacez-la par votre propre numéro au format international (sans espaces inutiles, avec l'indicatif +229) :

```js
const WHATSAPP_NUMBER = '+229 VOTRE_NUMERO_ICI';
```

**Exemple :**
```js
const WHATSAPP_NUMBER = '+229 12345678';
```

### Étape 3 : Tester
Ouvrez `invitation.html` dans votre navigateur, remplissez le formulaire et cliquez sur "Je confirme !" pour vérifier que l'envoi WhatsApp s'ouvre bien sur votre numéro.

## Utilisation

1. Télécharger ou cloner le dépôt
2. Configurer votre numéro WhatsApp (voir ci-dessus)
3. Ouvrir `invitation.html` dans votre navigateur web
4. Partager le lien ou la page selon vos besoins
