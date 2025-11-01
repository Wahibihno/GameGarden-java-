1. Architecture et modifications principales
Le projet repose sur une architecture claire.
Elle suit les principes de la programmation orientée objet.

Packages principaux
Quatre packages structurent l’ensemble :

engine : moteur du jeu, logique principale
go : tous les objets présents dans le jeu
launcher : chargement et initialisation des niveaux
view : affichage graphique des éléments
Chaque élément du jeu hérite d’une classe mère commune : GameObject.
Cela simplifie le traitement global et unifie les comportements.
