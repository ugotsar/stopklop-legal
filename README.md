# stopklop-legal

Pages légales publiques de l'application Stopklop, servies par GitHub Pages.

## Mise en ligne

1. Sur GitHub, cliquer sur **New repository**, nommer le dépôt `stopklop-legal`, le laisser **Public**, créer.
2. Sur la page du dépôt vide, cliquer sur **uploading an existing file** et déposer les six fichiers de ce dossier (les cinq `.html` et `style.css`).
3. Onglet **Settings**, menu de gauche **Pages**, section *Build and deployment* : choisir la source **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Attendre une à deux minutes. L'adresse devient :
   `https://ugotsar.github.io/stopklop-legal/`

## Adresses à reporter dans les boutiques

| Usage | URL |
|---|---|
| Politique de confidentialité (Apple et Google) | `.../confidentialite.html` |
| URL d'assistance (fiche App Store) | `.../assistance.html` |
| CGU / EULA (à lier depuis l'écran d'abonnement) | `.../cgu.html` |
| Mentions légales | `.../mentions-legales.html` |

## Avant publication : champs à compléter

Les passages surlignés en beige dans les pages contiennent des valeurs manquantes.

- SIREN et numéro de TVA intracommunautaire (après immatriculation de la SASU)
- Nom du président, pour la direction de la publication
- Région d'hébergement Firestore, visible dans la console Firebase
- Médiateur de la consommation à désigner

Rechercher `todo` dans les fichiers pour les retrouver tous.

## Domaine personnalisé

Si `stopklop.com` est acquis : Settings, Pages, *Custom domain*, saisir `stopklop.com`, puis créer chez le registrar un enregistrement CNAME `www` pointant vers `ugotsar.github.io`, et les quatre enregistrements A de GitHub Pages pour le domaine nu. Cocher ensuite **Enforce HTTPS**.
