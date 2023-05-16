# 2022_2023_4G_Kerleau_Cassagne
Projet Capteur 4GP

## 1. Présentation du projet
### 1.1 Cadre du projet 

Ce projet de réalisation d’un capteur se basant sur une technologie low tech nous a été proposé dans le cadre du cours intitulé “du capteur au banc de test en open source hardware” que nous avons suivi lors de notre 2ème année de cycle ingénieur à l’INSA Toulouse au sein du département Génie Physique. 

Afin de récupérer les données de déformation à partir du capteur, nous avons utilisé une carte Arduino UNO. L’affichage des données se fait d’une part sur un écran OLED, et de l’autre sur un ordinateur via une interface python. Cette dernière reçoit des valeurs de déformation par une communication série établie entre l’ordinateur et la Arduino. De plus, un encodeur rotatoire permet de sélectionner les données que l’on souhaite afficher sur l’écran OLED (courbe représentant la déformation en fonction du temps, valeur de la déformation, la résistance du capteur mesurée). Enfin, nous avons ajouté un flex sensor, permettant la comparaison des données de notre capteur graphite. 

### 1.2 Principe physique

La technologie low-tech utilisée ici consiste en des traces de crayon réalisées sur un papier. Ces dernières peuvent alors servir de jauge de détection de compression et d’extension. 

Lors de la friction entre le papier et la mine de crayon, des particules de graphite restent accrochées aux fibres du papier, organisées sous forme d’un fin réseau granulaire conducteur. Lors de la contraction ou de l’extension du capteur et donc du réseau de particules de graphite, les intéractions inter-moléculaires de contact sont modifiées. En résulte une modification de la conductivité électrique globale. C’est cette variation de conductivité et donc de résistance que nous mesurons, nous donnant par un simple calcul la valeur de la déformation. Cela offre ainsi la possibilité de réaliser des capteurs de façon rapide et avec des matériaux facilement accessibles.


### 1.3 Livrables 

#### 1.3.1 Livrables initiaux

- PCB supportant le capteur graphite, l’écran OLED, l'émetteur bluetooth, l’encodeur rotatoir, le flex sensor.
- Code Arduino 
- Banc de test
- Datasheet
- Application Android récupérant les données du capteur bluetooth 

#### 1.3.2 Rectification des livrables 

Ne disposant pas d’appareil Android mais ayant quand même pour objectif de transmettre les données afin de réaliser une interface graphique, nous nous sommes tournés vers la réalisation d’une interface python. Cette dernière récupère les données de la Arduino via une communication série et permet d’afficher la courbe représentant la valeur de la déformation au cours du temps ainsi que la valeur de la déformation.

## 2. Matériel nécessaire

Pour utiliser le capteur graphite, sont nécessaires : 
Une arduino 
Un capteur grpaphite
2 pinces crocodile 
(matériel AOP) 
Logiciel : Arduino, Python 

## 3. Arduino 

Pour traiter l’information nous utilisation un microcontrôlleur Arduino UNO

### 3.1 Librairies 

Nous nous sommes servis de différentes librairies telles que les librairies de l’OLED et de l’encodeur rotatoire

### 3.2 Code 

Le code complet est disponible ici. Il gère le calibrage du capteur, l’affichage de différentes données sur l’écran OLED, la gestion de choix sur l’OLED à l’aide d’un encodeur rotatoire et enfin un envoi des données en série pour les récupérer via Python

## 4.Python

### 4.1 Librairies 

_exemples :_
* [Materialize.css](http://materializecss.com) - Framework CSS (front-end)
* [Atom](https://atom.io/) - Editeur de textes
* 

Nous nous sommes servis de différentes librairies telles que les librairies de l’OLED et de l’encodeur rotatoire

### 4.2 Code 

## 5. KiCad

Nous avons utilisé le logiciel KiCad afin de pouvoir réaliser notre PCB, pour cela nous avons dans un premier temps fait la schématique de notre montage, puis nous avons défini les empreintes de nos différents composants pour ensuite pouvoir les disposer de façon optimale sur notre PCB

### 5.1 Schématique 
### 5.2 empreintes
### 5.3 Composants

## 6. Shield 
### 6.1 PCB
### 6.2 Perçage et soudure

## 7. Simu Spice 

## 8. Tests
### 8.1 Objectifs
### 8.2 banc de test
### 8.3 résultats 
### 8.4 analyse 
### 8.5 amélioration

# 9. Datasheet

# 10. Contacts & remerciements 





