🐦 Floppy Perroquet 

📌 Présentation

Ce projet est une reproduction d'un célèbre jeu, développée en HTML, CSS et JavaScript.

Le principe est simple : contrôler un oiseau afin de lui faire traverser des obstacles sans les toucher. Le joueur doit maintenir l'oiseau en vol et passer à travers les espaces entre les tuyaux afin d'obtenir le meilleur score possible.

Ce projet a été réalisé dans le cadre de ma formation de Développeur Web et Web Mobile (DWWM).

---

🎯 Objectifs du projet

- Reproduire les mécaniques principales de Flappy Bird
- Mettre en pratique JavaScript
- Manipuler les événements utilisateur
- Gérer les déplacements et les collisions
- Mettre en place un système de score
- Créer une interface de jeu simple et interactive
- Organiser les fichiers d'un projet web

---

🎮 Principe du jeu

Le joueur contrôle un oiseau qui avance automatiquement.

L'objectif est de :

- 🐦 Faire voler l'oiseau
- 🟩 Éviter les tuyaux
- ⭐ Traverser un maximum d'obstacles
- 🏆 Obtenir le meilleur score possible

La partie se termine lorsque l'oiseau entre en collision avec un obstacle ou le sol.

---

🕹️ Contrôles

Action| Contrôle
Faire monter l'oiseau| 🖱️ Clic souris
Faire monter l'oiseau| ⌨️ Touche clavier
Rejouer| 🔄 Bouton de redémarrage

---

🎨 Design

L'interface reste volontairement simple afin de mettre l'accent sur le gameplay.

Les éléments visuels comprennent notamment :

- 🐦 Le personnage principal
- 🌤️ Le décor
- 🟩 Les tuyaux
- 🌱 Le sol
- 🔢 Le système de score

Les différents éléments graphiques sont regroupés dans le dossier "media".

---

✨ Fonctionnalités

- 🐦 Déplacement de l'oiseau
- 🟩 Génération et déplacement des obstacles
- 💥 Détection des collisions
- 🔢 Calcul du score
- 🎮 Gestion des interactions utilisateur
- 🔄 Possibilité de recommencer une partie
- 🖼️ Utilisation d'éléments graphiques personnalisés

---

🛠️ Technologies utilisées

Technologie| Utilisation
HTML5| Structure du jeu
CSS3| Mise en page et design
JavaScript| Logique du jeu et interactions
Git / GitHub| Gestion du versioning

---

📁 Structure du projet

Flappy-bird/
│
├── media/
│   └── ... ressources graphiques
│
├── index.html
├── script.js
├── style.css
└── README.md

---

🚀 Installation

1. Cloner le projet

git clone https://github.com/Alliiissonnee/Flappy-bird.git

2. Accéder au projet

cd Flappy-bird

3. Lancer le jeu

Ouvrir le fichier "index.html" dans un navigateur.

Pour le développement, il est recommandé d'utiliser Live Server avec Visual Studio Code.

---

💻 Fonctionnement

La logique du jeu est principalement gérée par JavaScript.

Le script prend notamment en charge :

- la position de l'oiseau ;
- ses déplacements ;
- le mouvement des obstacles ;
- les interactions avec le joueur ;
- les collisions ;
- le calcul du score ;
- la fin de partie ;
- le redémarrage du jeu.

---

 Améliorations possibles

- [ ] Ajouter un meilleur score sauvegardé avec "localStorage"
- [ ] Ajouter des effets sonores
- [ ] Ajouter plusieurs niveaux de difficulté
- [ ] Ajouter une animation plus avancée de l'oiseau
- [ ] Ajouter un écran d'accueil
- [ ] Ajouter un écran de Game Over plus travaillé
- [ ] Optimiser l'expérience sur mobile
- [ ] Ajouter un classement des meilleurs scores
- [ ] Mettre le jeu en ligne avec une démo accessible directement depuis GitHub Pages

---

👩‍💻 Auteur

Alison Faidherbe

Projet réalisé dans le cadre de la formation Développeur Web et Web Mobile (DWWM).

---

📄 Licence

Projet réalisé à des fins pédagogiques.
