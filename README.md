# initiation_recherche

doi = numéro d'article universel de l'article

4 pages d'articles scientifiques à rédiger, 
à partir de 10 pages d'articles scientifiques existants 

................................................................

Sujet 1 : Livre blanc blockchains et développement durable : 

Sujet 2 : Classification de signaux audio en temps-réel : -> sujet retenu

................................................................

-> Sujet : 
Reconnaissance de l'espèce (faune et flore) en milieu forestier, 
sur des espaces de chasse, à des fins de sauvegarde.

Existant : 
- Gardes forestiers : 
    -> inconvénients : 
        . limites en ressources humaines
        . erreur humaine (lenteur, subjectivité des sens)

- Détecteurs de mouvements laser :
    -> inconvénients : 
        . balisage important de la zone à sécuriser avec de nombreux détecteurs, 
            en plus des grillages et des caméras (coût)
        . limites en termes de précision du dispositif : 
            impossibilité de réaliser une classification par espèce

- Computer vision + détecteur infrarouge
    -> inconvénients : 
        . difficile à mettre en oeuvre en milieu forestier
        . difficile de coupler la CV et la détection infrarouge dans un seul et même algo
        . infrarouge : limites en termes de précision du dispositif : 
            difficulté à réaliser une classification par espèce

Notre solution : 
classification des signaux audios émis par les espèces, 
d'après l'étude des spectres de fréquences, à l'intérieur d'un périmètre circonscrit
que l'on veut sécuriser.

-> Classification d'un spectre de signal machine learning
-> Classification des signaux audios émis en temps réel

Bonus : 
+ computer vision (classification d'images)
+ détecteur de température (filtres de Kalman), à l'intérieur d'un périmètre circonscrit
que l'on veut sécuriser.
+ détecteur de mouvement externe au périmètre circonscrit que l'on veut sécuriser.

