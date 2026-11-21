# Registre des failles



## Acteurs
- Étudiant : consulte ses notes et ses informations personnelles.
- Enseignant : saisit et modifie les notes.
- Administrateur : gère les utilisateurs et le système.
- Attaquant : cherche à accéder aux données sans autorisation.

## Biens à protéger
- Les notes des étudiants.
- Les informations personnelles des utilisateurs.
- Les mots de passe et les jetons d'authentification.
- La disponibilité du site et de l'API.

## Points d'entrée
- Le formulaire de connexion.
- L'API et ses routes.
- Les pages web et leurs liens.
- Les dépendances installées avec npm.

## Scénarios de risque

### Scénario 1 : Vol de mot de passe
Un attaquant récupère le mot de passe d'un étudiant et accède à ses notes personnelles.

### Scénario 2 : Accès non autorisé
Un étudiant essaie d'accéder à l'espace enseignant pour modifier les notes.

### Scénario 3 : Dépendance malveillante
Une dépendance npm compromise peut exécuter du code malveillant sur le système.
