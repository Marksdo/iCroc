# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - Application CLI de Croc pour iOS et macOS

Téléchargez [la dernière version depuis l'App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Refonte complète de toute l'interface de l'application et de la logique de fonctionnement.
- Mise à jour de la version embarquée de croc à v10.0.8.
- Ajout de la prise en charge de la fonctionnalité Handoff pour iOS et macOS.
- Prise en charge de plus de langues.

V1.1
---
- Refonte de l'icône de l'application.
- Corrections de bugs et améliorations des performances.

V1.0
---
croc est un outil qui permet à deux ordinateurs de transférer des fichiers et des dossiers de manière simple et sécurisée. À ma connaissance, croc est le seul outil de transfert de fichiers CLI qui offre toutes les fonctionnalités suivantes :

- Permet à deux ordinateurs de transférer des données (en utilisant un relais).
- Fournit un chiffrement de bout en bout (en utilisant PAKE).
- Facilite les transferts multiplateformes (Windows, Linux, Mac).
- Permet des transferts de plusieurs fichiers.
- Permet de reprendre les transferts interrompus.
- Pas besoin de serveur local ou de redirection de port.
- Priorité à IPv6 avec basculement sur IPv4.
- Peut utiliser un proxy, comme Tor.

L'application en ligne de commande sur laquelle elle est basée se trouve ici :

https://github.com/schollz/croc

## Activer iCroc dans les paramètres de macOS
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Envoi rapide de fichiers avec iCroc
- Sélectionnez des fichiers dans le Finder, puis utilisez "Ouvrir avec iCroc".
- Dans le Finder, sélectionnez des fichiers et utilisez ⌘+C pour copier, puis ouvrez iCroc et utilisez ⌘+V pour envoyer les fichiers.
- Faites glisser les fichiers dans iCroc.

# ⚡ Handoff
- Installer l'application iCroc sur les appareils iOS et macOS.
- Activer la fonctionnalité Handoff sur les appareils iOS et macOS.
- Lorsque l'expéditeur génère une phrase de code, iCroc sur l'autre appareil recevra automatiquement la phrase de code.

# 🔮 Reprendre une tâche interrompue
- L'expéditeur renvoie le fichier et le récepteur utilise le format nouvelle phrase de code@ancienne phrase de code, ex : 4161-mambo-young-baby@7611-south-concept-satire.
- L'expéditeur renvoie le fichier en utilisant le jeton personnalisé comme ancienne phrase de code.

# 💾 Dossier de réception personnalisé
- Le dossier de réception sera enregistré dans ~/Downloads/'${code-phrase}'.
- Utiliser '@nomDossier' pour enregistrer dans ~/Downloads/nomDossier, ex : 8443-siren-mayor-origin@mypics.
- Utiliser le même dossier de destination permettra de reprendre automatiquement les tâches de transfert interrompues.