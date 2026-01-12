# STEP 7 – Systèmes d’Automatisation Industrielle (Ladder)

## 📌 Présentation du projet
Ce dépôt regroupe plusieurs **applications d’automatisation industrielle** développées à l’aide du
logiciel **STEP 7 (Siemens SIMATIC S7)** et programmées en **langage Ladder (LAD)**.

Ces projets ont été réalisés dans le cadre de **travaux pratiques** en automatisation industrielle,
avec pour objectifs l’étude des **logiques de commande**, des **dispositifs de sécurité** et la
**validation par simulation**.

L’ensemble des systèmes a été conçu, programmé et testé à l’aide des outils de simulation intégrés
à STEP 7.

---

## 🎯 Objectifs pédagogiques
- Comprendre les principes de base des **Automates Programmables Industriels (API)**
- Concevoir des systèmes de commande à partir d’un **cahier des charges**
- Mettre en œuvre des logiques d’automatisation en **Ladder (IEC 61131-3)**
- Simuler et valider le comportement des programmes API
- Appliquer des concepts industriels tels que :
  - l’auto-maintien
  - les temporisations
  - les compteurs
  - les verrouillages électriques

---

## 🧠 Systèmes réalisés

### 🔔 TP4 – Système d’alarme
Système d’alarme avec détection d’intrusion comprenant :
- Activation générale du système par commutateur
- Détection de présence (caméra simulée)
- Détection d’ouverture de porte et de fenêtres
- Signalisation visuelle par LED verte et LED rouge
- Signalisation sonore par buzzer avec auto-maintien
- Réinitialisation manuelle de l’alarme

---

### ⚙️ TP5 – Démarrage étoile / triangle
Commande d’un moteur asynchrone triphasé :
- Démarrage en couplage étoile
- Passage automatique en couplage triangle après 5 secondes
- Commande du sens de rotation (droite / gauche)
- Verrouillage électrique pour la sécurité
- Arrêt du moteur par bouton dédié
- Maintien d’état à l’aide de bascules SR

---

### 🚧 TP2 – Système d’automatisation de tunnel
Système automatisé de gestion du trafic dans un tunnel :
- Détection de véhicules par capteurs
- Commande automatique de la barrière
- Mise en marche du ventilateur de ventilation
- Signalisation routière par LED
- Commande séquentielle des moteurs en fonction de la position du véhicule
- Temporisation de sécurité avant la montée ou la descente de la barrière

---

## 🧰 Matériel utilisé (simulation)
- **Automate** : Siemens SIMATIC S7
- **Entrées** :
  - Boutons poussoirs
  - Commutateurs
  - Capteurs
- **Sorties** :
  - Moteurs
  - Voyants lumineux (LED)
  - Buzzer d’alarme
  - Actionneur de barrière

---

## 🖥️ Environnement logiciel
- **STEP 7 (SIMATIC Manager)**
- Langage Ladder (LAD)
- Outils de simulation et de visualisation intégrés

---

## 🧪 Simulation et tests
Les systèmes ont été validés par simulation en :
- Forçant manuellement les entrées
- Observant le comportement des sorties
- Vérifiant les conditions de sécurité
- Testant les temporisations, compteurs et auto-maintiens
- Contrôlant la conformité avec les cahiers des charges

---

## 📄 Documentation
Le rapport technique complet est disponible dans le dossier et comprend :
- Les cahiers des charges
- Les tables des mnémoniques
- Les réseaux en langage Ladder
- Les étapes et résultats de simulation

---

## ⚠️ Portée du projet et remarques
Ce travail a été réalisé dans un cadre pédagogique et sous des contraintes de temps définies.
Les fonctionnalités principales attendues ont été implémentées et validées par simulation.

Certaines parties de la logique Ladder pourraient toutefois être optimisées ou restructurées afin
d’améliorer la lisibilité, la modularité ou l’extensibilité du programme. Ces points constituent des
axes d’amélioration et n’altèrent pas les objectifs pédagogiques du projet.

---

## 🛠️ Compétences mises en œuvre
- Programmation d’API (IEC 61131-3)
- Langage Ladder (LAD)
- Automatismes industriels
- Commande de moteurs (étoile / triangle)
- Systèmes d’alarme et de sécurité
- Simulation et mise au point de programmes API
- Rédaction de documentation technique

---

## 👤 Auteurs
Travaux pratiques réalisés dans le cadre d’une formation en **Automatisation Industrielle**

**Étudiants** :
- EL HADY Salma  
- EL KHANCHAF Zakaria  
- MTAHTAH Wissal  
- ZOUBAI Douha  

**Encadré par** :  
Monsieur Haddi
