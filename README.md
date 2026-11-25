# Correctif Quiz

Le Quiz était visible mais vide car l’ancien rendu du Blind test (`renderBlind`) tentait encore d’écrire dans l’ancienne zone `#songs`, supprimée lors de l’intégration du Blind Test Live. Cette erreur JavaScript interrompait `renderPlayer()` juste avant `renderQuiz()`.

Le correctif supprime cet appel obsolète. Aucun changement Supabase n’est nécessaire.
