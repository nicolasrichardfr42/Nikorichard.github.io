# Correctif connexion après ajout Z’amours

Le blocage venait de deux contrôles du modal Reset (`cancelReset` et `confirmReset`) référencés par JavaScript mais absents du HTML dans la dernière construction. L’exception arrêtait le script avant que la connexion puisse être utilisée correctement.

Cette version rétablit le modal Reset, conserve Z’amours + Jess/Nicolas + pré-réponses, et sécurise l’ancien rendu Blind Test. Aucun nouveau SQL n’est requis si l’installation Z’amours complète a déjà réussi.
