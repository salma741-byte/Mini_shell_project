Mini_Shell
Un shell UNIX minimaliste développé entièrement en langage C dans le cadre d’un projet de cours sur les systèmes d’exploitation.
Ce projet permet aux utilisateurs d’exécuter des commandes, de naviguer dans les répertoires et de comprendre le fonctionnement interne d’un shell à travers une programmation de bas niveau.

🔹 Table des matières

      Présentation du projet
      Fonctionnalités
      Installation
      Exemple d’utilisation

🔹 Objectifs pédagogiques

     Limitations
     Améliorations futures
     Auteur

🔹 Présentation du projet
Mini_Shell est un interpréteur de commandes UNIX minimal, développé en langage C, dans le cadre d’un projet de programmation système.

Ce shell permet d’exécuter des commandes de base, de gérer les processus à l’aide des appels système fork, execvp, et wait, et d’intégrer quelques commandes internes.
Il a été conçu pour approfondir la compréhension du fonctionnement interne d’un shell UNIX tout en développant des compétences en programmation système.

Le projet met l’accent sur :

La gestion des processus bas niveau

Le comportement d’un shell et l’interaction avec le terminal

Les appels système en C (gestion des processus, entrées/sorties, signaux)

🔹 Fonctionnalités
     Exécution de commandes – Prise en charge des commandes UNIX classiques comme ls, pwd, echo, etc.
     Commandes internes :

cd <répertoire> – Change le répertoire de travail courant

exit – Quitte le shell

help – Affiche une liste des commandes disponibles

  . Gestion des processus – Utilisation de fork(), execvp() et wait() pour créer et gérer des processus
  
  . Invite personnalisée – Affiche une invite de commande claire et intuitive
  
  . Gestion des signaux – Intercepte Ctrl+C pour éviter l’interruption du shell
  
  . Affichage propre – Résultats formatés pour une lecture claire

🔹 Installation

🛠 Prérequis

Un système basé sur Linux (Ubuntu, Debian, etc.)

Le compilateur GCC

L’utilitaire make

Git

🔹 Exemple d'usage
![image](https://github.com/user-attachments/assets/74804af0-e27e-4fdc-a573-83ecee7806d7)



















