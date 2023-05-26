# Stage-M2-CIC-Radiomic
Dépots de l'ensemble des traveaux de recherche de Master

Ce dépot correspond à l'ensemble des étapes de la radiomic. Nous auront

+ En premier point nous auront l'agorithme d'extraction des caractéristique radiomic 

+ En deuxième lieu la méthode de segmentation

+ En troisième lieu la prédiction sur nos données

1 - Extraction des features Radiomic

# Prérequis
* Créer un environnement virtuel
* Avoir un notebook jupyter déjà installer
* Installer les bibliothèque du fichier requierment.txt (Ce fichier ne précise pas de version car seul les versions recentes seront pris n charge)

Voivi l'arborescence des dossier pour la sauvegarde:

            !------------Image  # Comporte les images IRM de la prostate                
            !
            !------------Patient_ID   # Dans ce dossier nous alons récupérer les indexes les patients en 
            !                           fonction du Grade de Gleason.
            !                                   !--------GG1
            !                                   !--------GG2   ( Dans le dossier Img_msk_resambled nous normalisons les image
lesions --- !-------------Img_msk_resambled-----!--------GG3     en fontion de leurs masques en fonction de leurs grade de Gleason 
            !                                   !--------GG4     avant de procéder à l'extraction ) 
            !                                   !--------GG5
            !
            !-----------ADC_T2_Images_Analyses # Nous récuperons dans ce dossier les feautures radiomic en fonction du grade de Gleason
            !
            !
            !-------------Masks   #Comporte les Masks de chaque image
            
            
   # NB: Tous ses dossiers son déjà créer et existent déjà dans le zip du dossier lesions qui serait présent avec le fichier jupyter.ipynb, 
   # vous n'aurez qu'à cloner le projet , activer votre environnement virtuel puis installer les librairies du fichier requierement.txt
