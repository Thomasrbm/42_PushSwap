# 42_PushSwap

Bienvenue sur le dépôt **42_PushSwap** !  
Ce projet fait partie du cursus 42 et a pour but d'implémenter un algorithme de tri optimisé sur un ensemble de nombres à l’aide d’un jeu limité d’opérations sur deux piles.

---

## 🚀 Objectif du projet

Vous devez trier une liste d'entiers dans l'ordre croissant en utilisant uniquement certaines opérations prédéfinies (push, swap, rotate et reverse rotate) sur deux piles (`a` et `b`).  
Le défi est de minimiser le nombre de mouvements nécessaires.

---

## 🛠️ Fonctionnement

- **Entrée** : Une liste de nombres entiers en arguments de la ligne de commande.
- **Sortie** : Une suite d’instructions (opérations) qui, appliquées aux piles, trient la liste initiale.

### Opérations autorisées

- `sa`, `sb`, `ss` : swap le sommet de la pile
- `pa`, `pb` : push du sommet d'une pile sur l’autre
- `ra`, `rb`, `rr` : rotation vers le haut
- `rra`, `rrb`, `rrr` : rotation vers le bas

---

## 📦 Compilation

Pour compiler le projet :

```bash
make
```

Cela génère l’exécutable `push_swap`.

---

## 💡 Utilisation

```bash
./push_swap [nombres à trier]
```

**Exemple :**
```bash
./push_swap 2 1 3 6 5 8
```

Le programme affiche la suite d’opérations qui trie la pile.

---

## 📁 Structure du projet

- `src/` : fichiers sources principaux
- `include/` : headers du projet
- `Makefile` : fichier de compilation

---

## 🧠 Stratégies d’optimisation

L’algorithme doit être intelligent :
- Gestion efficace des petits cas (3, 5 éléments)
- Implémentation de tris plus avancés pour les grandes listes (ex: radix sort)
- Réduction maximale du nombre de coups

---

## 📝 Règles importantes

- Aucune fuite mémoire n’est tolérée (utilisez `valgrind` !)
- Respectez la norme 42
- Pas de bibliothèque standard autre que celles autorisées

---

## 🙌 Remerciements

Projet réalisé dans le cadre de la formation [42](https://42.fr/).

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE) ou selon les règles de 42.

---

Bonne chance et happy coding! 🚦
