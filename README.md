# <p align="center">Bienvenue sur le projet DIGICODE !</p>

<p align="center">Ce programme permet à l’administrateur du réseau de générer et de crypter les codes d’entrées des bâtiments, de surveiller les erreurs de saisie des codes d’accès et de diffusion des codes.</p>

<p align="center"><img src="https://francecentral1-mediap.svc.ms/transform/thumbnail?provider=spo&inputFormat=png&cs=fFNQTw&docid=https%3A%2F%2Fcolstad-my.sharepoint.com%3A443%2F_api%2Fv2.0%2Fdrives%2Fb!leq7VbMHCUu_PHjxxdJthBjYAEQLPhFAjzYKUtNOg5ZT6gBYpzLkSphCYKXIgsHF%2Fitems%2F015QWCDOJTWZGODGMKXNBI5VSRHKZCZ754%3Fversion%3DPublished&access_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJub25lIn0.eyJhdWQiOiIwMDAwMDAwMy0wMDAwLTBmZjEtY2UwMC0wMDAwMDAwMDAwMDAvY29sc3RhZC1teS5zaGFyZXBvaW50LmNvbUA4MjI1MmM0YS0zNTdiLTQ3OWQtYmVmZi1lODAzN2YzZTg3NmYiLCJpc3MiOiIwMDAwMDAwMy0wMDAwLTBmZjEtY2UwMC0wMDAwMDAwMDAwMDAiLCJuYmYiOiIxNjYyNzI0ODAwIiwiZXhwIjoiMTY2Mjc0NjQwMCIsImVuZHBvaW50dXJsIjoiYkEweVZ4OFNEclRjN2pabFRIRHdzL0lpYVpVbnhSTk9GYjVYanduakliST0iLCJlbmRwb2ludHVybExlbmd0aCI6IjExNyIsImlzbG9vcGJhY2siOiJUcnVlIiwidmVyIjoiaGFzaGVkcHJvb2Z0b2tlbiIsInNpdGVpZCI6Ik5UVmlZbVZoT1RVdE1EZGlNeTAwWWpBNUxXSm1NMk10TnpobU1XTTFaREkyWkRnMCIsIm5hbWVpZCI6IjAjLmZ8bWVtYmVyc2hpcHxkYW1pZW4ubm9sbGVAc3RhZGp1dG9yLmNvbSIsIm5paSI6Im1pY3Jvc29mdC5zaGFyZXBvaW50IiwiaXN1c2VyIjoidHJ1ZSIsImNhY2hla2V5IjoiMGguZnxtZW1iZXJzaGlwfDEwMDMyMDAxNzE3MzAyYjVAbGl2ZS5jb20iLCJzaWQiOiI3MDU3OTRlNi1kNWUwLTRiNDEtODg1MC1jYjczZGVkOTNjODYiLCJ0dCI6IjAiLCJ1c2VQZXJzaXN0ZW50Q29va2llIjoiMiIsImlwYWRkciI6IjgxLjI1MC4yNTMuMTg5In0.eDFBNjl2Z0tCaDdXY08wcmV2eUdHamswVVEvb0w0OGdqL0lTT3dHSHZTMD0&cTag=%22c%3A%7BE14CB633-8A99-42BB-8ED6-513AB22CFFBC%7D%2C2%22&encodeFailures=1&width=811&height=412&srcWidth=811&srcHeight=412"></p>

## <p align="center">Prérequis :</p>

L'application est disponible en éxécuatable et en solution source ce qui permettra à de futurs développeurs de travailler dessus.

Pour pouvoir reprendre le projet, il faudra au préalable installer Visual Studio pour ouvrir le fichier solution (.sln) !
<p align="center"><img width="200" height="100" src="https://logos-marques.com/wp-content/uploads/2021/03/Visual-Studio-Logo.png"></p>

## <p align="center">Auteurs :</p>

<p align="center">NOLLE Damien - Chef de projet et développeurs.</p>
<p align="center">DUCHENE Clément et LETELLIER Thomas - Développeurs.</p>

*<p align="center">Nous sommes tous les trois des étudiant en BTS SIO (SLAM) à l'établissement Saint-Adjutor, à Vernon.</p>*

<p align="center"><img width="350" height="100" src="https://www.stadjutor.com/wp-content/uploads/2021/01/logo-stadjutor.png"></p>

<p align="center">M. Lucien SAPIN - Directeur de la Maison des Ligues de Lorraine (M2L).</p>

*<p align="center">Qui nous a commandé le projet et permis sa réalisation.</p>*
<br/>
***<p align="center">TOUT LES DROITS DU PROJET REVIENNENT À LA M2L !</p>***

<p align="center"><img width="130" height="150" src="https://zupimages.net/up/22/36/vjpg.png"></p>

## <p align="center">Standardisation du nom des éléments :</p>

Tout les éléments du projet se nomme de la manière suivante : **\[initial élément]_\[action]**

***Exemple :*** le bouton pour ajouter se nommera *"btn_ajouter"*, la textBox pour le code sera *"tB_Code"*, etc...

## <p align="center">Déploiement :</p>

L'application, une gois générer, doit être mise sur le serveur central ou tout le système des claviers numérique des différents batîments afin de pouvoir déployer les digicodes plus rapidement. Il suffit juste de venir copier-coller le logiciel et de le lancer pour qu'il puisse passé en mode configuration afin de pouvoir connecter les différents claviers.

## <p align="center">Fonctionnalités :</p>

- Mode configuration pour venir configurer les claviers des différents batiments.

- Interface de connexion pour accéder à l'enssemble de l'application via le matricule et le code générer précédement (si aucun code n'a été générer le code par défaut est : 0000).

- Cryptage des code générer.

- En cas d'erreur de saisie des codes ou lors de la génération des codes, un système d'historique/logs est mis en place.

- Système de diffusion des mots de passe aux claviers et aux employés.

## <p align="center">Tehcnologies :</p>

La M2L dispose de claviers numériques sur les murs de leurs différents batiments qui, en saisissant le bon code, permet d'ouvrir la porte. Les claviers sont liés au serveur principal via des câbles afin de les contrôler sur celui-ci nottament via le logiciel DIGICODE.

<p align="center"><img src="https://www.sofernim.com/wp-content/uploads/2016/07/controle_acces_Portes_de_garage.jpg"></p>

## <p align="center">Merci !</p>

***Merci beaucoup à la M2L de nous avoir fait confiance tout au long du projet et merci à l'établissement Saint-Adjutor de nous avoir enseigné tout ce qui a permis la réalisation de celui-ci !***
<br/><br/>
**<p align="right">Version de DIGICODE :** 1.0</p>

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time
irm get.scoop.sh | iex
```