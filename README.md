Dans le cadre d'un projet de groupe, nous avons exploité des données environnementales (5 000 échantillons, 4 pays) pour comprendre les facteurs de dégradation de la qualité de l'air et construire un modèle de classification automatique.

🔍 Notre démarche :

Data Cleaning : Traitement robuste des valeurs aberrantes (imputation par la médiane) et standardisation des variables.

Analyse Exploratoire (EDA) : Étude des distributions, matrices de corrélation et boxplots pour visualiser l'impact des polluants.

Modélisation : Entraînement d'un modèle Random Forest (100 arbres) sur un jeu de données stratifié (80% train / 20% test).

Évaluation : Analyse des performances via l'accuracy, la précision, le rappel et la matrice de confusion.

💡 Les résultats clés :

Une performance élevée : Le modèle atteint une accuracy de 95,1 %, prouvant sa capacité à classer efficacement les niveaux de qualité de l'air.

Des facteurs d'alerte identifiés : L'importance des variables (feature importance) montre que le CO (Monoxyde de carbone) et la proximité industrielle sont les principaux marqueurs de la pollution.

Une utilité publique : Un tel système pourrait servir de base pour une surveillance automatisée ou un dispositif d'alerte précoce dans les zones à forte industrialisation.

Outils : Python | Pandas | Scikit-learn | Matplotlib / Seaborn
