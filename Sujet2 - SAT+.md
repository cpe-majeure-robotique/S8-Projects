# Sujet2 - SAT+

## En Bref !
1. Faire le pilotage automatique de la voiture à partir de la maquette physique (même chose qu'en TP, mais depuis un STM32)
2. Piloter la voiture du simulateur avsim2D avec volant et pédales:
  - depuis un même PC avec un bus CAN virtuel
  - puis depuis un 2ème PC au travers d'un bus CAN réel
3. En reprenant le programme de la partie 1, lorsque la voiture roule dans le simulateur, le volant doit tourner tout seul

PS : 1 et 2 peuvent être fait indépendament


## Mise en route

- [Téléchargez l'archive du projet](https://github.com/cpe-majeure-robotique/S8-Projects/raw/main/ressources/maquettes-sat-student_ver.zip)
- Dezippez là dans `~/STM32CubeIDE/workspace_1.5.1`
- Avec le navigateur de fichier, entrez dans le dossier dezzipé et double cliquez sur le fichier `.project` (si fichier pas visible, faites Ctrl-H)
- L'IDE stm32CubeIDE devrait s'ouvrir
- Configurez le bon Build config comme sur l'mage ci-dessous
![build config](https://github.com/cpe-majeure-robotique/S8-Projects/blob/main/img/Build_config.png?raw=true)
- Pour compilez faites `Project -> Build all` (ou Ctrl-B, ou raccourci sur le bandeau)
- Pour charger le programme dans la carte :
  - Mettez la carte sous tension (bloc alim 12V)
  - Branchez la carte Nucléo (blanche) en USB au PC
  - dans stm32CubeIDE cliquez sur le bouton vert avec un triangle blanc (play) pour charger le programme dans la carte
