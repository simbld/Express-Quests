# Express-Quests

💪 Challenge 1

Création de routes utilisateur
Ton défi consiste à :

Créer une route GET /api/users, cette route doit renvoyer un statut 200 et une liste d'utilisateurs de la base de données au format json
Créez une route GET /api/users/:id qui renverra uniquement l'utilisateur de la base de données correspondant à l'identifiant défini dans l'url
S'il y a un utilisateur qui correspond aux paramètres, renvoie une réponse avec un statut 200 et l'utilisateur correspondant en tant qu'objet json
Sinon, retourne un statut 404 avec un message "Not Found"
Publie une URL d'un dépôt GitHub avec ton application complète comme solution.

🧐 Critères de validation
 Le serveur fonctionne
 L'url /api/users affiche la liste des utilisateurs au format json
 L'url /api/users/2 affiche un utilisateur au format json
 L'url /api/users/0 affiche "Not found"

💪 Challenge 2

Insérer des utilisateurs dans la base de données
Maintenant que tu as créé la route POST pour les films, créons la route POST pour conserver les nouveaux utilisateurs.

Crée une route POST pour /api/users qui insérera un nouvel utilisateur dans la base de données
Publie un lien GitHub pour partager ta solution
🧐 Critères d'acceptation
 Le GitHub contient une route POST pour les utilisateurs
 Une requête POST sur /api/users devrait créer un nouvel utilisateur dans la base de données
