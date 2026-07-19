# Retouch Launcher

[![Release](https://img.shields.io/github/v/release/HSEV/retouch-releases?label=derni%C3%A8re%20version)](https://github.com/HSEV/retouch-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/HSEV/retouch-releases/total)](https://github.com/HSEV/retouch-releases/releases)
[![Platform](https://img.shields.io/badge/plateforme-windows-black)](https://github.com/HSEV/retouch-releases/releases/latest)
[![Discord](https://img.shields.io/discord/1528217755474591835?label=discord&logo=discord&color=5865F2)](https://discord.gg/U63MHffDQX)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fretouch.blog&label=retouch.blog)](https://retouch.blog)




**Retouch** est un launcher desktop qui te permet de jouer à **Dofus Touch** directement sur PC, sans émulateur Android.

Ce dépôt sert uniquement à la **distribution des builds** de Retouch — c'est ici que tu trouveras toujours la dernière version à télécharger. Site officiel : **[retouch.blog](https://retouch.blog)**


<img width="1697" height="992" alt="image" src="https://github.com/user-attachments/assets/6d33829a-2ffe-4fe7-9a67-14c228405004" />

## Téléchargement

👉 **[Dernière version](https://github.com/HSEV/retouch-releases/releases/latest)**

Deux fichiers sont proposés à chaque release :

| Fichier | Usage |
|---|---|
| `Retouch-x.x.x-portable.exe` | Aucune installation - lance-le directement, où tu veux. |
| `Retouch-x.x.x-Setup.exe` | Installeur classique (choix du dossier d'installation, raccourcis). |

> ⚠️ Les exécutables ne sont pas signés (pas de certificat payant) - Windows SmartScreen peut afficher un avertissement "éditeur inconnu" au premier lancement. C'est normal pour un projet indépendant : clique sur *Informations complémentaires* → *Exécuter quand même*.

## Fonctionnalités

- Lance Dofus Touch dans une fenêtre desktop moderne, redimensionnable
- Toujours synchronisé avec les fichiers officiels du jeu
- Réglages de résolution (presets ou taille personnalisée), appliqués instantanément
- Coupe-son fonctionnel
- Interface sombre, sans bordure système, pensée pour ne pas dénaturer l'expérience de jeu

## Comment ça marche, sans zone d'ombre

Dofus Touch est en réalité un jeu HTML5/JS servi par Ankama depuis son propre CDN — pas une appli Android à émuler. Le launcher se contente de le récupérer et de l'afficher.

**01 · Téléchargement**
Le launcher récupère les fichiers du client Dofus Touch directement depuis le CDN officiel d'Ankama, comme le fait l'application mobile.

**02 · Correctifs de compatibilité**
Des correctifs de compatibilité communautaires adaptent ces fichiers pour qu'ils tournent hors du wrapper Android natif prévu par Ankama.

**03 · Service local**
Les fichiers patchés sont servis localement sur votre machine, sans jamais transiter par un serveur tiers.

**04 · Affichage natif**
Electron affiche le client dans une fenêtre desktop sur-mesure. Le jeu se re-synchronise à chaque lancement : toujours à jour, sans intervention.

## Communauté

Une question, un bug, une suggestion ? Rejoins le Discord :

💬 **[discord.gg/U63MHffDQX](https://discord.gg/U63MHffDQX)**

🌐 Site : **[retouch.blog](https://retouch.blog)**

## Avertissement

Retouch n'est pas affilié à Ankama Games, éditeur de Dofus Touch. Il fonctionne en récupérant et en adaptant des ressources du jeu pour les exécuter dans un environnement desktop non prévu à l'origine ; à ce titre, son usage peut ne pas être conforme aux conditions d'utilisation du jeu. Utilisation à tes propres risques.
