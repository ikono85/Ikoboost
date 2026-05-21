# Ikoboost

<p align="center">
  <strong>Centre de monitoring et d'optimisation Windows</strong>
</p>

<p align="center">
  Surveillez votre PC en temps reel, diagnostiquez votre reseau, gerez vos processus et optimisez Windows depuis une interface moderne.
</p>

<p align="center">
  <a href="https://github.com/ikono85/Ikoboost/releases/tag/v1.0.0"><strong>Telecharger Ikoboost</strong></a>
  ·
  <a href="https://github.com/ikono85/Ikoboost/releases/tag/v1.0.0">Voir la release</a>
  ·
  <a href="https://github.com/ikono85/Ikoboost/issues">Signaler un probleme</a>
</p>

<p align="center">
  <img alt="Windows 10/11" src="https://img.shields.io/badge/Windows-10%20%2F%2011-00E5FF?style=for-the-badge&logo=windows&logoColor=white">
  <img alt="x64" src="https://img.shields.io/badge/x64-Self--contained-101827?style=for-the-badge">
  <img alt="Monitoring reel" src="https://img.shields.io/badge/Monitoring-reel-00E5FF?style=for-the-badge">
  <img alt=".NET 8" src="https://img.shields.io/badge/.NET-8-7C3AED?style=for-the-badge&logo=dotnet&logoColor=white">
</p>

---

## Vue D'Ensemble

Ikoboost est une application Windows moderne concue pour centraliser le monitoring systeme, le diagnostic reseau, la gestion des processus, les applications Winget et plusieurs outils d'optimisation dans une interface claire.

L'objectif est simple : afficher des donnees utiles, lisibles et reelles, sans simulation ni valeurs artificielles.

| Dashboard temps reel | Monitoring materiel | Diagnostic reseau |
| --- | --- | --- |
| CPU, RAM, GPU, stockage, reseau et temperatures en direct. | Capteurs CPU, GPU, disques et ventilateurs via LibreHardwareMonitor quand ils sont disponibles. | Ping multi-serveurs, latence moyenne/min/max, DNS, passerelle et adaptateur actif. |

| Optimisation Windows | Processus | Applications Winget |
| --- | --- | --- |
| Nettoyage, DNS, profils d'alimentation et actions systeme. | Recherche, kill, restart, priorite, chemin, RAM et details processus. | Detection, installation, mise a jour et desinstallation d'applications. |

---

## Fonctionnalites

### Dashboard

- Utilisation CPU, RAM, GPU, stockage et reseau.
- Widgets personnalisables.
- Mise a jour en temps reel selon la frequence choisie.
- Informations systeme : nom du PC, Windows, utilisateur et uptime.

### Monitoring

- Vue type HWMonitor avec capteurs groupes.
- Valeurs actuelles, minimum et maximum.
- Gestion propre des capteurs absents avec affichage `N/A`.
- Support LibreHardwareMonitor pour les donnees disponibles.

### Reseau

- IPv4, IPv6, DNS actifs et passerelle.
- Ping multi-serveurs : Cloudflare, Google, Quad9, Microsoft, GitHub.
- Latence moyenne, minimum et maximum.
- Boutons de diagnostic, reparation reseau et export.

### Optimisation

- Nettoyage systeme.
- Changement DNS : Cloudflare, Google, Quad9.
- Profils d'alimentation Windows.
- Journalisation des actions reussies ou echouees.

### Processus

- Liste des processus actifs.
- Recherche instantanee et tri.
- CPU, RAM, description, editeur et chemin complet.
- Actions : arreter, redemarrer et changer la priorite.

### Parametres

- Themes Jour, Nuit, Auto et Cyberpunk.
- Frequence d'actualisation : 1s, 2s, 5s, 10s.
- Alertes temperature, reseau, stockage et batterie.
- Sauvegarde automatique des preferences en JSON.
- Reduction dans le tray et restauration depuis la barre systeme.

---

## Installation

1. Ouvrir la page [GitHub Releases](https://github.com/ikono85/Ikoboost/releases/tag/v1.0.0).
2. Telecharger l'archive `Ikoboost-exe.7z`.
3. Extraire l'archive puis lancer `Ikoboost.exe`.

> L'application est publiee en version Windows x64 self-contained quand disponible. Aucun SDK .NET n'est requis pour l'utilisateur final avec cette version.

---

## Transparence

Ikoboost affiche uniquement des donnees reelles provenant du systeme.

- Aucune donnee simulee dans l'interface.
- Logs locaux pour suivre les actions et erreurs.
- Gestion des capteurs absents avec affichage clair.
- Gestion de Winget absent, permissions administrateur et cartes reseau indisponibles.
- Monitoring materiel via LibreHardwareMonitor selon les capteurs exposes par la machine.

---

## Roadmap

- Sante PC globale.
- Mode maintenance en un clic.
- Historique reseau.
- Notifications avancees.
- Installeur Windows complet.
- Export de rapports systeme.

---

## Stack Technique

- .NET 8
- WPF
- MVVM
- CommunityToolkit.Mvvm
- LibreHardwareMonitor
- LiveCharts
- Winget

---

## Licence

La licence du projet sera precisee dans le depot. Avant toute redistribution ou contribution publique, ajoute un fichier `LICENSE` adapte au mode de publication souhaite.

---

<p align="center">
  <strong>Ikoboost</strong><br>
  Windows monitoring & optimization center
</p>
