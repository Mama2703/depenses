# 📒 Mon Carnet de Dépenses

Une application web simple pour gérer ses dépenses mensuelles — sur téléphone, tablette et ordinateur, sans compte ni installation.

**👉 https://mama2703.github.io/depenses/**

---

## ✨ Fonctionnalités

### 📊 Dépenses
- Saisie rapide : description, montant (virgule ou point), catégorie, date — touche **Entrée** pour valider
- **Modifier une dépense** en la touchant ; **supprimer** avec possibilité d'**annuler**
- Suggestions de descriptions déjà utilisées (la catégorie se remplit toute seule)
- La dépense est rangée dans le **mois de sa date**
- **Budget mensuel** : repris automatiquement le mois suivant, modifiable mois par mois
- Comparaison avec le mois précédent, moyenne par dépense, jauge du budget
- Graphiques : répartition par catégorie, évolution sur 12 mois (touche une barre pour aller à ce mois ; barre rouge = budget dépassé)

### ✅ À payer
- Liste des dépenses récurrentes du mois, à cocher au fur et à mesure
- **Cocher une ligne l'ajoute automatiquement dans Dépenses**, la décocher l'en retire
- Dépenses ponctuelles (seulement ce mois-ci)

### 📋 Mon modèle
- Liste de tes dépenses qui reviennent chaque mois (loyer, abonnements…)
- Modifier le modèle met à jour **le mois actuel et les suivants** ; les **mois passés gardent leur historique**

### Et aussi
- **Mode sombre** (automatique, ou à choisir dans le menu « Données »)
- **Fonctionne hors connexion** une fois installée
- Navigation par mois commune aux onglets, bouton « Mois actuel »

---

## 📂 Catégories

🏠 Logement · 🛒 Alimentation · 🚗 Transport · 💊 Santé · 🎬 Loisirs · 👗 Vêtements · 📱 Abonnements · 💰 Épargne · 📦 Autre

---

## 📱 Installer l'appli sur son téléphone

**iPhone (Safari)** : ouvrir le lien → bouton **Partager** → **Sur l'écran d'accueil** → **Ajouter**

**Android (Chrome)** : ouvrir le lien → menu **⋮** → **Installer l'application** (ou « Ajouter à l'écran d'accueil »)

---

## 💾 Sauvegarder et transférer ses données

Les données sont enregistrées **dans le navigateur de chaque appareil**. Pour les retrouver ailleurs, menu **⋯ Données** :

1. **💾 Sauvegarder tout** → télécharge `depenses_sauvegarde_AAAA-MM-JJ.json` (dépenses, modèle, cases cochées, budgets)
2. Envoyer ce fichier sur l'autre appareil (mail, WhatsApp, iCloud, Drive…)
3. Sur l'autre appareil : **📂 Restaurer une sauvegarde**

> Pense à faire une sauvegarde de temps en temps : si tu effaces les données de ton navigateur, elles sont perdues.

---

## 📊 Excel / Google Sheets

- **⬇ Exporter les dépenses (CSV)** : toutes les dépenses de tous les mois
- **⬆ Importer un CSV** : colonnes `Mois ; Date ; Description ; Catégorie ; Montant (€)` — les doublons sont ignorés

---

## 🛠 Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | L'application complète |
| `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png` | Installation sur l'écran d'accueil |
| `sw.js` | Fonctionnement hors connexion (change `CACHE = 'depenses-vX'` après une modification) |

Les données de l'ancienne version sont reprises automatiquement à la première ouverture.

---

## 🔒 Confidentialité

Toutes les données restent **sur ton appareil**. Rien n'est envoyé à un serveur.

---

*Fait avec ❤️ pour remplacer le carnet papier.*
