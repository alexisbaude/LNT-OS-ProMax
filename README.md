# LNT-OS-ProMax
Le système d'exploitation de la LNT gratuit open source est paré pour réparer des pc arm64 et x86
Nous sommes fiers de vous le présenter : LNT OS ProMax (ou tout simplement LNT OS) .
C'est une version de Linux conçue à la base pour réparer des pc et mac (arm64 et x86)
Il fonctionne en bootant une clé usb sur le pc concerné puis il démarre en mode live cd (rien à installer )et supprime tous les fichier à la fin de la session.
Il est actuellement en test.
Il a été créé le 14/04/2025 et déployé le 16/04/2025
Vous pouvez le tester avec une image de moins de 1go sans les outils fonctionels +d'infos ici :https://github.com/alexisbaude/DEMO-LNT-OS
Les fiches d'aide utilisées lors du développement sont ici : https://drive.google.com/drive/folders/1yacYszdgbjaqtVcwnFAHmywGWpAMFSP0?usp=sharing
et aussi sur alexis.xbaude.fr

# LNT OS - Projet Système d'exploitation personnalisé

## Description
**LNT OS** est un système d'exploitation léger basé sur Linux, conçu pour les techniciens informatiques. Il inclut des outils de dépannage, une interface personnalisée, et un assistant vocal. L'objectif est de fournir un système rapide et pratique pour résoudre les problèmes informatiques.

## Fonctionnalités
- Mise à jour automatique des logiciels.
- Outils de dépannage préinstallés.
- Interface simplifiée pour les techniciens.
- Assistant vocal intégré.
- Configuration rapide avec un script d'installation.

## Installation

1. Clonez ce dépôt.
2. Exécutez le script d'installation `setup.sh` pour configurer le système et installer les dépendances.

### Commandes à exécuter :
```bash
git clone https://github.com/ton-utilisateur/LNT-OS.git
cd LNT-OS
./setup.sh
Documentation

Une documentation détaillée sur l’installation et l’utilisation se trouve dans le dossier docs/.

Contribuer

Si vous souhaitez contribuer, vous pouvez forker ce projet et soumettre une pull request. Voici quelques pistes pour contribuer :
	•	Ajouter de nouveaux outils de dépannage.
	•	Améliorer l’interface utilisateur.
	•	Corriger des bugs.

Licence

Ce projet est sous licence MIT.
