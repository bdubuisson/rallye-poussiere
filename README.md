# Rallye Poussière

Petit jeu de course tout-terrain en 3D (three.js), jouable à 1 ou 2 joueurs en écran partagé, plus des voitures pilotées par l'ordinateur, avec des F1 façon arcade, sur un circuit en terre avec 7 tremplins, 4 catapultes, 3 loopings pilotables, des bosses et des flaques de boue.

Cascades : en l'air, le bouton de cascade (E pour le joueur 1, Ctrl droit ou 0 du pavé pour le joueur 2, Y/LB à la manette) fait un salto, ou un tonneau en tournant ; atterrir après une cascade finie rapporte une nitro. Dans un looping, on entre par la file de gauche et on garde gaz, volant et nitro ; sans assez de vitesse, on décroche. La file de droite, ou un tremplin pris par l'arrière, éjecte la voiture. En marche arrière et très haut dans les airs, le feu sort des pots latéraux et des pneus du circuit. Caméra de poursuite derrière la voiture, légèrement à droite. Collisions de corps rigides : les voitures pivotent selon le point d'impact.

**Jouer :** https://bdubuisson.github.io/rallye-poussiere/

## Commandes
- **Joueur 1 (rouge)** : Z Q S D en AZERTY ou W A S D en QWERTY (mêmes touches physiques) + nitro Maj/Shift gauche ou Espace
- **Joueur 2 (bleu)** : flèches + nitro Entrée
- Manettes : A = gaz, B = frein, X/RB = nitro
- Tablette : accélération automatique, ◀ ▶ pour tourner, les deux ensemble pour reculer, 🔥 = nitro
- M = son, Échap = menu

Un seul fichier `index.html` (three.js r128 chargé depuis cdnjs) : il suffit de l'ouvrir dans un navigateur.
