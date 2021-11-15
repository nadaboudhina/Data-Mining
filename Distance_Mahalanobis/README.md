la distance de Mahalanobis est une mesure de distance mathématique introduite par Prasanta Chandra Mahalanobis en 19361. 
Elle est basée sur la corrélation entre des variables par lesquelles différents modèles peuvent être identifiés et analysés.
C'est une manière utile de déterminer la similarité entre une série de données connues et inconnues.
Elle diffère de la distance euclidienne par le fait qu'elle prend en compte la variance et la corrélation de la série de données. Ainsi, à la différence de la distance euclidienne où toutes les composantes des vecteurs sont traitées indépendamment et de la même façon, la distance de Mahalanobis accorde un poids moins important aux composantes les plus dispersées. Dans le cas de l'analyse des signaux, et en supposant que chaque composante soit une variable aléatoire de type gaussien, cela revient à minimiser l'influence des composantes les plus bruitées (celles ayant la plus grande variance).

La distance de Mahalanobis est souvent utilisée pour la détection de données aberrantes dans un jeu de données, ou bien pour déterminer la cohérence de données fournies par un capteur par exemple : cette distance est calculée entre les données reçues et celles prédites par un modèle.

En pratique, la distance de Mahalanobis d'un vecteur à plusieurs variables { \displaystyle x=(x_{1},x_{2},x_{3},\dots ,x_{p})^{T}}x=(x_{1},x_{2},x_{3},\dots ,x_{p})^{T} à un ensemble de vecteurs de valeurs moyennes {\displaystyle \mu =(\mu _{1},\mu _{2},\mu _{3},\dots ,\mu _{p})^{T}}\mu =(\mu _{1},\mu _{2},\mu _{3},\dots ,\mu _{p})^{T} et possédant une matrice de covariance Σ est définie comme suit :

{\displaystyle D_{M}(x)={\sqrt {(x-\mu )^{T}\Sigma ^{-1}(x-\mu )}}.,}D_{M}(x)={\sqrt {(x-\mu )^{T}\Sigma ^{{-1}}(x-\mu )}}., La distance de Mahalanobis peut aussi être définie comme étant la mesure de dissimilarité entre deux vecteurs aléatoires {\displaystyle {\vec {x}}}{\vec {x}} et {\displaystyle {\vec {y}}}{\vec {y}} de même distribution avec une matrice de covariance Σ :{\displaystyle d({\vec {x}},{\vec {y}})={\sqrt {({\vec {x}}-{\vec {y}})^{T}\Sigma ^{-1}({\vec {x}}-{\vec {y}})}}.,}d({\vec {x}}, {\vec {y}})={\sqrt {({\vec {x}}-{\vec {y}})^{T}\Sigma ^{{-1}}({\vec {x}}-{\vec {y}})}}., Si la matrice de covariance est la matrice identité, cette distance est simplement la distance euclidienne. Si la matrice de covariance est diagonale, on obtient la distance euclidienne normalisée :

{\displaystyle d({\vec {x}},{\vec {y}})={\sqrt {\sum {i=1}^{p}{(x{i}-y_{i})^{2} \over \sigma {i}^{2}}}}}d({\vec {x}}, {\vec {y}})={\sqrt {\sum {{i=1}}^{p}{(x{i}-y{i})^{2} \over \sigma _{i}^{2}}}} où σi est l'écart type de xi sur la série de données.

Cette distance est souvent utilisée en analyse des données.
