# Scope Duel

Jeu de sniper 1v1 en vue à la première personne contre un bot ou un pote en ligne, dans le navigateur (HTML + Three.js, un seul fichier).

**Jouer :** https://aurelien-d.github.io/ShotGame/

- **1v1 en ligne entre potes** : « Un pote (en ligne) » → « Créer une partie », puis envoie le code (5 lettres) ou le lien. L'hôte choisit map, style et manches.
- 3 maps : Docks, Tour, Ruelles
- 4 armes : MK7, FAUCON, TITAN (traverse les murs), RAFALE (semi-auto)
- Style CS (précision à l'arrêt, contre-strafe) ou Arcade (bhop, air strafe, glissade)
- Quickscope, noscope, 360°, headshot, wallbang

Commandes : ZQSD / WASD, souris pour viser, clic droit lunette, clic gauche tirer, Espace sauter, C s'accroupir, Maj marcher, R recharger, 1–4 changer d'arme avant le GO, P pause.

## Jeu en ligne

Connexion directe entre les deux navigateurs (WebRTC via [PeerJS](https://peerjs.com/)), sans serveur de jeu : le serveur public PeerJS sert seulement à mettre les deux joueurs en relation. Certains réseaux très fermés (entreprise, certains opérateurs mobiles) peuvent bloquer la connexion directe.
