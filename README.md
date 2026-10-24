# Copeaux & Commandes

Un roguelite d'atelier en 3D pour réviser la préparation de chantier en **agencement intérieur** : relevés, lecture de plan, nomenclatures, dossier chiffré et commandes AutoCAD.

**Jouer : https://emericch.github.io/copeaux-et-commandes/**

## Principe

Chaque chantier se joue en trois actes : relevé sur site, bureau d'études, puis chiffrage et livraison. Sur le plan du chantier, tu choisis ton chemin de case en case. Dans chaque combat, une bonne réponse fait frapper ton perso, une erreur le fait encaisser. Les séries de bonnes réponses et la mise (×2, ×3) rendent les coups plus forts.

Au programme :

- QCM métier, vrai ou faux, mot à trouver ;
- relevés et calculs de chantier ;
- plans où il faut repérer les erreurs ;
- nomenclatures et dossiers techniques à remplir ligne par ligne ;
- commandes AutoCAD à taper (alias) ;
- questionnaire et entretien d'entraînement pour faire le point.

Les questions de relevé, de métier et d'entretien citent leur source. Le carnet suit ta progression par domaine, sur 14 jours, avec tes points faibles.

## Une progression par joueur

- Chaque joueur a sa propre sauvegarde, gardée dans le navigateur qu'il utilise. Rien n'est envoyé sur un serveur.
- Sur un même appareil, plusieurs personnes peuvent jouer chacune avec sa progression : **Accueil → Changer de joueur**, ou **Réglages → Joueur**.
- Pour continuer sur un autre appareil : **Exporter ma progression** (un fichier `.json`), puis **Importer une progression** sur l'autre appareil.
- Attention : vider les données du navigateur efface la progression. Exporte-la de temps en temps.

## Configuration

- Un navigateur récent (Chrome, Edge, Firefox ou Safari, ordinateur ou téléphone) avec WebGL 2.
- Une connexion Internet : les personnages et les décors 3D se chargent avant chaque combat. Si l'appareil peine, le jeu coupe de lui-même les effets les plus lourds.

## Contenu du dépôt

| Chemin | Contenu |
|---|---|
| `index.html` | le jeu complet (code, interface, questions) |
| `models/` | personnages, outils et meubles en 3D, un fichier par modèle |
| `music/` | les musiques du jeu |

Il n'y a rien à installer ni à compiler : le site est servi tel quel par GitHub Pages.

## Crédits

- Conception, questions et musique : Emeric Chenay
- Personnages, outils et décors 3D générés avec [Meshy](https://www.meshy.ai)
- Rendu 3D : [three.js](https://threejs.org) (licence MIT)
- Polices : Cinzel, EB Garamond et Courier Prime via [Google Fonts](https://fonts.google.com) (licence SIL Open Font)

© 2026 Emeric Chenay. Tous droits réservés.
