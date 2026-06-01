# 📋 Gestion RH — Personnel DRCF
**HR Management App — Regional Directorate of Culture**

> Application web hors ligne de gestion du personnel pour administrations publiques à ressources limitées.
> Offline HR management web app for public administrations with limited resources.

---

## 🇫🇷 Français

### Présentation

**Gestion RH** est une application HTML/JS monopage développée pour la Direction Régionale de la Culture et de la Francophonie du N'Zi (Ministère de la Culture et de la Francophonie, Côte d'Ivoire). Elle remplace les registres papier et les tableaux Excel par un outil numérique léger, utilisable sans connexion Internet, sans serveur, et sans installation.

Développée et déployée en production par **Loua Monné Victorine KPAN**, Conservatrice d'Archives et responsable RH auprès du Directeur régional.

### Fonctionnalités

- 👥 **Gestion des agents** — Fiche individuelle (matricule, poste, département, téléphone)
- 📅 **Pointage quotidien** — Présence, retard, absence, départ anticipé
- 🏥 **Absences** — Suivi par type (maladie, congé annuel, absence injustifiée, événement familial) avec justification
- 🚪 **Autorisations de sortie** — Heure de départ, heure de retour, motif, autorisant
- 📝 **Permissions** — Demande, approbation/refus, suivi du statut
- 📊 **Rapports individuels imprimables** — Récapitulatif mensuel avec blocs de signature (Agent / Responsable RH / Directeur)
- 💾 **Sauvegarde JSON** — Export et import des données pour archivage ou migration

### Technologie

| Composant | Technologie |
|---|---|
| Interface | HTML5 / CSS3 / JavaScript (vanilla) |
| Stockage | localStorage (navigateur, hors ligne) |
| Export | JSON natif |
| Impression | CSS Print |
| Dépendances | Aucune — fichier unique autonome |

### Utilisation

1. Ouvrir `gestion_rh.html` dans un navigateur (Chrome, Firefox, Edge)
2. Aucune installation, aucune connexion requise
3. Les données sont stockées localement dans le navigateur (localStorage)
4. Utiliser **Sauvegarder** pour exporter les données en JSON

### Contexte de déploiement

Déployé depuis septembre 2025 à la DRCF N'Zi (Dimbokro, Côte d'Ivoire) pour la gestion quotidienne du personnel d'une direction régionale du ministère. Remplace un suivi manuel sur registres papier.

---

## 🇬🇧 English

### Overview

**Gestion RH** is a single-file HTML/JS offline web application developed for the Regional Directorate of Culture and Francophonie, N'Zi (Ministry of Culture and Francophonie, Côte d'Ivoire). It replaces paper registers and Excel spreadsheets with a lightweight digital tool that works without internet access, without a server, and without installation.

Developed and deployed in production by **Loua Monné Victorine KPAN**, Records Manager and HR Officer to the Regional Director.

### Features

- 👥 **Staff directory** — Individual records (staff ID, position, department, phone)
- 📅 **Daily attendance tracking** — Present, late, absent, early departure
- 🏥 **Absence management** — By type (sick leave, annual leave, unjustified absence, family event) with justification flag
- 🚪 **Exit authorizations** — Departure/return time, reason, authorizing officer
- 📝 **Leave permissions** — Request, approval/rejection, status tracking
- 📊 **Printable individual reports** — Monthly summary with signature blocks (Staff / HR Officer / Director)
- 💾 **JSON backup** — Data export and import for archiving or migration

### Technology

| Component | Technology |
|---|---|
| Interface | HTML5 / CSS3 / Vanilla JavaScript |
| Storage | localStorage (browser-based, offline) |
| Export | Native JSON |
| Printing | CSS Print |
| Dependencies | None — fully self-contained single file |

### Usage

1. Open `gestion_rh.html` in any browser (Chrome, Firefox, Edge)
2. No installation or internet connection required
3. Data is stored locally in the browser (localStorage)
4. Use the **Sauvegarder** button to export data as JSON

### Deployment context

In production since September 2025 at DRCF N'Zi (Dimbokro, Côte d'Ivoire) for daily personnel management of a regional ministry directorate. Replaces manual paper-register tracking.

---

## Auteure / Author

**Loua Monné Victorine KPAN**
Conservatrice d'Archives | Records Manager & Information Management Specialist
Ministère de la Culture et de la Francophonie, Côte d'Ivoire

- 🌐 [victorinemonne.com](https://victorinemonne.com)
- 💼 [linkedin.com/in/victorinemonne](https://linkedin.com/in/victorinemonne)
- 🐙 [github.com/VMONNE](https://github.com/VMONNE)

---

## Licence / License

MIT License — voir [LICENSE](LICENSE)

Free to use, adapt, and redistribute with attribution.
