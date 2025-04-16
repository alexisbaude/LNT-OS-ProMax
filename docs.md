# Guide d'installation de LNT OS

## Prérequis

Avant d'installer LNT OS, assurez-vous d'avoir :
- Un PC ou une machine virtuelle compatible avec Linux.
- Une connexion Internet pour télécharger les outils nécessaires.
- Une clé USB (si vous souhaitez créer un Live USB).

## Étapes d'installation

1. Clonez le dépôt `LNT-OS` depuis GitHub :
   ```bash
   git clone https://github.com/ton-utilisateur/LNT-OS.git
   cd LNT-OS
     	2.	Exécutez le script d’installation :
./setup.sh
  	3.	Suivez les instructions à l’écran pour compléter l’installation.

Une fois l’installation terminée, vous pouvez utiliser les outils inclus dans LNT OS pour résoudre des problèmes informatiques.
  #### d) Code source dans `src/`

Tu peux ajouter des fichiers comme `main.c`, `init.c`, et `utils.c` pour le code de base de ton projet. Par exemple, `main.c` peut contenir une fonction qui initialise le système et affiche un message de bienvenue :

```c
#include <stdio.h>

// Fonction d'initialisation
void init_system() {
    printf("Bienvenue sur LNT OS !\n");
}

// Fonction principale
int main() {
    init_system();
    printf("Le système est prêt à être utilisé.\n");
    return 0;
}
