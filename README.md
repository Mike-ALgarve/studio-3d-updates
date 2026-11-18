# Studio 3D — Mises à jour Windows

Ce dépôt public contient uniquement les versions Windows signées de **Studio 3D** et les fichiers nécessaires aux mises à jour automatiques (`latest.yml`, `.blockmap`).

Le code source de Studio 3D reste dans le dépôt privé `Mike-ALgarve/studio-3d`.

## État

Le canal de publication sera activé après configuration du certificat de signature Windows et vérification de la première version signée. **Aucune version non signée ne doit être publiée ici.**

## Sécurité

- Ne jamais ajouter de code source, secrets, mots de passe ni certificats privés.
- Les versions sont publiées uniquement depuis la procédure GitHub Actions du dépôt privé.
- Les installateurs et mises à jour doivent porter une signature Authenticode valide.
- La toute première version signée doit être installée manuellement pour activer ensuite les mises à jour depuis l'application.
