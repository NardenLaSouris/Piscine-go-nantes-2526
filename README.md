# Piscine Go, Nantes 2025-2026

Mes exercices de la Piscine Go (Ynov Nantes, plateforme 01 Edu) : une centaine de fonctions écrites sans la bibliothèque standard, pour apprendre Go et l'algorithmique de base.

## Organisation

Chaque exercice suit le même schéma :

- `nomexercice.go` : la fonction demandée, dans le paquet `piscine` ;
- `nomexercice/main.go` : un petit programme qui l'appelle pour la tester.

Les fonctions n'importent aucun paquet de la bibliothèque standard : tout est réécrit à la main (seul `eightqueens` affiche avec `z01.PrintRune`, la bibliothèque de la Piscine). Les programmes de test, eux, affichent les résultats avec `fmt`.

## Thèmes couverts

| Thème | Exemples |
|---|---|
| Affichage | `printalphabet`, `printcomb`, `printcombn`, `printnbr`, `printnbrbase` |
| Chaînes | `strlen`, `strrev`, `capitalize`, `split`, `splitwhitespaces`, `join`, `index`, `compare` |
| Conversions | `atoi`, `atoibase`, `convertbase`, `nbrconvertalpha` |
| Mathématiques | `fibonacci`, `isprime`, `findnextprime`, `sqrt`, `recursivepower`, `iterativefactorial` |
| Tableaux et tris | `sortintegertable`, `sortwordarr`, `advancedsortwordarr`, `issorted`, `makerange`, `map`, `countif` |
| Pointeurs | `pointone`, `divmod` |
| Arguments du programme | `printparams`, `revparams`, `sortparams`, `flags`, `displayfile`, `cat` |
| Listes chaînées | `listpushback`, `listreverse`, `listsort`, `listmerge`, `listremoveif`, `sortlistinsert` |
| Arbres binaires de recherche (Quest 12) | `btreeinsertdata`, `btreeapplyinorder`, `btreelevelcount`, `btreedeletenode`, `btreetransplant` |
| Problèmes classiques | `eightqueens` |

## Lancer un exercice

Go 1.23 ou plus récent.

```bash
git clone https://github.com/NardenLaSouris/Piscine-go-nantes-2526.git
cd Piscine-go-nantes-2526
go run ./atoi
```

Remplacer `atoi` par le nom de n'importe quel dossier d'exercice.
