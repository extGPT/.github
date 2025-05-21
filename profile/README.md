# 🌐 Bienvenue sur l’organisation GitHub de extGPT

Bienvenue ! Ici, vous trouverez nos projets collaboratifs dédiés à l’innovation, à la technologie et aux systèmes intelligents. Explorez nos dépôts principaux, **Fumobilité** et **NetMatéria**, chacun illustrant un domaine spécifique de recherche et développement.

## 🚀 Projets Actifs

### 🚍 [Fumobilité](https://github.com/extGPT/Fumobilite)

**Fumobilité** est une application de gestion de la mobilité urbaine, développée en C# (.NET Framework 4.8, WinForms). Elle vise à optimiser les déplacements, faciliter la gestion des réseaux de transport et améliorer l’accessibilité pour tous les usagers.

#### ✨ Fonctionnalités principales

- **Consultation du réseau** : Visualisation des lignes, arrêts et horaires.
- **Recherche d’itinéraires** : Calcul de trajets optimisés selon les besoins de l’utilisateur.
- **Gestion des utilisateurs** : Administration des comptes, rôles (Admin/Utilisateur), activation/désactivation.
- **Gestion des lignes, arrêts et horaires** : Ajout, modification, suppression via une interface graphique intuitive.
- **Authentification sécurisée** : Connexion/déconnexion, gestion des droits d’accès.
- **Mode invité** : Accès limité pour les utilisateurs non authentifiés.

#### 🛠️ Technologies

- **Langage** : C#
- **Framework** : .NET Framework 4.8
- **Interface** : Windows Forms (WinForms)
- **Base de données** : SQLite (fichier local `Fumoblilite.db`)
- **Architecture** : Séparation claire entre interface, logique métier et accès aux données

#### 📦 Structure du projet

- `Fumoblilite.Interface` : Interface graphique (WinForms)
- `Fumoblilite.Systeme` : Modèles, services métier
- `Fumoblilite.SQL` : Accès et gestion de la base de données

#### 🚀 Démarrage rapide

1. **Cloner le dépôt**
   `git clone https://github.com/extGPT/Fumobilite.git`
&nbsp;

2. **Ouvrir la solution dans Visual Studio 2022**
&nbsp;


3. **Compiler et exécuter**
   - La base de données SQLite est créée automatiquement au premier lancement.
   - Identifiants par défaut :  
     - Utilisateur : `admin`  
     - Mot de passe : `admin`

### 🧪 [NetMatéria](https://github.com/extGPT/NetMateria)

**NetMatéria** est un utilitaire Windows permettant de calculer le **checksum d’un en-tête IP** à partir de données hexadécimales. Il s’adresse aux étudiants, enseignants et professionnels des réseaux souhaitant vérifier ou comprendre le calcul du checksum IP.

#### ✨ Fonctionnalités principales

- **Calcul du checksum IP** : Saisie d’un en-tête IP au format hexadécimal, calcul automatique du champ checksum.
- **Explication détaillée** : Affichage étape par étape du calcul pour l’apprentissage ou la vérification.
- **Gestion des erreurs** : Messages clairs en cas de format incorrect ou de données invalides.
- **Interface intuitive** : Application Windows Forms ergonomique et simple d’utilisation.
- **Effacement rapide** : Réinitialisation du formulaire en un clic.

#### 🛠️ Technologies

- **Langage** : C#
- **Framework** : .NET Framework 4.8
- **Interface** : Windows Forms (WinForms)

#### 📦 Structure du projet

- `Forms/MainForm.cs` : Logique principale de l’interface utilisateur
- `Forms/MainForm.Designer.cs` : Définition de l’interface graphique
- `Program.cs` : Point d’entrée de l’application

#### 🚀 Démarrage rapide

1. **Cloner le dépôt**
`git clone https://github.com/NOM-ORGA/NetMateria.git`
&nbsp;



2. **Ouvrir la solution dans Visual Studio 2022**
&nbsp;

3. **Compiler et exécuter**
   - L’application démarre directement, aucune base de données n’est requise.
   - Entrez un en-tête IP en hexadécimal, cliquez sur "Calculer le Checksum".


## 📫 Contact
Pour toute question ou collaboration, n’hésitez pas à nous contacter via GitHub ou à envoyer un email à exGPT@gmail.com.

---

Merci de votre intérêt pour nos projets ! 🚀

![fumo](https://preview.redd.it/dwj3062yenx71.gif?width=374&auto=webp&s=241fdc1deb723ec5ecc0e247a63e51c73914f80c)
