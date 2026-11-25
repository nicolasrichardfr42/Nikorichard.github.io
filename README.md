# Correctif mobile v13

Cette version corrige une panne de parsing JavaScript sur certains navigateurs mobiles :
- suppression de toutes les syntaxes `?.` et `??` ;
- suppression du gestionnaire global qui affichait `Script error` pour des erreurs externes ;
- erreurs de connexion toujours affichées directement par le bouton Entrer ;
- ajout du marqueur `version mobile 13` en bas de page.

Aucun SQL supplémentaire n’est nécessaire.
