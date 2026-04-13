# PAP-Plateforme

Outil de pré-consultation et d’aide à la prescription d’activité physique

---

## 🎯 Objectif

PAP-Plateforme est un outil conçu pour :

* préparer la consultation médicale
* structurer l’évaluation de l’activité physique
* faciliter la prescription d’activité physique

Il s’adresse :

* aux patients (auto-évaluation)
* aux professionnels de santé (aide à la décision et à la rédaction)

---

## 🧩 Fonctionnalités

L’outil permet :

* Évaluation du niveau d’activité physique (GPAQ – OMS / Marshall)
* Calcul des MET-min/semaine
* Détermination du stade motivationnel
* Évaluation de l’importance et de la confiance (EVA 0–10)
* Structuration de la consultation
* Génération de comptes rendus de consultation (CRC)

Les résultats sont destinés à être utilisés en consultation médicale.

---

## 🔒 Données & confidentialité

* Aucune donnée n’est stockée
* Aucune transmission automatique
* Aucune base de données
* Exécution locale uniquement

Les données restent sous le contrôle exclusif de l’utilisateur.

---

## 🏗️ Architecture du projet

Le projet repose sur trois niveaux :

### 1. Logique clinique (gelée)

* Questionnaires (GPAQ, Marshall)
* Calculs et seuils
* Logique motivationnelle
* Ordre des étapes
* Données cliniques fondamentales

→ Voir : `PROTOCOLE_STABILITE_CLINIQUE_PAP.md`

---

### 2. Stabilité technique (DSR)

Toute modification suit un protocole visant à :

* éviter les régressions
* maintenir l’intégrité fonctionnelle
* garantir la cohérence du système

→ Voir : `PROTOCOLE_DSR_PAP.md`

---

### 3. Architecture clinique

Les modules sont structurés selon une logique décisionnelle (conditions → actions).

→ Voir : `ARCHITECTURE.md`

---

## ⚙️ Caractéristiques techniques

* Application HTML (exécution navigateur)
* Fonctionnement local
* Sans base de données
* Sans stockage persistant

---

## 🧠 Positionnement

PAP-Plateforme est :

* un outil d’évaluation
* un support d’aide à la décision clinique
* un outil de structuration de la consultation

Il ne remplace pas le jugement clinique du professionnel de santé.

---

## 📜 Licence

### Code source

Licence GNU GPL v3

### Contenu médical

Licence Creative Commons CC BY-NC-SA 4.0

Conditions :

* attribution obligatoire
* usage non commercial
* partage dans les mêmes conditions

---

© Antoine Bosquet – 2026
