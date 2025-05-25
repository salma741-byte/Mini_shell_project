# 🐚 Mini Shell – Interpréteur de commandes UNIX en C

Un mini shell développé en C, dans le cadre d’un projet de programmation système.  
Il permet l’exécution de commandes, la navigation dans les répertoires, et offre une meilleure compréhension du fonctionnement interne d’un shell UNIX.

---

## 📚 Sommaire

- [🧠 Présentation du projet](#-présentation-du-projet)
- [⚙️ Fonctionnalités](#️-fonctionnalités)
- [📦 Installation](#-installation)
- [🖥️ Exemple d'utilisation](#️-exemple-dutilisation)
- [🎯 Objectifs pédagogiques](#-objectifs-pédagogiques)
- [⛔ Limitations](#-limitations)
- [🚀 Améliorations prévues](#-améliorations-prévues)
- [👩‍💻 Auteure](#-auteure)

---

## 🧠 Présentation du projet

**Mini Shell** est un interpréteur de ligne de commande minimaliste fonctionnant sous UNIX/Linux.  
Il exécute des commandes simples, gère des processus via `fork`, `execvp` et `wait`, et propose quelques commandes intégrées.  

Objectifs principaux du projet :
- Apprendre à manipuler des processus à bas niveau
- Comprendre le fonctionnement interne d’un shell
- Utiliser des appels système C (entrées/sorties, signaux, exécution)

---

## ⚙️ Fonctionnalités

✔️ **Exécution de commandes UNIX standards** (`ls`, `pwd`, `echo`, etc.)  
✔️ **Commandes intégrées** :
- `cd <répertoire>` – Changer de répertoire
- `exit` – Quitter le shell
- `help` – Afficher l’aide

✔️ **Gestion des processus** avec `fork()`, `execvp()`, et `wait()`  
✔️ **Invite personnalisée**  
✔️ **Gestion basique de `Ctrl+C`** (signal SIGINT)  
✔️ **Affichage clair et structuré des résultats**

---

## 📦 Installation

### 🔧 Prérequis

- Système Linux (Ubuntu, Debian…)
- Compilateur GCC
- `make`
- `git`

## 🛠️ Étapes d’installation

```bash
# Cloner le dépôt
git clone https://github.com/salma741-byte/Mini_shell_project.git

# Aller dans le dossier du projet
cd Mini_shell_project_salma_farid

# Compiler le shell
make

# Lancer le shell
./salma_shell

```

## 🖥️ Exemple d'utilisation
![Capture d’écran (9)](https://github.com/user-attachments/assets/e65e7563-a1f4-424f-a103-35fb5c6b35e9)





## 🎯 Objectifs pédagogiques
Ce projet m’a permis de :

- Mieux comprendre le rôle et la structure d’un shell UNIX

- Travailler avec des appels système (fork, execvp, wait)

- Gérer les entrées utilisateur et parser des commandes

- Utiliser des signaux (comme SIGINT)

- Organiser un projet C avec Makefile

- Développer mes compétences en C et en interaction terminale


## 👩‍💻 Auteur

**Nom** : Salma Farid

**Projet** : Mini Shell développé pour un module de systèmes d’exploitation

**GitHub** : [@salma741-byte](https://github.com/salma741-byte/Mini_shell_project)



