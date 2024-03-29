**SimpleTodo** est un petit gestionnaire de liste de tâches simple avec onglet.
Il est écrit en Python3 et dispose d'une interface GTK3.

![./capture.png](./capture.png)

**Installation :**

Pour une installation rapide et basique, il suffit de récupérer le fichier *simpletodo.py* et de lancer le logiciel avec la commande :

`python3 simpletodo.py`

**Utilisation :**

***Gérer les projets :***

Au premier lancement, un projet par défaut est proposé, il est possible de le renommer via l'entrée de menu « Renommer... » puis d'y ajouter des tâches.
Pour créer un nouveau projet, il suffit de cliquer sur le « + » dans la barre de titre.
De même, pour supprimer un projet, il suffit de cliquer sur le « - ». Toutes les tâches du projets sont évidemment supprimées avec lui.
Via le menu, il est également possible de cloner un projet. Une invite vous demande alors le nom à donner au clone.

***Gérer les tâches :***

Pour ajouter une tâche, il suffit de cliquer sur « Nouvelle tâche » puis de saisir son nom ou sa description.
La case à cocher devant la description de la tâches indique son état (finie / non finie).
À chaque « coche » ou « décoche » d'une tâche, un indicateur de pourcentage accompli est mis à jour et affiché.

Via le menu en bas à gauche, vous pouvez cocher, décocher ou inverser d'un clic l'état de l'ensemble des tâches de votre projet
Vous pouvez ajouter des sous-tâches à une tâche principale. Lorsque toutes les sous-tâches sont complétées, la tâche mère l'est aussi.

![./tasks.png](./tasks.png)

***Raccourcis clavier***

L'application utilise les raccourcis suivants :

- Ctrl + n : créer une nouvelle tâche ;
- Ctrl + e : basculer l'état du mode « Édition ».

**Quitter l'application :**

Le bouton « Quitter » enregistre tous les projets et ferme l'application.

**Fichiers :**

L'application enregistre les projets dans des fichiers séparés dans le répertoire de l'utilisateur sous *$HOME/.local/share/simpletodo*.
