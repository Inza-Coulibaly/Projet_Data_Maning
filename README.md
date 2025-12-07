# Analyse de la croissance des enfants — Projet Science des Données
## Parcours : Exploration & Modélisation Statistique
## Auteur : Dosse Inza COULIBALY

# Résumé
Ce projet analyse les trajectoires de croissance (taille, poids, IMC) d'une cohorte d'enfants (1–18 ans) à partir d'un jeu de données longitudinal. Après nettoyage et harmonisation (interpolation spline), l'étude compare profils filles/garçons, teste 6 méthodes de classification supervisée et retient le meilleur modèle (KNN) pour produire une liste d'enfants à surveiller (IMC extrême et discordance morphologique).

# Objectifs

Prétraitement et harmonisation des trajectoires
Analyse descriptive et tests statistiques par âge
Comparaison de modèles supervisés (Arbre, LDA, QDA, KNN, Bayes, Régression logistique)
Détection d'anomalies (IMC et discordance prédite)
Produire une vitrine reproductible pour démontrer compétences en data science

# Contenu du dépôt

data/ : croissance.csv (jeu de données, échantillon ou instructions de téléchargement)
notebooks/ : code.Rmd (analyse complète, RMarkdown)
reports/ : Projet_Data_Mining.pdf 
Dashboard: Tableau de bord_SAE_Data_mining.pbix ( outils automatisé qui analyse la courbe de croissance)
Meilleur modèle : KNN.
Nombre d'enfants analysés : 9 184 (125 933 mesures)
Enfants identifiés à surveiller (IMC ou discordance) : On a  environ 81100 enfants pour lesquels il faut vérifier s'ils ne sont pas malades ou pas
