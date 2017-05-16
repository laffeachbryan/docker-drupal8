# REQUIS POUR INSTALLER LE PROJET SUR SA MACHINE. # 

* Docker : version 17.03.0-ce, build 60ccb22
* Docker compose : version 1.11.2, build dfed245
* Composer : version 1.4.1
* Git
### CONFIG GIT ###
Pour ce brancher à git faire la commande suivante : 
<code>git remote add origin https://github.com/laffeachbryan/docker-drupal8</code>
#### Pour installer la première fois le projet ####
Ce rendre dans le dossier <b>docker/image</b><br/>
Lancer la commande suivante : <code>docker build -t local/drupal8 .</code><br />
Une fois l'image docker créer retourner dans le dossier docker <br/>
### ATTENTION ###
Ne surtout pas oublier de changer le docker-compose avec le bon nom de dossier avant de lancer les containers.<br />
Lancer la commande <code> docker-compose up -d </code><br />
Allez dans le dossier web pour lancer un composer update qui aura pour but d'installer des modules par défaut de drupal.<br />
Lancer un navigateur et ce rendre sur localhost pour procéder à l'installation de drupal.<br/>
Enjoy.
