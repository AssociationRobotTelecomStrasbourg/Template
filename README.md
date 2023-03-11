# Template
Voici le template permettant l'aide au suivi des projets de l'association RTS

Comment utiliser ce template et publier ton projet sur Git ?

0. Si vous n'en avez pas : créez une clé ssh : 

utiliser la commande ssh-keygen

la mettre sur cette arborescence: C:\users<yourusername>.ssh\id_rsa
mdp useless (juste pour vous en local si un accès physique à la machine est possible)
et  vous trouverez votre clef publique ici: C:\Users<nomUtilisateur>.ssh\id_rsa.pub

Ajoutez votre clé public à votre profil Github, pour celà cliquez sur votre photo de profil>settings>SSH and GPC keys>New SSH key
Ouvrez le fichier id_rsa commençant par ssh-rsa, copier et coller la. 

1. Créer un nouveau dépôt Git vide sur GitHub. Notez le nom du dépôt.

2. Cloner le dépôt du modèle sur votre ordinateur à l'aide de la commande git clone suivie de l'URL du dépôt du modèle. Par exemple :

git clone https://github.com/username/template-repository.git

Remplacer "username" et "template-repository" par le lien suivant : https://github.com/AssociationRobotTelecomStrasbourg/Template

3. Aller dans le répertoire du modèle que vous venez de cloner avec la commande suivante :

cd Template

Changer le nom Template par le nom souhaité avec la commande suivante : 

mv Template nouveau_dossier

4. Supprimer le dossier .git du modèle

5. Initialiser un nouveau dépôt Git pour votre projet avec la commande suivante :

git init 

6. Ajouter tous les fichiers de votre projet avec la commande suivante :

git add .

7. Effectuer un commit avec la commande suivante :

git commit -m "Initial commit"

8. Connecter votre dépôt Git local à votre dépôt GitHub en utilisant la commande suivante :

git remote add origin https://github.com/username/new-repository.git

Remplacez https://github.com/username/new-repository.git par le lien de votre dépôt créé à l'étape 1.

9. Pousser votre projet sur GitHub en utilisant la commande suivante :

git push --set-upstream origin master


![logo](https://user-images.githubusercontent.com/97883569/224491210-221ec3b2-5f8e-453a-960b-218e50e97f09.png)
