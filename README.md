Ce programme Python est conçu pour gérer les inscriptions des participants à une conférence internationale en utilisant la programmation orientée objet (POO). Les participants sont répartis en trois catégories — étudiants, professeurs et professionnels de l'industrie — ayant chacun des attributs spécifiques et des frais d'inscription qui varient selon la catégorie et la date d'inscription.

Le programme inclut :

Classes et Héritage :

Une classe parente Participant gère les informations générales des participants (comme le nom et le prénom).
Trois classes filles (Etudiant, Professeur, et Industriel) héritent de Participant et ajoutent des attributs spécifiques (comme le niveau d'étude pour les étudiants ou l'entreprise pour les professionnels de l'industrie).

Gestion de la Conférence :

La classe Conference gère la liste des participants et propose plusieurs fonctionnalités : ajout, modification, recherche, suppression de participants, et calcul des frais d'inscription.
Les frais d'inscription sont ajustés en fonction de la catégorie et de la date d'inscription du participant, encourageant ainsi les inscriptions anticipées.

Interface Basée sur un Menu :

Le programme propose un menu pour l'interaction utilisateur, permettant des actions telles que l'affichage du nombre total de participants ou le calcul des frais pour chaque participant.

Visualisation Statistique avec Matplotlib :

Un graphique à barres affiche le nombre de participants par catégorie, offrant une vue d'ensemble claire de la participation pour la planification de l'événement.
Ce programme démontre les principes fondamentaux de la POO, tels que l'héritage, l'encapsulation et la modularisation. Il propose également un exemple d'intégration de la visualisation des données avec matplotlib pour améliorer l'interprétation des données.
