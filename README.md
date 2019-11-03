# LGBT VIOLENCE AND HARASSMENT IN EUROPE

## Description :

  Ce projet a pour but, avec l'aide de deux dahsboard (faits avec les langages Python et R), d'exposer les violences et harcèlements subits par la communauté LGBT (Lesbienne, Gay, Bisexuelle et Transgenre). De plus, il sera aussi question d'analyse et interprétations des graphes obtenus, débouchant sur une meilleure compréhension des possibles craintes et agressions subits par une communauté victime de dynamiques homophobes et/ou transphobes systémiques.
  
  Le travail s'appuie sur deux sondages auprès de LGBT volontaires en Europe, constituant nos jeux de données :
  
            - un concernant leur vie quotidienne, et un autre concernant les violences (sexuelles ou non) et harcèlements qu'ils peuvent subir (Pyhton -> Dash)
            - seulement le jeu de donné des violences et harcèlements subits (R -> Shiny)

## Données utilisées :

1/ "LGBT_Survey_DailyLife.csv" 

    Ce jeu brut de données est de taille 34021*6
    Les 6 variables sont :
            - Le pays (CountryCode) -> pays Européens
            - Le sous-groupe de la communoté LGBT (subset) -> Lesbienne, Gay, Femme Bisexuelle, etc...
            - Le code de la question (question_code)
            - La question écrite (question_label)
            - La réponse (answer)

2/ "LGBT_Survey_ViolenceAndHarassment.csv" (renommé "LGBT_Survey")
    
    Ce jeu brut de données est de taille 45356*6
    Les 6 variables sont les mêmes que pour le premier jeu de données

## Installation des packages R :

    Lignes de code : 
        
        install.packages("shiny")
        install.packages("dplyr")
        install.packages("geojsonio")
        install.packages("leaflet")
        install.packages("ggplot2")
        install.packages("shinythemes")

## Script :

Il suffira simplement d'ouvrir le fichier app.R avec RStudio et d'appuyer sur la touche "Run App" pour excécuter le fichier.

