# I-Présentation et objectif du projet
## Mini-projet-I : Analyse des sentiments pour les critiques des films

## Participants
OMOUALA André Kevin(OMOA15099900)
BOCOUM Aoua(BOCA65570200)
Agossou Fulbert(AGOF722040000)

## Objectif du Mini-Projet-I
Dans ce projet, on va devoir créer un système d'analayse des sentiments
qui sera capable de donner les avis ainsi que les critiques des films 
qui sont contenue dans le fichier IMDB. Notre système va devoir être 
capable de donner un avis "Positif" ou "Négatif"

## Tâches spécifiques à réaliser
(1)-Préparation des données
(2)-Prétraitement du texte
(3)-Extraction de caractéristique
(4)-Formation des modéles
(5)-Évaluation du modèle
(6)-Optimisation des hyperparamètres
(7)-Analyse de la courbe d'apprentissage
(8)-Analyse de l'empreinte carbone avec CodeCarbon
(9)-Considérations éthiques et explicabilité
(10)-Considération relatives au déploiement des systèmes embarqués

# II- Instruction pour le téléchargement et le prétraitement des données
Pour ce projet, il faudrait tout d'abord commencer par vérifier si on a
instaler nos bibliothèques dans notre Anaconda ces bliothèques sont : 
`pip install pandas`
`pip install numpy`
`pip install scikit-learn`
`pip install matplotlib`
`pip install seaborn`
`pip install nltk`
`pip install codecarbon`
`pip install shap`
Une fois les bibliothèques installer et vérifier, on va par la suite procéder
au téléchargement du fichier IMBD directement sur le site indiquer: 
[Large Movie Review Dataset] [https://ai.stanford.edu/%7Eamaas/data/sentiment/]
il faut que l'utilisateur qui veut réaliser ce projet se rassure 
que ce fichier soit placer au bonne endroit. Par la suite
concernant le prétraitement de données on aura : 

-le Nettoyage de texte(suppression des balises, conversion en minuscules, suppression de la ponctuation et des caractères spéciaux, ainsi que la suppression)
-la tokenization(on parle la de la division du texte en mots individuels)
-Suppression des stopwords
-Steming(on parle là de la réduction des mots)
-Vectorization(on parle de TF-IDF)


# III- Étapes de formation et d'évaluation 
Dans cet partie on va voir ce qui suit 

1-la division des données(il s'agit de séparer le dataset en ensemble d'entrainement)
2-formation des modéles(on parle des modéles classiques comme des modéles avancés)
3-l'évaluation(qui comprends les matrices de confusion, F1-Score, etc...)

## IV- Résultats de l'analyse de l'empreinte carbone
Dans notre Anaconda on déjà télécharger la bibliothèques adéquates. 
Son utilisation va nous permettre de mesurer l'impact énergetique
"from codecarbon import EmissionsTracker"

## V- Considérations éthiques et méthodes d'explicabilité
Ici il s'agit de respecter la vie privée des utilisateurs et de faire la prévention
des biais qui sont liés au genre, a la race ou à d'autres caractéristiques
pour mieux comprendre l'explicabilité on doit utiliser la bibliothèques
"import shap"

## VI- Aperçu du déploiement des sytèmes embarqués
On va faire la conversion du modèle qui sera comptabible avec un microcontrôleurs(Arduino)
en prenant en compte certaines contraintes du Arduino qui sont la limite de 
mémoire et tout ce qui l'entoure

## VII- Responsabilités liées à la publication du code :
7-1 Responsabiltés
-Garder un code propre, clair et qui fonctionne bien.
-Vérifie qu'il n'y a pas de données sensibles.
-être vigilant sur la reproductibilité des résultats.

7-2 Licences open source
-MIT License
-Cette license est utilisé parce que elle permet a d'autres : 
->De réutiliser le code
->De modifier le code

7-3 Pratique de publication
-A travers le dépôt public
-A travers la documentation

7-4 Protocole de signalement et correction des bogues
-Signaler un bug
-Créer une branche pour la correction Soumettre une pull request
-Mettre a jour la documentation 
-modifier la communauté des corrections majeures








