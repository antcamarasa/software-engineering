# Software Engineering

Mon parcours d'autoformation en informatique fondamentale, construit sur une seule idée :

> **Short cut makes long delay.**

Les frameworks, je les apprends au travail. Ici, je construis ce que les frameworks cachent : les structures de données, le langage C, la machine, le réseau.

## Feuille de route

| # | Bloc | Ressource | Pratique | Statut | Repo |
|---|------|-----------|----------|--------|------|
| 1 | Structures de données et algorithmes (Java) | *Data Structures and Algorithms in Java* — Goodrich, Tamassia, Goldwasser | Recoder chaque structure + exercices de chaque chapitre | 🟡 En cours | [dsa-java](https://github.com/antcamarasa/data-structures-algorithm) |
| 2 | C | *The C Programming Language* — Kernighan & Ritchie | Tous les exercices | ⚪ À faire | [C](https://github.com/antcamarasa/c) |
| 3 | Systèmes informatiques (C) | *Computer Systems: A Programmer's Perspective* — Bryant & O'Hallaron | Les 8 labs officiels | ⚪ À faire | [computer-systems](https://github.com/antcamarasa/computer-systems) |
| 3b | ↳ Minishell | Shell Lab de CS:APP | Mon propre shell Unix avec contrôle des tâches | ⚪ À faire | [minishell](https://github.com/antcamarasa/minishell) |
| 4 | Programmation réseau (C) | *Hands-On Network Programming with C* — Lewis Van Winkle |  ⚪ À faire | [network-programming-c](https://github.com/antcamarasa/network-programming) |
| 4b | ↳ Discord | Serveur de chat en C (POSIX)| Mon propre discord maison | ⚪ À faire | [minishell](https://github.com/antcamarasa/discord) |

Statut : ⚪ À faire · 🟡 En cours · 🟢 Terminé

## Les blocs

### 1. Structures de données et algorithmes — Java

**Pourquoi :** la base de tout. Sans ça, on ne sait pas coder. Choisir une structure, raisonner en complexité, écrire du vrai code orienté objet (ADT → classe abstraite → implémentations).

**Condition de sortie :** livre lu, structures implémentée, exercices fait.

### 2. Langage C

**Pourquoi :** le langage de tous les blocs suivants. CS:APP suppose qu'on le maîtrise déjà. Minishell n'a aucun intérêt dans un autre langage. le réseau s'apprend en C.

**Périmètre :** le livre en entier.

**Condition de sortie :** tous les exercices faits.

### 3. Systèmes informatiques — C

**Pourquoi :** la machine de bas en haut. Représentation des données en binaire, assembleur, processeur, hiérarchie mémoire, édition de liens, processus et signaux, mémoire virtuelle, E/S système, réseau, concurrence.

**Périmètre :** le livre en entier + labs

**Labs :** Data, Bomb, Attack, Architecture, Cache, Shell (→ minishell), Malloc, Proxy.

**Projet :** Re construire un minishell.

### 4. Programmation réseau — C

**Pourquoi :** Un back-end, c'est un programme qui parle à d'autres programmes à travers le réseau. Ce bloc approfondit ce que CS:APP a posé : UDP, DNS, HTTP, TLS, gestion de plusieurs clients.

**Périmètre :** tout le livre sauf SMTP (chap. 8), SSH (chap. 11) et IoT (chap. 14).

**Projet :** un serveur de chat type Discord en C, avec plusieurs clients, des salons et `poll()`. Le projet existe comme sujet de la plateforme.


## Plus tard, peut-être

- Le fonctionnement interne des bases de données.
- Les compilateurs et interpréteurs.
- Les systèmes distribués
