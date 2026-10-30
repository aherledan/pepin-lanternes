# Pépin et les Lanternes Célestes

Un petit jeu de plateforme 3D jouable directement dans le navigateur.

Le ciel de l'Archipel s'est éteint. Aide Pépin, un petit esprit-graine, à retrouver les 6 lanternes célestes cachées sur les îles flottantes : le Grand Arbre, le phare, l'île-nuage, l'Île des Piliers, l'Île Mécanique et l'Arène des Ombrons.

**▶ Jouer : https://aherledan.github.io/pepin-lanternes/**

## Commandes

| Action | Clavier et souris | Manette |
|---|---|---|
| Se déplacer | ZQSD (WASD en QWERTY) ou flèches | Stick gauche |
| Sauter · deux fois pour un double saut · maintenir pour planer | Espace | A |
| Tourbillon (renverse les Ombrons) | Maj ou clic | X ou B |
| Tourner la caméra · zoomer | Souris, A/E (Q/E en QWERTY) · molette | Stick droit |
| Musique · pause | M · P | Start (pause) |

Sur téléphone : joystick à gauche, boutons à droite, et glisser le doigt sur l'écran pour tourner la caméra.

## Lancer en local

Ouvre `index.html` dans un navigateur récent. Une connexion internet est nécessaire pour charger Three.js et les polices.

## Technique

Tout tient dans `index.html` : rendu 3D avec [Three.js](https://threejs.org) 0.160 (chargé depuis jsDelivr), physique, ennemis et sons (WebAudio) écrits à la main, sans aucune image ni fichier audio. Le personnage, les niveaux et la musique sont originaux.
