# Correctif sélection Quiz

Le rafraîchissement automatique toutes les 2 secondes reconstruisait la liste de réponses. Tant que Supabase n’avait pas encore renvoyé `my_vote`, la sélection locale était remplacée par « Choisir... ».

Ce correctif :
- conserve la sélection locale pendant les rafraîchissements ;
- désactive temporairement le champ pendant l’enregistrement ;
- recharge le vote depuis Supabase juste après validation ;
- affiche `Vote enregistré : Prénom`.

Aucun SQL supplémentaire n’est nécessaire.
