# AMAPF
Solving Anonymous Multi Agent Path Finding using Network Flow.
Description des fichiers:

**********time_expand***********
Input: graphe NetworkX, et d'un horizon de temps T 
Output: 
#créer le graphe étendu dans le temps pour T 
TimeExpand.edges: retourne toutes les arêtes du graphe temporel 
TimeExpand.init_edges: retourne les arêtes pour T=1 (nécessaire pour les update)


**********min_time***********
Input: graphe NetworkX, Positions de départ, positions d'arrivée
Output:
# Retourne les chemins qui minimise le temps d'arrivée du dernier agent (makespan)
MinTime.opt_time: retourne le makespan
MinTime.t_borne: retourne les bornes de T (bornes Yu LaValle)
MinTime.paths: retourne les chemins des agents (liste de positions à chaque instance de temps)
MinTime.cost: retourne le temps total d'arrivée (somme des temps individuels)


