# # PAP-Plateforme

Outil de pré-consultation et d’aide à la prescription d’activité physique

---

## Description

PAP-Plateforme est un outil mono-fichier HTML destiné :

- aux patients, pour l’auto-évaluation de leur niveau d’activité physique
- aux professionnels de santé, comme support d’aide à la consultation

Il permet :

- L’évaluation du niveau d’activité physique (GPAQ – OMS / Marshall)
- Le calcul des MET-min/semaine
- La détermination du stade motivationnel
- L’auto-évaluation de l’importance et de la confiance (EVA 0–10)
- L’aide à la structuration de la consultation
- L’assistance à la rédaction de comptes rendus de consultation (CRC)

Les résultats sont destinés à être utilisés en consultation médicale.

Aucune donnée n’est stockée.

---

## Architecture du projet

Le projet repose sur trois niveaux distincts :

### 1. Logique clinique (gelée)

Les éléments suivants sont strictement verrouillés :

- Questionnaires (GPAQ, Marshall)
- Calculs et seuils
- Logique motivationnelle
- Ordre des étapes
- Structure des résultats

Voir :
**PROTOCOLE_STABILITE_CLINIQUE_PAP.md**

---

### 2. Stabilité technique (anti-régression)

Toute modification technique suit un protocole DSR (Debug Sans Régression) visant à :

- Corriger sans perte fonctionnelle
- Éviter toute régression visible ou invisible
- Maintenir l’intégrité des parcours validés

Voir :
**PROTOCOLE_DSR_PAP.md**

---

### 3. Évolutions

Les évolutions nécessitent une validation explicite afin de garantir la cohérence clinique et technique du projet.

---

## Caractéristiques techniques

- Application mono-fichier HTML
- Exécution locale dans le navigateur
- Aucune base de données
- Aucun stockage persistant

---

## Positionnement

PAP-Plateforme est :

- un outil d’évaluation
- un support d’aide à la décision clinique
- un outil d’accompagnement à la consultation
- un support de structuration et de rédaction

Il ne remplace pas le jugement clinique du professionnel de santé.

---

## Licence

### Code source
Ce projet est distribué sous licence GNU GPL v3.

Toute réutilisation, modification ou distribution doit :
- conserver cette licence
- mentionner l’auteur original

### Contenu médical (guide, fiches, documents associés)
Le contenu est distribué sous licence Creative Commons CC BY-NC-SA 4.0.

Vous êtes autorisé à :
- partager
- adapter

À condition de :
- citer l’auteur
- ne pas en faire un usage commercial
- partager les modifications sous les mêmes conditions

---

© Antoine Bosquet – 2026 – Tous droits réservés

---





