# :rocket: Apprentissage en Data Science : Concepts Appris

Bienvenue dans mon projet de Data Science ! Ce dépôt présente les concepts que j'ai appris et appliqués, ainsi que mes erreurs et améliorations au fil du temps. Il permet de suivre mon évolution dans la manipulation de données et la construction de modèles prédictifs.

:book: **Le contenu du projet comprend** :
- Techniques de prétraitement des données
- Sélection des caractéristiques
- Analyse statistique
- Construction de pipelines
- Tests d'hypothèses

Voici les concepts clés que j'ai étudiés.

---

## Concepts Appris

### 1. **BA-BA Analyse (Exploratory Data Analysis - EDA)** :bar_chart:
   - **Objectif** : Comprendre et explorer les données avant de commencer à appliquer des modèles.
   - **Description** : L'EDA est une étape fondamentale pour analyser des données et en extraire des insights utiles. Cela inclut des visualisations, des statistiques descriptives, et l'identification de tendances et anomalies.
   - **Outils utilisés** : `pandas`, `matplotlib`, `seaborn`, `plotly`.

   ![Exploratory Data Analysis](https://media.giphy.com/media/l0HlNQ03J5JxX6lva/giphy.gif)

### 2. **Pipeline** :gear:
   - **Objectif** : Organiser et automatiser le processus de transformation des données et de modélisation.
   - **Description** : Un pipeline est une séquence d'étapes de prétraitement et de modélisation. Il aide à rendre les processus reproductibles et facilite le test de plusieurs modèles.
   - **Outils utilisés** : `sklearn.pipeline.Pipeline`, `FunctionTransformer`.

   ![Pipeline Animation](https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif)

### 3. **Preprocessing** :wrench:
   - **Objectif** : Préparer les données pour l'entraînement d'un modèle.
   - **Description** : Le prétraitement transforme et nettoie les données avant leur utilisation dans un modèle. Il inclut la normalisation, la mise à l'échelle des caractéristiques et le codage des variables catégorielles.
   - **Outils utilisés** : `StandardScaler`, `MinMaxScaler`, `OneHotEncoder`, `LabelEncoder`.

   ![Preprocessing](https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif)

### 4. **PolynomialFeatures** :bar_chart: ➗
   - **Objectif** : Gérer les relations non linéaires entre les caractéristiques.
   - **Description** : L'extension polynomiale des caractéristiques permet de créer de nouvelles variables d'interaction, ce qui améliore les performances des modèles linéaires.
   - **Outils utilisés** : `sklearn.preprocessing.PolynomialFeatures`.

   ![Polynomial Features](https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif)

### 5. **Feature Selection** :dart:
   - **Objectif** : Sélectionner les caractéristiques les plus pertinentes pour le modèle.
   - **Description** : La sélection de caractéristiques consiste à choisir les variables les plus importantes, réduisant le bruit et améliorant les performances du modèle.
   - **Outils utilisés** : `SelectKBest`, `RFE` (Recursive Feature Elimination), `FeatureImportances`.

   ![Feature Selection](https://media.giphy.com/media/3o7TKSjRrfIPjeiVyo/giphy.gif)

### 6. **Gestion des Outliers** :warning:
   - **Objectif** : Identifier et traiter les valeurs aberrantes dans les données.
   - **Description** : Les outliers peuvent fausser les résultats d'un modèle. Cette étape permet de les détecter et de les traiter à l'aide de méthodes comme l'IQR (Interquartile Range).
   - **Outils utilisés** : `IQR`, `Z-score`, `Quantile-based Flooring/Capping`.

   ![Outliers Detection](https://media.giphy.com/media/l0IylOPCNkiqOgMyA/giphy.gif)

### 7. **Gestion des NaN (Not a Number)** :x:
   - **Objectif** : Traiter les données manquantes pour éviter les erreurs lors de l'entraînement des modèles.
   - **Description** : Traiter les données manquantes par imputation ou suppression est crucial pour éviter que les modèles ne soient faussés.
   - **Outils utilisés** : `SimpleImputer`, `fillna`, `dropna`.

   ![Handling Missing Data](https://media.giphy.com/media/xT0xeJpnrWC4XWblEk/giphy.gif)

### 8. **Tests Statistiques** :mag_right:
   - **Objectif** : Effectuer des tests statistiques pour valider des hypothèses.
   - **Description** : Ces tests permettent de tirer des conclusions significatives à partir des données et de vérifier la validité des hypothèses.

   #### Types de tests :
   
   - **Test Binomial** : Utilisé pour déterminer si un échantillon suit une distribution binomiale.
   - **Test Chi-Carré** : Test l'indépendance entre deux variables catégorielles dans un tableau de contingence.
   - **Test Chi-Carré Convergent** : Variante du test Chi-Carré utilisée pour des données convergentes.
   - **Test de Student (t-test indépendant)** : Compare les moyennes de deux groupes indépendants.
   - **ANOVA (Analyse de la Variance)** : Teste si plusieurs groupes ont des moyennes statistiquement différentes.
   - **Corrélation de Pearson** : Mesure la force et la direction de la relation linéaire entre deux variables continues.
   
   - **Outils utilisés** : `scipy.stats`, `statsmodels`.

   ![Hypothesis Testing](https://media.giphy.com/media/DHqth0hVQoIzS/giphy.gif)

## Outils et Bibliothèques Utilisés
- **Python** : Langage de programmation utilisé pour le traitement des données et la création des modèles.
- **pandas** : Bibliothèque pour la manipulation et le nettoyage des données.
- **sklearn** : Bibliothèque pour l'apprentissage automatique, y compris le prétraitement et la création de pipelines.
- **matplotlib**, **seaborn**, **plotly** : Bibliothèques pour la visualisation des données.
- **numpy** : Bibliothèque pour les opérations mathématiques et la gestion des tableaux multidimensionnels.
- **scipy** : Bibliothèque pour les tests statistiques et l'analyse mathématique.
- **statsmodels** : Bibliothèque pour la modélisation statistique avancée et les tests.

## Conclusion :trophy:
Ce projet permet d'acquérir une solide compréhension des processus de traitement des données et d'application des modèles prédictifs. En appliquant ces concepts et outils, vous serez prêt à travailler avec des ensembles de données complexes et à construire des modèles d'apprentissage automatique de manière structurée.

🔗 **Suivez mon évolution !** Ce dépôt montre comment mes compétences en Data Science ont évolué à travers les erreurs rencontrées et les améliorations apportées. Retrouvez mes progrès en explorant les commits et les versions précédentes !

---

Ce **README.md** est conçu pour être une vitrine dynamique de mes compétences en Data Science, tout en incluant une touche d'animation pour rendre l'apprentissage plus engageant ! :sparkles:
