# FreeRTOS
Exemples FreeRTOS on Arduino Mega

Ce github est utiliser afin de stocker les différents exemples de code FreeRTOS du cours "Real Time Multitasking" ainsi que le projet finale lié à ce cours.

# Final Project : Thermostat

Le but de ce projet, sur base des exemples et de la théorie vue en cours, est de créer un système de thermostat a l’aide du matériel fournit. 

Le code mesure et affiche sur un écran lcd la température et la luminosité en temps réel ainsi que la température voulue,
réglable grâce à un potentiomètre. 
Une led représente le système de chauffe et s’allume uniquement si la température demandée excède la température mesurée. 
Le capteur de luminosité tant qu’à lui, permet d’adapter automatiquement la luminosité de l’écran lcd en fonction de l’environnement. 

Ce code utilise le modèle de tâches productrices / consommatrices. Les capteurs de luminosité et de température ainsi que le potentiomètre sont les tâches productrices. Le lcd et la led, les tâches consommatrices. 

Le code est trouvable [ici](FinalProject)

![image](https://github.com/HEPL-Dosogne/FreeRTOS/blob/main/BlockDiagram_FinalProject.png) 
