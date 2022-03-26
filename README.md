## Projet dashboard lecteur

Projet de création d'un dashboard via tablette pour l'affichage des informations moteur en direct pour remplacer l'instalation de manomettre.

#### Véhicule :
-   BMW serie 3 1995 convertible
-   code chassis E36
-   328I 
-   code Moteur M52B28 2.8L essence 6 cylindres simple vanos
-   DME (ECU) Siemens MS41


#### Communication DME

La communication avec le DME Siemens s'effectue via le protocole ISO 9141 via la broche K-line
Le modèle BMW E36 ne dispose pas d'une prise OBD2 d'origine une modification du faisceau d'origine est requis 

<p align="center">
<img src="./pictures/BMW_MS_41_1.jpg" ></p>

connecteur DME
-   88 => Blanc-violet = K-line
-   49 => Vert = +12V
-   60 => Vert-Bleu = +12V
-   28 => Marron-Orange = Masse
-   26 => Rouge = +12V



<p align="center">
<img src="./pictures/obdii-20-16-pinout1-2-2020-05-03T18_15_02Z.png" ></p>

connection prise OBD II
-   4-5 => Masse
-   7 => K-line
-   16 => +12V



### Schema DME X6000 DME control unit - Siemens MS41

<p align="center">
<img src="./pictures/images.png" ></p>

<p align="center">
<img src="./pictures/Screenshot_2022-03-26_23-11-00.jpg" ></p>
