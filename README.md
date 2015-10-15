# BlackPandem.github.io  

- Ecrire un fichier readme.md : permet d'écrire du texte avec du style avec différents symboles.

> dillinger.io, github.io, etc.  

SSG : Static Site Generator  

> http://jekyllrb.com  

NodeJS : JavaScript et fonctionne avec Ruby, Pearl, etc.

*Git* est un logiciel de gestion de versions décentralisé. C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2.

####Installation de Jekyll sur Linux

- Sur la machine virtuelle, ouvrir le terminal et se situer dans la racine de l'utilisateur
```sh
cd home  
cd atc123
```
- Création du dossier "Sites"
```sh
mkdir Sites
```

- Installer jekyll en ligne de commande grâce aux instructions du site jekyll en installant le langage ruby.
```sh  
sudo apt-get install ruby
sudo apt-get install jekyll  

```

Créer le dossier du site web avec jekyll et lancer le serveur jekyll.  

```sh  
jekyll new prevots-website 
cd prevots-website  
jekyll serve
```
> serveur localhost:4000  
> Le serveur Jekyll est actif, ne pas oublier de l'arrêter !  
> Github lance un serveur Jekyll pour éviter de revenir sur le serveur de git à chaque mise à jour.

- Editer le fichier index.html
-  installer une application

```sh  
sudo apt-get install nomApplication
```

- Suivre github page pour créer une repository.

#### Pour cloner le projet sur la machine virtuelle

```sh  
git clone https://github.com/username/username.github.io
```  

#### Aller dans le dossier repository de git sur la machine virtuelle et écrire dans l'index html

```sh  
cd username.github.io  

echo "Hello World" > index.html

git add --all  

git commit -m "Initial commit"  

git push -u origin master  

```  

- Voir les commits  

```sh 
git log
``` 

> http://username.github.io. pour accéder à la page : http://blackpandem.github.io.
