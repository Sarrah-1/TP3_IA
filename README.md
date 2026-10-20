Salut, je suis OUADAY sara, étudiante en master TEE.

Ce projet est mon TP3 de NLP (Natural Language Processing). J'y ai appris à transformer un texte en vecteurs, puis à entraîner des modèles pour décider si un tweet est positif ou négatif.

## Ce que j'ai fait
Données : tweets sur le coronavirus, regroupés en 2 classes (positive et negative), les tweets neutres sont supprimés
Nettoyage : minuscules, suppression des liens, mentions et ponctuation
Tokenisation et stopwords : découpage du texte en mots et suppression des mots vides
Lemmatisation : retour des mots à leur forme de base
Vectorisation : TF-IDF pour transformer les mots en chiffres
Séparation : 80 % pour l'entraînement et 20 % pour le test
Modèles : SVM, Decision Tree, Random Forest, Naive Bayes et Logistic Regression
Validation croisée : 5-fold sur l'ensemble d'entraînement pour comparer les modèles
Évaluation : accuracy, F1-score et matrice de confusion sur l'ensemble de test

## Outils utilisés
Python, Jupyter Notebook, NLTK, scikit-learn, pandas, matplotlib, seaborn

## Fichier principal
tp3_classification_binaire.ipynb : le notebook avec le code et les résultats.

## Pour le lancer
pip install nltk scikit-learn pandas matplotlib seaborn
jupyter notebook
(mettre Scrapped_sentimental_data.csv dans le même dossier que le notebook)
<img width="490" height="323" alt="image" src="https://github.com/user-attachments/assets/9b9cb24c-9793-4658-b627-34f078d963b2" />
<img width="621" height="310" alt="image" src="https://github.com/user-attachments/assets/927532a8-a1ff-4ae1-b65c-6676ac2bb95c" />
<img width="428" height="142" alt="image" src="https://github.com/user-attachments/assets/82da0f47-3d82-426f-9f16-0b7ae865f58e" />
<img width="419" height="299" alt="image" src="https://github.com/user-attachments/assets/76384089-5568-49a4-95d9-b1996c8f4d98" />

