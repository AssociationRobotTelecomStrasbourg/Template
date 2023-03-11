# Template
Voici le template permettant l'aide au suivi des projets de l'association RTS

Comment utiliser ce template et publier ton projet sur Git ?

1. Créez un nouveau dépôt Git vide sur GitHub. Notez le nom du dépôt.

2. Clonez le dépôt du modèle sur votre ordinateur à l'aide de la commande git clone suivie de l'URL du dépôt du modèle. Par exemple :

git clone https://github.com/username/template-repository.git

Remplacez "username" et "template-repository" par le lien suivant : https://github.com/AssociationRobotTelecomStrasbourg/Template

3. Allez dans le répertoire du modèle que vous venez de cloner avec la commande suivante :

cd template-repository

Remplacez "template-repository" par Template.

4. Supprimez le dossier .git du modèle

5. Initialisez un nouveau dépôt Git pour votre projet avec la commande suivante :

git init 

6. Ajoutez tous les fichiers de votre projet avec la commande suivante :

git add .

7. Effectuez un commit avec la commande suivante :

git commit -m "Initial commit"

8. Connectez votre dépôt Git local à votre dépôt GitHub en utilisant la commande suivante :

git remote add origin https://github.com/username/new-repository.git

Remplacez https://github.com/username/new-repository.git par le lien de votre dépôt créé à l'étape 1.

9. Poussez votre projet sur GitHub en utilisant la commande suivante :

git push --set -upstream origin master


![logo](https://user-images.githubusercontent.com/97883569/224491210-221ec3b2-5f8e-453a-960b-218e50e97f09.png)
