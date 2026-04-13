# ARCHITECTURE CLINIQUE PAP

## 1. Objectif

Définir les principes de structuration des modules cliniques du projet PAP.

---

## 2. Principe général

Le système repose sur une aide à la décision clinique structurée.

L’outil :

* organise les informations
* structure le raisonnement clinique
* propose des éléments d’aide

Le médecin :

* reste décisionnaire
* adapte au contexte réel du patient

---

## 3. Contraintes générales

* Outil non considéré comme dispositif médical
* Aucune automatisation décisionnelle
* Le médecin garde la décision finale
* Le contenu est une aide cognitive structurée

---

## 4. Workflow clinique

Le parcours doit respecter les étapes suivantes :

1. Évaluation activité physique (GPAQ / Marshall)
2. Évaluation motivationnelle
3. Stratification du risque
4. Structuration de la décision
5. Génération du compte rendu

---

## 5. Logique de structuration

Les éléments doivent être présentés sous forme conditionnelle pour structurer le raisonnement :

IF condition → THEN éléments à considérer / options / vigilance

⚠️ Ces éléments :

* ne constituent pas une décision automatique
* ne sont pas prescriptifs
* doivent être interprétés par le médecin

---

## 6. Structure des modules pathologies

Chaque module doit inclure :

### 6.1 Contraintes

* contre-indications
* limitations

### 6.2 Adaptations

* type d’activité
* intensité
* progression

### 6.3 Conditions spécifiques

* situations cliniques particulières

### 6.4 Règles de structuration

* logique IF → THEN (aide au raisonnement)

---

## 7. Données cliniques

Les données doivent être :

* structurées
* cohérentes
* exploitables dans le système

---

## 8. Générateur de CRC

Le générateur doit produire :

* une restitution fidèle des données
* une cohérence avec les éléments structurés
* une aide à la rédaction

---

## 9. Interdits

* Pas de décision automatique
* Pas de recommandation imposée
* Pas de scoring décisionnel automatisé
* Pas de recommandation individualisée fermée
* Pas de contenu purement descriptif

---

## 10. Règle de conception

Chaque élément doit contribuer à :

* structurer le raisonnement
* faciliter la décision
* réduire la charge cognitive

---

FIN
