# BrodeuseNum_2spi
*[english version](https://github.com/LucieMrc/EmbroideryMachine_sp33d)*

**Ou comment utiliser plus ou moins en autonomie la brodeuse numérique.**

Pré-requis : être à l'atelier numérique.

Le tissu : moins de 1mm d'épaisseur, attention si élastique ou trop fin.

## Attention

Si la machine s'arrête pendant la broderie en disant que le fil du bas ou du haut est cassé, mais que le fil n'apparaît pas cassé, merci de NE PAS RELANCER LA MACHINE directement. Il faut d'abord checker le dessous du tissu, et vérifier qu'il n'y a pas de noeuds de fils à l'envers du tissu.

Si il y a des noeuds, il faut les découper au maximum avec le découd-vite ou des ciseaux, voir virer tous les points qui ont des noeuds et reprendre la broderie depuis la dernière partie clean.

Si il n'y a pas de noeuds du tout, vérifier que la canette est bien placée, qu'il reste du fil dedans, et si tout est bon, on peux relancer la broderie.


## 1. Placer le tissu sur le cadre

Prendre la taille de cadre adaptée au motif choisi, le cadre par défaut est celui qui permet de broder en 10*10cm, et desserrer la vis.

![Premier cadre'](./images/img0_1.jpg)

Mettre le tissu dessus.

![Premier cadre'](./images/img0_2.jpg)

Poser par dessus la grande partie du cadre, et faire en sorte que le tissu se coince le plus droit et tendu possible en tirant sur la partie extérieur du tissu doucement.

![Premier cadre'](./images/img0_3.jpg)
![Premier cadre'](./images/img0_4.jpg)

Faire en sorte que les deux cadres soient bien calés l'un contre l'autre pour que le tissu soit bien tendu sur le dessous de la grande partie du cadre.

![Premier cadre'](./images/img0_5.jpg)
![Premier cadre'](./images/img0_6.jpg)

Resserrer la vis en gardant le tissu tendu au fur et à mesure.

![Premier cadre'](./images/img0_7.jpg)

## 2. Mettre le cadre dans la machine

Placer le cadre avec la partie tendue du tissu sur le dessous.

![Premier cadre'](./images/img0_8.jpg)

Faire glisser les bras du cadre sous les parties en métal des bras de la machine.

![Premier cadre'](./images/img0_9.jpg)

Pousser le cadre jusqu'à ce que les deux cotés soient enclenchés et que les boutons en métal sur la machine soient dans les trous des bras du cadre.

![Premier cadre'](./images/img0_11.jpg)
![Premier cadre'](./images/img0_13.jpg)

## 3. Ajouter un motif en USB

**Après avoir créé le motif en .pes**

Placer la clef USB dans la machine, sur le coté de l'interface.

![Premier cadre'](./images/img0_14.jpg)

Entrer dans le menu USB.

![Premier cadre'](./images/img0_15.jpg)

Sélectionner le motif à broder.

![Premier cadre'](./images/img0_16.jpg)

Cliquer sur `Régler` pour choisir la taille et la position.

![Premier cadre'](./images/img0_17.jpg)

Vérifier que le motif rentre dans le cadre en pointillé, le redimensionner avec le premier bouton à gauche carré, et le déplacer avec les boutons flèches à droite si besoin, puis cliquer sur `Broder`.

![Premier cadre'](./images/img0_18.jpg)

## 4. Lancer la broderie

Appuyer sur le bouton de verrouillage sur l'écran (rouge = verrouillé).

<!--//photo-->

Appuyer sur le bouton ⬆️ pour lancer la machine.

<!--//photo-->

Pour arrêter la broderie en cours, rappuyer sur le bouton ⬆️. 

# Si besoin

## A. Créer un motif .pes avec Inkscape et Ink/Stitch

Installer [Inkscape](https://inkscape.org) et l'extension [Ink/Stitch](https://inkstitch.org/fr/).

Ouvrir l'image (png, jpeg, svg) avec Inkscape.

Si l'image n'est pas un svg, passez par l'étape `Chemin` > `Vectoriser un objet matriciel`.

![Premier cadre'](./images/img3_1.png)

Cliquer `Appliquer` dans la fenêtre qui s'ouvre, puis ne garder que la forme vectorisée (supprimer l'image en dessous).

![Premier cadre'](./images/img3_2.png)

Sélectionner la forme vectorisée et aller dans `Extensions` > `Ink/Stitch` > `Paramètres`.

![Premier cadre'](./images/img3_3.png)

Modifier les réglages si besoin, et cliquer sur `Apply and quit`.

![Premier cadre'](./images/img3_4.png)

Avant d'exporter, on peux prévisualiser la broderie en allant dans `Extensions` > `Ink/Stitch` > `Visualiser et exporter` > `Simulateur/ Aperçu réaliste`.

![Premier cadre'](./images/img3_10.png)

Pour exporter en fichier .pes, simplement enregistrer le fichier.

![Premier cadre'](./images/img3_5.png)
![Premier cadre'](./images/img3_6.png)

Pour adapter la taille de l'image à la taille de la broderie, mettre la taille en haut en cm ou mm :

<!--Si besoin, le repasser par PE Design pour adapter la taille.-->

### Pour faire un motif avec plusieurs couleurs :

Importer un svg avec plusieurs couleurs dans Inkscape, et commencer par faire faisant `Chemin` > `Objet en chemin`.
Ensuite, faire la même manipulation que pour une couleur : `Extensions` > `Ink/Stitch` > `Paramètres`, modifier les réglages si besoin, et cliquer sur `Apply and quit`, puis enregistrer en .pes.

![Premier cadre'](./images/homographie.svg)
*Le svg*

![Premier cadre'](./images/img3_8.png)
*La prévisualisation de la broderie dans Inkstitch*

![Premier cadre'](./images/img3_9.jpg)
*La broderie : rendu pas terrible, le tissu a un maillage trop gros par rapport aux points du motif*

<!--## B. Créer un motif .pes avec le logiciel PE Design

Ouvrir le logiciel PE Design.

![Premier cadre'](./images/Capture1.png)

Aller dans l'onglet `Image` puis cliquer sur `Piqûre automatique` et sélectionner l'image choisie.

![Premier cadre'](./images/Capture2.png)

Rogner le motif si besoin, puis cliquer sur `Suivant` pour lancer le calcul de conversion de l'image en motif de broderie.

![Premier cadre'](./images/Capture4.png)

Après le premier calcul de conversion, on peux changer la sensibilité de la réduction des parasites et de la segmentation pour affiner le rendu. On peux également décider du nombre de couleur max (ici : 2, le tracé et le fond), puis décider de supprimer des couleurs en cliquant dessus dans la partie `Omettre les couleurs des parties`. Ici j'ai supprimé la couleur du fond, qui est barrée.

![Premier cadre'](./images/Capture6.png)

Redimensionner le motif afin qu'il rentre dans le cadre blanc.

![Premier cadre'](./images/Capture7.png)
![Premier cadre'](./images/Capture8.png)

Pour exporter, cliquer le logo du logiciel en haut à gauche, puis `Enregistrer sous...` .

![Premier cadre'](./images/Capture9.png)

Enregistrer en format .pes.

![Premier cadre'](./images/Capture10.png) -->

## B. Passer le fil

**Attention : la machine doit être éteinte !**

Mettre la bobine sur le premier bâton, et passer le fil dans le trou 1.

![passage du fil dans le premier trou'](./images/img1_1.jpg)

Passer ensuite le fil dans le trou 2, sur le dessus de la machine, et le faire passer dans le petit angle à coté de la petite molette

![passage du fil dans le second trou'](./images/img1_2.jpg)

En suivant le schéma, faire passer le fil autour de la molette de tension du fil, dans le sens des aiguilles d'une montre.

![passage du fil dans la molette'](./images/img1_3.jpg)

Passer le fil sous le morceau en métal de la seconde petite molette.

![passage du fil dans la dernière molette'](./images/img1_4.jpg)

Descendre le fil le long de la fente de droite, passer sous la partie 4 avec la flèche, et remonter dans la fente de gauche.

![passage du fil dans les fentes'](./images/img1_5.jpg)

Passer le fil de droite à gauche dans le trou 5, et redescendre la fente de gauche.

![passage du fil dans le trou devant'](./images/img1_6.jpg)

Passer le fil dans le trou 6 sur l'avant de la machine.

![passage du fil dans le dernier trou'](./images/img1_7.jpg)

Faire passer le fil dans le petit bras en métal à droite de l'aiguille, en tendant le fil le long de l'aiguille et en utilisant le petit outil pour le pousser derrière le bras.

![passage du fil à coté de l'aiguille'](./images/img1_8.jpg)

**Ici on allume la machine**

Pour faire passer le fil dans le chat de l'aiguille, appuyer sur le bouton `Passage du fil` tout à droite sur l'interface de la machine.

![passage du fil dans l'aiguille'](./images/img1_10.jpg)

Deux petits crochets se calent autour l'aiguille, il faut tenir le fil tendu sous les deux en rappuyant sur le bouton pour que les crochets viennent tirer le fil et passer le fil.

![passage du fil dans l'aiguille'](./images/img1_9.jpg)

Si un de ses étapes a été oublié ou fait dans le mauvais sens, le fil peux être trop ou pas assez tendu, ou se casser.

Pour changer de couleurs le fil, le plus simple est de sortir le fil du chat de l'aiguille, puis de couper en sortie de la bobine, nouer le fil qui passe dans la machine au fil de la nouvelle bobine, et tirer sur le fil pour le faire passer.

<!-- photo !!-->

## C. Remplir la canette

Récuperer la canette sous dans la petite trappe en dessous de l'aiguille.

![repérer la canette](./images/img3_0.jpg)

L'enlever en tirant sur la petite partie charnière.

![tirer dessus](./images/img3_01.jpg)

Enlever la canette de son réceptacle.

![repérer la canette](./images/img3_02.jpg)

Choisir le fil pour la bobine (ici le fil lila), et le passer dans les numéros qui sont dans un cercle.

![passage du fil en haut](./images/img3_1.jpg)

![passage du fil en haut](./images/img3_2.jpg)

![passage du fil en haut](./images/img3_3.jpg)

Faire quelques tours de fil autour de la canette vide, puis caler la canette sur l'axe sur le coté de la machine.

![photo de la canette avec des tours de fil](./images/img3_4.jpg)
![photo de l'axe](./images/img3_5.jpg)

Coincer le fil dans la petite fente sur le coté.

![photo du fil dans la rainure](./images/img3_6.jpg)

Rabattre le petit coude sur la canette.

![photo du petit coude rabattu](./images/img3_7.jpg)

Sur l'écran de la machine, le menu de la canette apparaît, cliquer sur "Démarrer". L'axe tourne jusqu'au remplissage de la canette.

![photo de l'écran de la machine](./images/img3_8.jpg)

Remettre le petit coude dans sa position de base, couper le fil et enlever la canette, et on peux la remettre dans la machine.

## D. Placer la canette

**Attention : la machine doit être éteinte !**

Placer la canette avec le fil qui tourne dans le sens horaire dans le recepteur à canette.

Faire sortir le fil sur 5cm, d'abord dans la petite fente du réceptacle.

![photo de l'écran de la machine](./images/img4_1.jpg)

Faire coulisser le fil, et le faire sortir par le trou le long de la fente.

![photo de l'écran de la machine](./images/img4_3.jpg)

Placer la canette dans son emplacement.

![photo de l'écran de la machine](./images/img4_4.jpg)

Pousser la canette dans son emplacement jusqu'au clic, et refermer.

![photo de l'écran de la machine](./images/img4_5.jpg)

![photo de l'écran de la machine](./images/img4_6.jpg)


## E. Tendre ou détendre le fil du dessus

Le fil du dessus est trop lâche si la broderie a l'air trop lâche, ou si il boucle et fait des noeuds en début de broderie (les boucles s'emmêlent > les noeuds cassent le fil > la brodeuse s'arrête)
Il est trop tendu si on voit trop le fil du dessous sur la broderie, ou il se casse pendant la broderie (la brodeuse s'arrête).

On peux tendre ou détendre le fil en tournant la petite molette en haut au dessus de la machine ainsi que la grosse molette de tension du fil juste en dessous de la petite molette en question.

Tendre le fil : sens des aiguilles d'une montre :

![Premier cadre'](./images/img2_1.jpg)

Détendre le fil : sens contraire des aiguilles d'une montre :

![Premier cadre'](./images/img2_2.jpg)

<!--//photo de broderies foirées-->

# Pour aller + loin

Le [manuel de la machine Brother de l'atelier](https://download.brother.com/welcome/doch100509/vr_dom01eu_fr.pdf).

Liste de [tutoriels de broderie machine](https://edutechwiki.unige.ch/fr/Catégorie:Guide_de_tutoriels_de_broderie_machine).

La BD [The Dancing Plague](https://www.selfmadehero.com/books/the-dancing-plague).