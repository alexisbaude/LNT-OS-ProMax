# Guide d'installation de LNT OS

## Prérequis

Avant d'installer **LNT OS**, vous devez avoir :
- Une machine (physique ou virtuelle) avec une version récente de Linux (Ubuntu ou Debian recommandés).
- Un accès Internet pour installer les dépendances.
- Une clé USB (si vous voulez créer une version Live USB).

## Étapes d'installation

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/ton-utilisateur/LNT-OS.git
    cd LNT-OS
    ```

2. Exécutez le script d'installation :
    ```bash
    ./setup.sh
    ```

3. Le script va installer les outils et configurer le système pour vous. Il est important de suivre toutes les étapes affichées à l'écran.

## Résolution des problèmes
Si vous avez des problèmes pendant l'installation, vérifiez :
- Que votre machine a accès à Internet.
- Que toutes les dépendances nécessaires sont installées (par exemple, `curl`, `git`, `build-essential`).
