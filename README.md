# premier-modele-IA
## Table des matières
1. [Infos générales]
2. [Regression linéaire simple sur le dataset reg_simple.csv **sans Sklearn**]
3. [Regression linéaire multiple sur le dataset boston_house_prices.csv **sans sklearn**]
4. [Regression linéaire polynomiale sur les datasets Position_Salaire.csv et qualite_vin_rouge.csv **sans Sklearn**]
5. [Regression linéaire simple sur le dataset reg_simple.csv avec **Sklearn**]
6. [Regression linéaire multiple sur le dataset boston_house_prices.csv avec **sklearn**]
7. [Regression linéaire polynomiale sur les datasets Position_Salaire.csv et qualite_vin_rouge.csv avec **Sklearn**]
## Infos générales
Pour ce brief, nous allons faire des regressions linéaires simples, multiples et polynomiales sur différents datasets avec et sans Scikit-learn (bibliothèque Python destinée à l’apprentissage automatique. Construite sur les bases de NumPy, SciPy et matplotlib).
- Le jupyter notebook ModeleIA correspond au Jupyter Notebook où nous faisons les régressions linéaires sans scikit-learn.
- Le jupyter notebook MIA_ScikitLearn correspond au Jupyter Notebook où nous faisons les régressions linéaires avec scikit-learn.
## Regression linéaire simple sur le dataset reg_simple.csv sans Sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairesimple.png) 

> Résultat de la régression linéaire simple à partir du dataset "reg_simple" (aucun souci).
## Regression linéaire multiple sur le dataset boston_house_prices.csv sans sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairemultiple1.png)

> Résultat de la régression linéaire multiple à partir du dataset "boston_house_prices" avec comme variables "DIS" et "AGE", et "MEDV" comme target.

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairemultiple2.png)

> Résultat de la régression linéaire multiple à partir du dataset "boston_house_prices" avec comme variables "DIV" et "NOX", et "MEDV" comme target.
## Regression linéaire polynomiale sur les datasets Position_Salaire.csv et qualite_vin_rouge.csv sans Sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomiale1.png)

> Résultat de la régression linéaire polynomiale à partir du dataset "Position_Salaire".

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomiale2.png)

> Résultat de la régression linéaire polynomiale à partir du dataset "Position_Salaire" où l'on compare la régression linéaire polynomiale de base et celle qui est prédite.

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomiale3.png)

> Résultat de la régression linéaire polynomiale à partir du dataset "qualite_vin_rouge". On remarque ici que faire une régression linéaire polynomiale sur ce dataset est impossible et ne donne pas de résultat probant. 
## Regression linéaire simple sur le dataset reg_simple.csv avec Sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairesimplesklearn1.png)

> Résultat de la régression linéaire simple (échantillon d'entraînement) effectuée avec Sklearn à partir du dataset "reg_simple".

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairesimplesklearn2.png)

> Résultat de la régression linéaire simple (échantillon de test) effectuée avec Sklearn à partir du dataset "reg_simple".
## Regression linéaire multiple sur le dataset boston_house_prices.csv avec sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairemultiplesklearn2.png)

> Résultat de la régression linéaire simple (échantillon d'entraînement) effectuée avec Sklearn à partir du dataset "boston_house_prices".

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairemultiplesklearn1.png)

> Résultat de la régression linéaire simple (échantillon de test) effectuée avec Sklearn à partir du dataset "boston_house_prices".
## Regression linéaire polynomiale sur les datasets Position_Salaire.csv et qualite_vin_rouge.csv avec Sklearn
![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomialesklearndeg1.png)

> Résultat de la régression linéaire polynomiale de premier degré effectuée avec Sklearn à partir du dataset "Position_Salaire". La courbe de la prédiction (en bleu) ne correspond pas du tout à la courbe du jeu de données (en orange).

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomialesklearndeg3.png)

> Résultat de la régression linéaire polynomiale de troisième degré effectuée avec Sklearn à partir du dataset "Position_Salaire". La courbe de la prédiction (en bleu) correspond un peu mieux à la courbe du jeu de données (en orange).

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomialesklearndeg5.png)

> Résultat de la régression linéaire polynomiale de cinquième degré effectuée avec Sklearn à partir du dataset "Position_Salaire". On voit ici que le 5ème degré correspond parfaitement à ce que l'on souhaitait. La courbe de la prédiction (en bleu) correspond à la courbe du jeu de données (en orange). 

![alt text](https://github.com/PaulineSanchez/premier-mod-le-IA/blob/main/reglineairepolynomialesklearnvin.png)

> Résultat de la régression linéaire polynomiale effectuée avec Sklearn à partir du dataset "qualite_vin_rouge". On remarque qu'avec Scikit-learn la régression linéaire polynomiale n'est toujours pas possible. 
