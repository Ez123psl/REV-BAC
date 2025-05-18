Quiz de Révision Interactif Bac Pro SN
Un projet web “vanilla” (HTML/CSS/JS) pensé pour faciliter les révisions du Bac Pro Systèmes Numériques (SN) et d’autres matières (Histoire, Géographie, EMC, Français). Des quiz dynamiques, responsive et animés pour tester vos connaissances et cibler vos lacunes.

Site en ligne : https://votre-site-de-quiz.example.com](https://rev-bac.vercel.app/

📚 Fonctionnalités principales
15 questions par thème

Feedback immédiat : correction automatique, score et conseils de révision

Interface Desktop & Mobile : barre de navigation déroulante et menu “drawer” optimisé

Animations CSS : sous-menus qui glissent, retours visuels et transitions fluides

Thèmes couverts :

Histoire : Guerre froide, Décolonisation

Géographie : Ressources & Développement Durable, Sociétés & Risques

EMC : Défis de Société & Bioéthique

Français : Œuvres étudiées, Figures de style

Bac Pro SN : Architecture & OS, Réseaux & IP, Systèmes Embarqués, Cybersécurité

🚀 Mise en route
Cloner ou télécharger le dépôt.

Ouvrir index.html dans votre navigateur ou lancer un serveur local (VSCode Live Server, python -m http.server, etc.).

Sélection du quiz

Desktop : choisissez un thème dans la barre du haut pour dérouler le sous-menu.

Mobile : appuyez sur ☰ pour ouvrir le menu latéral, déroulez les catégories et sélectionnez un quiz.

🛠️ Architecture du code
index.html : structure globale, desktop navbar, mobile drawer, containers de quiz, footer

CSS (dans <head>) : variables, layout responsive, animations sub-nav et drawer

JavaScript (fin de <body>) :

Données JSON des questions (quizData)

Génération dynamique des quiz

Gestion de la navigation desktop & mobile

Soumission des réponses & feedback

📦 Technologies utilisées
HTML5

CSS3 (Flexbox, variables, transitions)

JavaScript (ES6+)

Aucun framework externe — tout est “vanilla” pour la légèreté et la simplicité.

⚖️ Licence
Ce projet est distribué sous Licence MIT. Vous êtes libre de l’utiliser et de l’adapter, à condition de conserver la mention d’auteur.
