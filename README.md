# MyServeur - Interface Web sur Raspberry Pi

Bienvenue sur le dépôt GitHub du projet **MyServeur**, une interface web hébergée sur un **Raspberry Pi** permettant d'accéder facilement à des ressources personnelles comme des fichiers, cours, et projets. Ce dépôt contient le code source et les instructions pour installer et configurer l'interface web de votre serveur personnel.

## Table des matières
- [À propos](#à-propos)
- [Fonctionnalités principales](#fonctionnalités-principales)
- [Structure des pages](#structure-des-pages)
- [Installation](#installation)
- [Légalité et distribution de liens](#légalité-et-distribution-de-liens)
- [Contact](#contact)
- [Licence](#licence)

---

## À propos
**MyServeur** est un projet personnel qui utilise un serveur **Raspberry Pi** pour stocker et organiser des fichiers, cours et projets. Accessible via une interface web, ce serveur offre une gestion simplifiée des ressources numériques et permet une interaction facile via le navigateur. Il est utilisé dans un cadre éducatif pour stocker et partager des cours et projets scolaires.

Le serveur est accessible localement via `http://rezkimohammad.ddns.net/`, mais il est essentiel de respecter les lois relatives à la distribution des liens, surtout dans un contexte HTML et de partage en ligne.

---

## Fonctionnalités principales

### 1. **Accès aux fichiers**
L'interface web permet de naviguer entre différents dossiers (cours, projets, etc.), offrant un accès rapide aux ressources personnelles.
- 💡 **Illustration suggérée** : Capture d'écran de la page d'accueil avec les sections "Fichiers", "Mes cours", "Mes Projets".

### 2. **Gestion des cours et projets**
Organisation des cours par année scolaire (Seconde, Première, Terminale) avec des sous-sections dédiées aux différents projets.
- 💡 **Illustration suggérée** : Une vue des différentes sections de cours organisées par année (avec des sous-dossiers pour chaque matière ou projet).

### 3. **Intégration Discord**
Le site inclut un lien pour rejoindre le serveur Discord de la communauté, favorisant la discussion autour des projets et des cours partagés.
- 💡 **Illustration suggérée** : Capture du bouton pour rejoindre le serveur Discord.

### 4. **Interface intuitive**
L'interface permet de naviguer facilement entre les pages grâce à des boutons de navigation "Retour" et "Avant", facilitant l'exploration des contenus stockés.
- 💡 **Illustration suggérée** : Visuel des boutons de navigation sur la page.

---

## Structure des pages

### Page d'accueil
- **Sections** : 
  - Fichiers : Accès direct à tous les fichiers stockés sur le serveur.
  - Mes cours : Organisation des cours par niveau (Seconde, Première, Terminale).
  - Mes projets : Gestion des projets personnels et scolaires.
  - Discord : Invitation à rejoindre le serveur Discord pour discuter avec la communauté.

### Page des cours et projets
- **Sous-sections** : 
  - Ma Seconde
  - Ma Première
  - Ma Terminale

Chaque sous-section contient des fichiers relatifs à l'année scolaire correspondante, permettant une navigation facile entre les différents documents.

### Page Discord
- Lien direct pour rejoindre le serveur Discord, permettant aux utilisateurs de discuter en temps réel des projets partagés et des cours.

---

## Installation

### Prérequis
- Un **Raspberry Pi** (version recommandée : Raspberry Pi 3 ou 4)
- **Raspbian OS** installé
- **Serveur Web** (Apache, Nginx ou autre)
- **PHP** (version 7.4 ou supérieure)

### Étapes d'installation
1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/votre-utilisateur/myserveur.git
   ```
2. **Configurer le serveur web** :
   - Installez Apache ou Nginx et PHP sur votre Raspberry Pi.
   - Configurez le serveur pour pointer vers le dossier de votre projet.

3. **Lancer l'interface web** :
   Accédez à l'interface via l'adresse locale ou publique configurée sur votre Raspberry Pi (`http://rezkimohammad.ddns.net/`).

### Gestion des fichiers
Vous pouvez organiser vos fichiers directement via le système de fichiers de votre Raspberry Pi ou via l'interface web, en accédant aux sections *Fichiers*, *Mes cours*, et *Mes projets*.

---

## Légalité et distribution de liens

### Règles à suivre
Il est crucial de respecter les lois en vigueur concernant la **distribution de liens sans autorisation**. Voici quelques points importants à prendre en compte :
- **Ne pas distribuer** le lien `http://rezkimohammad.ddns.net/` sans une autorisation préalable pour éviter toute violation du droit d'auteur.
- La distribution du lien **peut être autorisée** uniquement dans un cadre strictement éducatif ou lors d'une présentation de projet, à condition que cette diffusion soit limitée aux personnes impliquées dans le projet ou l'enseignement.
- **Conséquences légales** : La distribution non autorisée de ce lien peut entraîner des poursuites judiciaires. Il est donc fortement conseillé de **consulter les lois** applicables avant tout partage.

En conclusion, il est impératif de respecter la loi pour protéger les droits d'auteur et éviter tout problème légal.

---

## Contact
Pour toute question ou demande d'information supplémentaire, n'hésitez pas à me contacter via :
- **E-mail** : rezki.mohammad.222@gmail.com

---

## Licence
Ce projet est sous licence [MIT](LICENSE). Consultez le fichier de licence pour plus de détails.

---
