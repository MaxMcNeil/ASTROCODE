# Astrocode

Site vitrine (page unique) pour les consultations Astrocode : dons, questions flash, guidances, thèmes astraux et boutique.

## Mettre le site en ligne avec GitHub Pages (gratuit)

1. Crée un nouveau dépôt sur GitHub, par exemple `astrocode`.
2. Ajoute le fichier `index.html` de ce dossier à la racine du dépôt (glisser-déposer sur la page GitHub, ou via git).
3. Dans le dépôt : **Settings** → **Pages**.
4. Sous « Build and deployment », choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`. Enregistre.
5. Après 1 à 2 minutes, le site est accessible à une adresse du type :
   `https://<ton-pseudo-github>.github.io/astrocode/`
6. C'est ce lien que tu partages pendant tes lives.

## Ce que fait le site

- Une seule page, mobile et PC, dans les couleurs et polices demandées (Cinzel / Montserrat, indigo + or).
- Bouton « Faire un don » fixé en haut de page.
- Chaque prestation a un bouton « Choisir » qui affiche un récapiulatif et amène vers la section paiement.
- La section paiement affiche l'IBAN/BIC avec bouton « Copier », et un lien mail pré-rempli (objet « Paiement voyance ») pour que le client te confirme son virement.

## Point important — à savoir

Le site est **statique** (hébergé gratuitement sur GitHub Pages) : il ne peut pas déclencher automatiquement un virement SEPA ni envoyer un email tout seul quand quelqu'un paie. Concrètement :
- Le client copie l'IBAN et fait le virement lui-même depuis sa banque.
- Le bouton mail ouvre une brouillon pré-rempli, mais c'est le client qui doit l'envoyer.

Si tu veux un jour automatiser (email automatique dès réception du virement, paiement par carte bancaire, etc.), il faudra un service tiers (ex. Stripe, ou une intégration bancaire), ce qu'un simple site GitHub Pages ne permet pas — dis-le-moi si tu veux qu'on regarde ça plus tard.
