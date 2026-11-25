# Correctif Blind Test Live

Le bouton **Lancer le morceau** est corrigé. La variable de connexion Supabase nommée `URL` masquait l’API native `window.URL.createObjectURL()` utilisée pour lire le fichier audio local.

Remplacez les fichiers GitHub Pages par ceux de cette archive. Aucun nouveau SQL Supabase n’est nécessaire.

Test : connecter Nicolas / 2027, sélectionner un fichier audio sur la ligne 1, choisir le morceau 1 dans la régie puis cliquer sur Lancer le morceau.
