# Am I Synced?
The different ways to tell if your GitHub and GitKraken are synced and that you have the right versions of the .do files (_Français ci-dessous_)

_Video:_ [Am I Synced?](https://www.youtube.com/watch?v=oVu9VVGPFF8&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=12&t=0s)

### Summary 
An overview of the different ways to make sure that GitHub and GitKraken are synced. Whenever there is an Internet connection, GitHub and GitKraken need to be synced to make sure that all users have access to the most up-to-date versions of the .do files

#### By the end of this video, you should be able to:
- Use the icons in the commit graph to identify whether to push or pull
- Use the arrows in the left panel to identify whether to push or pull
- Comfortably sync GitHub and GitKraken as often as possible

### How to Pull and Push
- _Pull_: Click on the Pull button on the toolbar
- _Push_: Click on the Push button on the toolbar


### How to identify whether GitHub and GitKraken are synced
#### Using the commit graph:
- If a branch name appears once in the commit graph, and has both a PMA and a computer icon next to it, GitHub and GitKraken are synced
- If a branch names appears twice in the commit graph, and each branch appearance has either the PMA or the computer icon (but not both) next to it, GitHub and GitKraken are not synced
  - If the branch name with the PMA icon is higher on the commit graph, you need to pull
  - If the branch name with the computer icon is higher on the commit graph, you need to push
- If a branch name appears once in the commit graph, and only has the computer icon next to it, GitHub and GitKraken are not synced
  - You need to push
- If a branch name appears once in the commit graph, and only has the PMA icon next to it, GitHub and GitKraken are not synced
  - You have not yet added the branch to your local. If you want to access the branch, double click on it to import it as a local

#### Using the left panel
- If there are no arrows next to the branch name in the local menu, GitHub and GitKraken are synced
- If there are arrows next to the branch name in the local menu, GitHub and GitKraken are not synced
  - If the arrows are pointing down, you need to pull
  - If the arrows are pointing up, you need to push



### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Branch | A branch is a parallel version of a repository that allows you to work freely without disrupting the master version of a file. PMA uses branches to update .do file content and prepare .do files for round specific data collection |
| Commit | A commit is a way to save a change to a file that also stores information on what changes were made, when and by who. PMA uses commits to systematically document changes to .do files |
| Local | Files and changes that are saved on a local computer within a working directory |
| Master | The default branch that is made each time a new repository is created. At PMA, the master branch contains the template of any give .do file. No changes should be made in the master branch |
| Pull | When changes are taken from the GitHub server to a local copy of the repository. GitKraken pulls data from GitHub to keep the two platforms synced |
| Push | Sending committed changes to a remote version of the repository. GitKraken pushes data to GitHub to keep the two platforms synced |
| Remote | The version of a something (repository/branch/file) that is hosted on GitHub. All PMA repositories, branches and .do files have a remote version on the GitHub server |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |



_________________________________________________________________




# Suis-je synchro ?
Les différentes manières de savoir si votre GitHub et GitKraken sont synchronisés et si vous avez les bonnes versions des .do files 

_Vidéo:_ [Suis-Je Synchro ?](https://www.youtube.com/watch?v=IVayHG1foKA&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=12&t=0s)

### Résumé  
Aperçu de différentes manières de s’assurer que GitHub et GitKraken sont synchronisés. Dès qu’il y a une connexion internet, GitHub et GitKraken doivent être synchronisés pour s’assurer que tous les utilisateurs et utilisatrices aient accès aux dernières versions des .do files. 

#### A la fin de la vidéo, vous devriez être en mesure de :
- Lire les icônes du graphique de commit pour savoir s’il faut push ou pull
- LIre les flèches dans le panel de gauche pour savoir s’il faut push ou pull
- Synchroniser GitHub et GitKraken sans difficulté aussi souvent que possible.


### Comment effectuer les actions Pull et Push
- _Pull_ : Cliquez sur le bouton Pull dans la barre à outils
- _Push_ : Cliquez sur le bouton Push dans la barre à outils


### Comment savoir si GitHub et GitKraken sont synchronisés
#### A l'aide du graphique des commits
- Si le nom d’une branch apparait une fois dans le graphique des commits, avec à la fois le logo de PMA et l’icône d’un ordinateur à côté, cela signifie que GitHub et GitKraken sont synchronisés.
- Si le nom d’une branch s’affiche deux fois dans le graphique des commits, et que chaque apparition de branch a soit le logo de PMA, soit l’icône de l’ordinateur (mais pas les deux), alors GitHub et GitKraken ne sont pas synchronisés.
  - Si le nom de la branch avec le logo de PMA se trouve plus haut sur le graphique du commit, vous devez effectuer l’action Pull
  - Si le nom de la branch avec l’icône de l’ordinateur est plus haut sur le graphique du commit, alors vous devez effectuer l’action Push
- Si le nom d’une branch s’affiche une fois sur le graphique des commits et n’a que l’icône de l’ordinateur à côté, GitHub et GitKraken ne sont pas synchronisés.
  - Vous devrez effectuer l’action Push
- Si le nom d’une branch s’affiche une fois dans le graphique des commits et n’a que le logo de PMA à côté, GitHub et GitKraken ne sont pas synchronisés.
  - Vous n’avez pas encore ajouté la branch à votre local. Si vous souhaitez accéder à la branch, double-cliquez dessus et importez-la en local.

#### Sur le panel de gauche
- S’il n’y a pas de flèche à côté du nom de la branch dans le menu local, GitHub et GitKraken sont synchronisés.
- S’il y a des flèches à côté du nom de la branch dans le menu local, GitHub et GitKraken ne sont pas synchronisés.
  - Si les flèches pointent vers le bas, vous devez effectuer l’action Pull.
  - Si les flèches pointent vers le haut, vous devez effectuer l’action Push.


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Branch | Version parallèle d’un repository permettant de travailler librement sans perturber la version master d’un fichier. PMA utilise des branches pour mettre à jour le contenu des dofiles et les préparer pour la collecte de données d’une vague d’enquête spécifique. |
| Commit | Manière de sauvegarder une modification d’un fichier en stockant aussi des informations sur les changements qui ont été faits, quand et par qui. PMA utilise des commits pour documenter systématiquement les modifications des .do files |
| Local | Les fichiers et modifications sont sauvegardés sur un ordinateur en local dans un working directory. |
| Master | Branch par défaut générée à chaque fois qu’un nouveau repository est créé. À PMA, la master branch contient le modèle de chaque .do file. Aucune modification ne devrait être apportée à la master branch |
| Pull | Lorsque les modifications sont « tirées » (extraites) du serveur GitHub vers une copie d’un repository en local. GitKraken tire les données de GitHub pour que les deux plateformes soient synchronisées. |
| Push | Envoyer des modifications d’un commit vers une version remote (à distance) d’un repository. GitKraken push (pousse) les données sur GitHub pour que les deux plateformes soient synchronisées. |
| Remote | La version de quelque chose (repository/branch/fichier) hébergée sur GitHub. Tous les repositories, branches et .do files de PMA ont une version remote sur le serveur GitHub. |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
