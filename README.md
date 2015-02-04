# 8GIF128--Generateur_de_graphe
Premier Service pour le projet 8GIF128
Le premier service est un programme permettant de générer un graphe aléatoire. Un graphe est généralement décrit à l'aide d'une liste d'arêtes. Un algorithme peut ensuite lire la liste des arêtes et créer le graphe dans ses structures de données internes.
Pour les problèmes de graphes de ce projet, les graphes ne sont pas des graphes dirigés, ce qui veut dire que les arêtes vont dans les deux directions. Le terme utilisé est undirected graph1
Ce premier service est donc essentiel au fonctionnement des autres services. Quelques demandes :
 Lorsque l'usager utilise le service de générateur de graphes, il doit entrer le nombre de sommets du graphe et la densité de ce graphe. La densité est un nombre entier entre 0 et 100. Un densité de 50 signifie tout simplement qu'il y a une chance de 50 pourcent qu'il y ait une arête entre le sommet a et b
 Le générateur de graphe doit s'assurer que le graphe est connecté et qu'il n'y ait qu'une seule arête par paire de sommets.
 Un graphe connecté signifie que tous les sommets ont au moins un chemin vers les autres sommets.
Voici un exemple de format de description de graphe simple. La première ligne contient deux valeurs entières : le nombre de sommets (n) et le nombre d’arêtes (m). Les m lignes suivantes décrivent les arêtes de la façon suivante : sommet1 sommet2 poids. Vous pouvez néanmoins employer un format différent ou alors utiliser JSON ou XML.
￼￼￼￼69 04 3 01 1 0 3 10 13 3 12 2 23 4 25 5
￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼1 http://en.wikipedia.org/wiki/Graph_%28mathematics%29#Undirected_graph
