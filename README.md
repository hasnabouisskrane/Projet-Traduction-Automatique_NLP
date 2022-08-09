# Projet-Traduction-Automatique_NLP

La traduction automatique peut se définir comme la mise en place de solutions visant à traduire un texte d’une langue à une autre en utilisant des outils qui ne font pas appel directement à des linguistes ou des traducteurs professionnels. Il s’agit donc de mettre en place des algorithmes qui nous permettront de réaliser des traductions sans intervention humaine.
Le projet inclut les étapes suivantes:
1) Ensemble de données de traduction 
2) Préparation des données textuelles
3) Former le modèle de traduction neuronale
4) Évaluer le modèle de traduction neuronale
ETAPE 1: Ensemble de données de traduction 

![image](https://user-images.githubusercontent.com/61788817/183774783-f9b43da4-da99-424a-ab0e-7f4a56e9fd16.png)

ETAPE 2: Préparation des données textuelles

Suppression des signes de ponctuation des données.
Conversion de corpus de texte en caractères minuscules.
Mélanger les phrases comme les phrases étaient auparavant triées dans l'ordre croissant de leur longueur.

ETAPE 3: Former le modèle de traduction neuronale

A. Word embedding 
Word embedding est une représentation  de mot qui convertit les données textuelles en données numérique d’une certain forme. Aussi il permet à des mots ayant une signification similaire d’avoir une représentation similaire.

![image](https://user-images.githubusercontent.com/61788817/183775147-dd6eb94d-5090-4733-9691-54d610371c34.png)


B. Encodeur-décodeur LSTM

L'encodeur-décodeur LSTM est un réseau neuronal récurrent conçu pour résoudre les problèmes de séquence à séquence, parfois appelés seq2seq. Aussi il permet au modèle d'être utilisé à la fois pour prendre en charge des séquences d'entrée de longueur variable et pour prédire ou sortir des séquences de sortie de longueur variable.

![image](https://user-images.githubusercontent.com/61788817/183775214-5f650409-21c1-4e9d-9b56-7ce467711322.png)

C. Former un modèle

![image](https://user-images.githubusercontent.com/61788817/183775278-8045ed65-ddbe-4f04-a0a0-0c10f502a356.png)

ETAPE 4: Évaluer le modèle de traduction neuronale

BLEU score est un algorithme permettant de comparer le texte prédit traduit par machine avec la chaîne de référence donnée par l'humain. 












