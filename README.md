# EMENDAR — V5 prête pour préparation à la publication

## Corrections visuelles validées
- suppression du bandeau qui chevauchait « Système de management » ;
- les quatre tuiles utilisent maintenant toutes « En savoir plus » ;
- chaque bouton de tuile reprend la couleur de sa rubrique ;
- « Découvrir mon parcours » est désormais un bouton vert.

## Préparation technique ajoutée
- métadonnées SEO et partage social sur les pages ;
- favicon ;
- robots.txt ;
- sitemap.xml préparé pour `https://emendar-iso17025.fr/` ;
- fichier `.nojekyll` pour GitHub Pages ;
- accessibilité clavier et respect de `prefers-reduced-motion`.

## À compléter AVANT mise en ligne publique
1. Mentions légales : statut juridique, SIREN/SIRET, adresse à afficher, responsable de publication et hébergeur.
2. Formulaire : remplacer le formulaire `mailto:` de démonstration par une solution définitive.
3. Vérifier l'affichage mobile sur de vrais appareils.
4. Publier d'abord sur GitHub Pages pour recette.
5. Connecter ensuite `emendar-iso17025.fr` et vérifier les DNS sans modifier les enregistrements de messagerie.

## V6 — formulaire
- formulaire Contact connecté à Web3Forms ;
- anti-bot honeypot ajouté ;
- redirection après envoi vers `merci.html` ;
- page de confirmation aux couleurs EMENDAR ;
- mention de confidentialité sous le formulaire ;
- page confidentialité mise à jour pour signaler l'utilisation de Web3Forms.

### Test à réaliser après dépôt GitHub
Envoyer une demande test depuis la page Contact publique et vérifier :
1. redirection vers `merci.html` ;
2. réception de l'email à l'adresse EMENDAR ;
3. présence de la soumission dans le tableau de bord Web3Forms ;
4. qualité de présentation du message reçu.


## V7 — Mentions légales

La page mentions-legales.html a été complétée avec les informations administratives d’EMENDAR et une information RGPD adaptée au formulaire de contact. L’adresse publique de contact affichée dans le pied de page a été harmonisée vers contact@emendar-iso17025.fr.
