# Libft

## Description

Projet `libft` de l'école 42. L'objectif est de créer votre propre bibliothèque C standard, contenant des fonctions couramment utilisées, pour remplacer certaines des fonctions de la bibliothèque standard C.

## Fonctionnalités supportées

- Fonctions de manipulation de chaînes de caractères (`strlen`, `strcpy`, `strcat`, `strchr`, etc.).
- Fonctions de manipulation de mémoire (`memset`, `bzero`, `memcpy`, `memccpy`, etc.).
- Fonctions de conversion de types (`atoi`, `itoa`, `utoa`, `ftoa`, etc.).
- Fonctions de manipulation de listes (`lstnew`, `lstadd_front`, `lstsize`, `lstiter`, etc.).
- Fonctions additionnelles utiles (`isalpha`, `isdigit`, `isspace`, etc.).

## Comment utiliser

1. Clonez le dépôt : `git clone <lien du dépôt>`.
2. Naviguez dans le répertoire `libft`.
3. Exécutez `make` pour compiler la bibliothèque statique `libft.a`.
4. Vous pouvez maintenant utiliser `libft.a` avec votre programme.

## Exemples

```c
#include "libft.h"

int main()
{
    char *str = "Hello, world!";
    ft_putstr(str);
    return (0);
}
