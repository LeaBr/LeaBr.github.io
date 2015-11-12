Création du dossier "sites" dans home

Ouvrir un terminal. Se placer dans "home" et entrer les commandes suivantes :

	-> sudo mkdir sites
	    entrer votre mot de passe

	-> sudo chmod 777 sites


Installation de Jekyll

http://jekyllrb.com/docs/installation/

Dans le terminal écrire :	

	-> sudo apt-get install jekyll
	    Après cette opération, 52,5 Mo d'espace disque supplémentaires seront utilisés	    Souhaitez-vous continuer ? 
	    entrer "o" pour oui puis valider


Création d'un fichier index.html

Créer un fichier index.html dans le répertoire sites


Lancement de Jekyll

	-> jekyll build index.html
	-> jekyll serve -w  // le -w permet d'afficher les changements apporté au fichiers 


Mettre à jour Jekyll

GitHub

Créer un compte Git sur le site https://github.com/
Puis suivre les instructions de https://pages.github.com/

