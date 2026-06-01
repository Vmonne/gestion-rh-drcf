# 📋 Gestion RH
**Application de gestion du personnel — offline, sans installation**

> Application web hors ligne de gestion du personnel pour administrations publiques à ressources limitées.
> Offline HR management web app for public administrations with limited resources.

---

## 🇫🇷 Français

### Présentation

**Gestion RH** est une application HTML/JS monopage développée pour la gestion quotidienne du personnel d'une direction administrative. Elle remplace les registres papier et les tableaux Excel par un outil numérique léger, utilisable sans connexion Internet, sans serveur, et sans installation.

Développée et déployée en production par **Loua Monné Victorine KPAN**, Conservatrice d'Archives et responsable RH auprès du Directeur régional (Ministère de la Culture et de la Francophonie, Côte d'Ivoire).

### Fonctionnalités

- 👥 **Gestion des agents** — Fiche individuelle (matricule, poste, département, téléphone)
- ✅ **Pointage quotidien** — Présent, absent, permissionnaire
- 📅 **Absences** — Suivi par type (maladie, congé annuel, absence injustifiée, événement familial)
- 🚪 **Autorisations de sortie** — Heure de départ, heure de retour, motif, autorisant
- 📝 **Permissions** — Demande, approbation/refus, suivi du statut
- 📊 **Rapports hebdomadaires imprimables** — Récapitulatif par agent avec blocs de signature (Agent / Responsable RH / Directeur)
- 💾 **Sauvegarde / Restauration JSON** — Export et import des données

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
2. Saisir le mot de passe (voir section **Personnalisation** ci-dessous)
3. Aucune installation, aucune connexion requise
4. Les données sont stockées localement dans le navigateur (localStorage)
5. Utiliser le bouton **Sauvegarder** régulièrement pour exporter vos données en JSON

> ⚠️ Les données sont liées au navigateur. Si vous changez de navigateur ou d'ordinateur, utilisez la fonction **Restaurer** pour récupérer vos données depuis un fichier de sauvegarde.

### Personnalisation

#### Changer le nom de l'organisation

Ouvrir `gestion_rh.html` dans un éditeur de texte (Notepad, VS Code, etc.) et rechercher `MON ORGANISATION`. Remplacer par le nom de votre structure. Cette mention apparaît à 3 endroits dans le fichier.

#### Changer le mot de passe

L'application n'a pas d'interface de configuration — le mot de passe se change directement dans le code.

**Mot de passe par défaut : `admin1234`**

Pour le changer :

1. Ouvrir `gestion_rh.html` dans un éditeur de texte
2. Rechercher la ligne suivante (vers la fin du fichier) :
```javascript
const MDP_STOCKE = hashSimple('admin1234');
```
3. Remplacer `admin1234` par votre mot de passe
4. Sauvegarder le fichier

> ⚠️ Le mot de passe est stocké sous forme de hash simple dans le code. Cette protection est suffisante pour un usage interne, mais ne convient pas à des données hautement sensibles.

---

## 🇬🇧 English

### Overview

**Gestion RH** is a single-file HTML/JS offline web application for day-to-day staff management in an administrative directorate. It replaces paper registers and Excel spreadsheets with a lightweight digital tool that works without internet access, without a server, and without installation.

Developed and deployed in production by **Loua Monné Victorine KPAN**, Records Manager and HR Officer to the Regional Director (Ministry of Culture and Francophonie, Côte d'Ivoire).

### Features

- 👥 **Staff directory** — Individual records (staff ID, position, department, phone)
- ✅ **Daily attendance tracking** — Present, absent, on leave
- 📅 **Absence management** — By type (sick leave, annual leave, unjustified absence, family event)
- 🚪 **Exit authorizations** — Departure/return time, reason, authorizing officer
- 📝 **Leave permissions** — Request, approval/rejection, status tracking
- 📊 **Printable weekly reports** — Per-staff summary with signature blocks (Staff / HR Officer / Director)
- 💾 **JSON backup / restore** — Data export and import

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
2. Enter the password (see **Customization** section below)
3. No installation or internet connection required
4. Data is stored locally in the browser (localStorage)
5. Use the **Sauvegarder** button regularly to export your data as JSON

> ⚠️ Data is tied to the browser. If you switch browsers or computers, use the **Restaurer** function to restore your data from a backup file.

### Customization

#### Change the organization name

Open `gestion_rh.html` in a text editor (Notepad, VS Code, etc.) and search for `MON ORGANISATION`. Replace it with your organization's name. This appears in 3 places in the file.

#### Change the password

The application has no configuration interface — the password is changed directly in the source code.

**Default password: `admin1234`**

To change it:

1. Open `gestion_rh.html` in a text editor
2. Find the following line (near the end of the file):
```javascript
const MDP_STOCKE = hashSimple('admin1234');
```
3. Replace `admin1234` with your chosen password
4. Save the file

> ⚠️ The password is stored as a simple hash in the code. This protection is suitable for internal use, but not for highly sensitive data.

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
