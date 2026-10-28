# Scope Duel

Jeu de sniper 1v1 en vue à la première personne contre un bot ou un pote en ligne, dans le navigateur (HTML + Three.js, un seul fichier).

**Jouer :** https://aurelien-d.github.io/ShotGame/

- **1v1 en ligne entre potes** : « Un pote (en ligne) » → « Créer une partie », puis envoie le code (5 lettres) ou le lien. L'hôte choisit map, style et manches.
- 5 maps (Docks, Tour, Ruelles, Hangar, Toits) ou une map aléatoire à chaque manche, avec tremplins et plusieurs points d'apparition
- Mouvement façon STRAFTAT : bhop, air strafe, course sur les murs et saut de mur, glissade, manches éclair
- Départ au couteau, armes jetables posées sur la map (MK7, FAUCON, TITAN qui traverse les murs, RAFALE semi-auto, POMPE, REVOLVER), lancer d'arme qui sonne ou tue à la tête, propulsion à la pompe et au Titan
- Se pencher (A/E), bruits de pas spatialisés de l'adversaire
- Rendu soigné : ciel avec soleil et nuages, reflets d'environnement, textures en relief, bloom et étalonnage, fumée et poussière, bot animé, mains en vue subjective. Réglage Graphismes (Bas / Moyen / Élevé), avec passage automatique en Moyen si l'image rame
- Quickscope, noscope, 360°, headshot, wallbang, kill sur le mur, dans le dos, au lancer

Commandes : ZQSD / WASD, souris pour viser, clic droit lunette, clic gauche tirer (couteau : frapper), Espace sauter (contre un mur : rebondir), Maj ou C glisser, C s'accroupir, A/E se pencher, F lancer son arme, G prendre une arme au sol, P pause.

## Jeu en ligne

Connexion directe entre les deux navigateurs (WebRTC via [PeerJS](https://peerjs.com/)), sans serveur de jeu : le serveur public PeerJS sert seulement à mettre les deux joueurs en relation. Certains réseaux très fermés (entreprise, certains opérateurs mobiles) peuvent bloquer la connexion directe.
