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

![image]([https://github.com/HEPL-Dosogne/FreeRTOS/blob/main/BlockDiagram_FinalProject.png](https://private-user-images.githubusercontent.com/159046303/400462923-d8648b8d-fd5f-48eb-8c95-0d0720d2d1b1.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzYxNzY1OTYsIm5iZiI6MTczNjE3NjI5NiwicGF0aCI6Ii8xNTkwNDYzMDMvNDAwNDYyOTIzLWQ4NjQ4YjhkLWZkNWYtNDhlYi04Yzk1LTBkMDcyMGQyZDFiMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMTA2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDEwNlQxNTExMzZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05Y2VmOTVhMmFiNTY1OWRjNTM3NGIxZWRiOTEyN2Y0MmIyYTA2NDIwMDMxNTYyOWEyMjc5MzhiOGQzNGJjNWM5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9._ee6mN9hKipXRU__-xrhyqAR6Ijbbk7Ak5pMq_jW4Os)) 
