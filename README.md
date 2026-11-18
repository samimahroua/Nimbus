# Nimbus

Jeu d'aventure à la première personne, jouable en réalité virtuelle et sur écran.
Nom provisoire.

## Cadre validé

| Sujet | Décision |
|:---:|:---:|
| Univers | Une cité bâtie sur le dos d'une créature géante endormie, qui vole dans les nuages |
| Héros | Un mécanicien, qui détecte les esprits du ciel avec un instrument qu'il a fabriqué |
| Pouvoirs | Vent, foudre, givre, lest ; un geste par pouvoir, doublé d'un bouton |
| Structure | Une cité centrale et quatre ailes, une par pouvoir ; orage scénarisé ; carnet de connaissances |
| Durée | 3 heures de chemin principal, plus du contenu facultatif pour approcher 4 heures |
| Rythme | Chapitres de 20 à 25 minutes, sauvegarde automatique permanente |
| Modes | Écran (clavier et souris) et VR (OpenXR, SteamVR) |
| Intrigue | Tenue secrète : elle se découvre en jouant |

## Choix techniques

- Moteur : Godot 4, rendu Mobile.
- Matériel visé : PS VR2 sur PC, carte graphique d'entrée de gamme (Quadro T2000, 4 Go).
- Décors : kits modulaires libres de droits, assemblés par code ; style low-poly.
- Cible de fluidité en VR : 90 images par seconde.

## Hors périmètre

- Corps à corps contre des personnages humains.
- Vol libre.
- Boucle temporelle chronométrée.
- Voix, cinématiques, animations faciales.
- Infiltration longue : une seule séquence.

## Garde-fous

- Chaque énigme est vérifiée par un programme qui prouve qu'elle a une solution.
- Indices en trois paliers, puis possibilité de passer l'énigme.
- Difficulté des combats abaissée automatiquement après deux échecs.
- Journal automatique de session : temps par zone, échecs, indices utilisés.

## État

Cadre fixé. Développement non commencé.
