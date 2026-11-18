# Studio 3D — versions Windows personnelles

Ce dépôt public sert uniquement à publier les **installateurs Windows non signés** de Studio 3D et leurs manifestes `studio3d-update.json`. Le code source du logiciel reste privé dans `Mike-ALgarve/studio-3d`.

## Fonctionnement

Chaque publication officielle contient :

- `Studio3D-Setup-X.Y.Z.exe` : installateur Windows 64 bits.
- `studio3d-update.json` : version, nom, taille et empreinte SHA-256 de l'installateur.

Studio 3D V0.1.2 (et versions suivantes) peut détecter les nouvelles publications, télécharger le fichier via HTTPS, vérifier l'empreinte SHA-256 et demander une confirmation avant l'ouverture de l'installateur.

**Important :** pas de certificat Windows payant. Ces fichiers ne sont pas signés ; Windows peut afficher un avertissement SmartScreen. La vérification SHA-256 protège contre les corruptions, pas contre la compromission du dépôt de publication.

## Publication

Utiliser exclusivement le workflow GitHub Actions **Publier Studio 3D Windows (usage personnel)** du dépôt privé. Ne jamais ajouter du code source, des clés d'accès ou des certificats privés ici.
