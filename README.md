# Veltrix Mecha-Chameleon | External Cheat & Overlay

Un logiciel de triche (cheat) externe et autonome pour Windows. Conçu avec un scanner de signatures dynamique, il intègre un système d'assistance à la visée (aimbot) et un affichage visuel superposé (ESP/Overlay) via l'API graphique GDI de Windows.

##  Téléchargement et Utilisation

1. Rendez-vous dans la section **[Releases](https://github.com/VeltrixJS/VelTrix-Meccha-Chameleon-Cheat/releases)** située à droite de cette page.
2. Téléchargez la dernière version du fichier `VELTRIX.exe`.
3. Lancez votre jeu, puis exécutez le fichier `.exe` en mode administrateur pour lui permettre de se lier au processus.

##  Analyse de Sécurité (VirusTotal)

L'exécutable a été soumis à une analyse complète sur VirusTotal pour garantir une totale transparence :

* **Rapport de scan :** [Cliquez ici pour voir le rapport officiel VirusTotal](https://www.virustotal.com/gui/file/67adda36a36da0e3d128f9db64b832edf373282cf284c77d6882b61bc961131c)
* **Score de détection :** 3 / 69 (Faux positifs)

> **Note importante sur les alertes :** Le fichier affiche un score de 3 détections sur 69 (notamment l'alerte générique *Wacatac.B!ml* de Microsoft Windows Defender). Il s'agit de **faux positifs** habituels pour ce type de programme. Les algorithmes d'apprentissage automatique (Machine Learning) des antivirus signalent l'exécutable car il utilise les fonctions natives de l'API Windows pour interagir avec la mémoire d'un autre processus en cours d'exécution. Les 66 autres moteurs de sécurité confirment que le fichier est totalement sain.

##  Prérequis et Spécifications

- **Système d'exploitation :** Windows 10 / Windows 11 (64-bits).
- **Privilèges :** Exécution en mode Administrateur requise (nécessaire pour la lecture de la mémoire du jeu).
- **Dépendances :** Aucune (application autonome / standalone).
