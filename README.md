# Nuance-Research

Bibliothèque, recherche documentaire et rédaction scientifique. Le moteur et le modèle sont intégrés aux installateurs : aucun serveur sur le Mac du développeur, Python, Docker ou GPU n’est nécessaire chez l’utilisateur. Un compte Nuance avec un statut rédacteur, validateur ou administrateur approuvé est requis.

## Télécharger la bêta 0.30

| Ordinateur | Installateur |
|---|---|
| Mac Apple Silicon — macOS 14+ | [Télécharger pour Mac](https://github.com/pjeu-oss/nuance-research-downloads/releases/download/research-beta-0.30/Nuance-Research-Mac-arm64-Preview.pkg) |
| Windows x64 Intel/AMD | [Télécharger pour Windows](https://github.com/pjeu-oss/nuance-research-downloads/releases/download/research-beta-0.30/Nuance-Research-Windows-x64-Setup.exe) |
| Linux amd64 — Ubuntu 22.04+ / Debian 12+ | [Télécharger pour Linux](https://github.com/pjeu-oss/nuance-research-downloads/releases/download/research-beta-0.30/Nuance-Research-Linux-amd64.deb) |

[Notes, empreintes SHA-256, captures et rapports de vérification](https://github.com/pjeu-oss/nuance-research-downloads/releases/tag/research-beta-0.30). Les Mac Intel et les plateformes ARM Windows/Linux ne sont pas couverts par ces paquets.

Enregistrer son travail, quitter Research, puis ouvrir l’installateur téléchargé. Conserver une sauvegarde séparée de sa bibliothèque. Sur Linux, ouvrir le fichier avec le gestionnaire de logiciels ou utiliser `sudo apt install ./Nuance-Research-Linux-amd64.deb`. L’interface Linux s’ouvre dans le navigateur du poste ; fermer l’onglet ne quitte pas le moteur : utiliser l’action **Quit local engine** du lanceur.

Internet est nécessaire pour l’authentification Nuance et les services documentaires externes. Les documents personnels ne sont pas inclus dans les paquets et restent dans le dossier de données du compte local.

## Vérifications et limites

La 0.30 aligne l’interface et le moteur sur le même instantané, sécurise la livraison des styles indépendamment des associations Windows et teste les vrais paquets. Les contrôles graphiques du portail couvrent les couleurs, les thèmes clair/sombre, la langue et la fermeture des menus. Le contraste élevé du système reste respecté. Les rapports précisent la portée exacte ; ils ne remplacent pas tous les essais sur des portables et comptes réels.

Bêta : installateur Windows sans signature éditeur ; Mac avec signature ad-hoc vérifiée, sans Developer ID ni notarisation. Un avertissement du système peut apparaître. Aucun installateur ne peut être garanti sans défaut sur toutes les machines.

Ce dépôt public distribue uniquement les installateurs et leurs rapports. Le code courant est conservé séparément dans un dépôt privé.
