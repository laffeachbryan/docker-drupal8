# REQUIS POUR INSTALLER LE PROJET SUR SA MACHINE. # 

* Docker : version 17.03.0-ce, build 60ccb22
* Docker compose : version 1.11.2, build dfed245
* Composer : version 1.4.1
Git

#### Pour installer la première fois le projet ####
Ce rendre dans le dossier <b>docker/image</b><br/>
Lancer la commande suivante : <code>docker build -t local/drupal8 .</code><br />
Une fois l'image docker créer retourner dans le dossier docker <br/>
Lancer la commande <code> docker-compose up -d </code> 
Lancer un navigateur et ce rendre sur localhost pour procéder à l'installation de drupal.<br/>
Enjoy.
