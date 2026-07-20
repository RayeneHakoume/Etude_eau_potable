# Etude_eau_potable
Une étude sur l'eau potable
Voici une proposition de fichier **README.md** complet, scannable et professionnel, rédigé de ton point de vue (Consultant Data Analyst en mission chez DWFA).

---

# 📝 README.md

# DWFA — Tableau de Bord Décisionnel pour le Financement de l'Accès à l'Eau Potable dans le Monde

## 📌 Présentation du Projet

En tant que Consultant Data Analyst au sein de l'ONG **DWFA (Drinking Water For All)**, ma mission s'inscrit dans le cadre d'une demande de financement stratégique auprès d'un bailleur de fonds international. L'objectif de l'association est de sécuriser des fonds pour investir massivement dans l'un de ses 3 domaines d'expertise :

1. **Création** de services d’accès à l’eau potable.
2. **Modernisation** de services d’accès à l’eau déjà existants.
3. **Consulting** auprès d’administrations et de gouvernements sur les politiques publiques de l’eau.

Sous la direction de Thibaut Renard (Chef de mission), ce projet consiste à concevoir un tableau de bord analytique et accessible permettant d'identifier les pays prioritaires subissant les plus fortes crises d'accès à l'eau, afin de guider l'affectation des futurs financements.

---

## 🎯 Objectifs de la Mission

### Phase 1 : Cadrage & Maquettage UI/UX

* **Sélection des indicateurs :** Synthèse des besoins du Comité et choix des KPIs pertinents basés sur les données de l'OMS et de la FAO (ex: taux d'accès à l'eau potable, stress hydrique, investissements publics, efficacité des infrastructures).
* **Design Basse Fidélité :** Création d’un document de cadrage comprenant un *blueprint* (schéma technique) et un *mockup* (maquette visuelle) pour valider l'ergonomie et l'architecture avant le développement.

### Phase 2 : Développement du Tableau de Bord (Tableau / Power BI)

Conception d'un outil décisionnel structuré autour de **3 vues clés** demandées dans le compte-rendu de la réunion de lancement :

* **Vue Globale / Macro :** Cartographie et état des lieux mondial pour identifier instantanément les pays en situation d'urgence hydrique.
* **Vue Expertise Métier :** Focus analytique croisant la situation des pays avec les 3 piliers de DWFA (Création, Modernisation, Consulting) pour déterminer *où* et *comment* agir.
* **Vue Zoom Pays / Fiche d'Identité :** Analyse granulaire et multivariée d'un pays sélectionné pour préparer les dossiers de plaidoyer destinés au bailleur de fonds.

### Phase 3 : Accessibilité & Restitution

* **Optimisation de l'accessibilité :** Choix de palettes de couleurs adaptées (inclusive pour le daltonisme), contrastes respectant les normes d'accessibilité et lecture intuitive.
* **Storytelling & Démo :** Publication du livrable final sur le Cloud (Tableau Public / Power BI Service) et préparation d'une soutenance sous forme de démonstration guidée.

---

## 📁 Structure des Données sources

Le projet exploite les données consolidées par le Data Engineer de l'ONG, enrichies par les standards de l'OMS (JMP) et de la FAO (AQUASTAT) :

* `donnees_eau_potable.zip` : Fichiers sources contenant les indicateurs d'accès à l'eau par type de population (urbaine/rurale), les données de stress hydrique et les métriques de développement par pays.
* `dictionnaire_donnees.xlsx` : Référentiel sémantique et technique des variables du dataset.

---

## 🛠️ Stack Technique

* **Outil de Business Intelligence :** **Tableau Desktop** (ou **Power BI**) pour la création des tableaux de bord et des histoires d'analyse (*Tableau Story*).
* **Cadrage Visuel :** Figma / Balsamiq (pour le mockup et le blueprint).
* **Sources de Référence :** OMS (Organisation Mondiale de la Santé), FAO (Organisation des Nations Unies pour l'alimentation et l'agriculture).
* **Déploiement :** Tableau Public / Power BI Cloud pour le partage des livrables.

---

## 🚀 Structure des Livrables à Présenter

1. **Document de cadrage préliminaire :** Présentation écrite des indicateurs sélectionnés accompagnée du mockup validé.
2. **Lien vers le Tableau de Bord Interactif :** Rapport en ligne comprenant les 3 vues dynamiques interconnectées.
3. **Démonstration Vidéo / Orale :** Parcours utilisateur guidé simulant la recherche d'un pays cible pour le bailleur de fonds.

---

## 👥 Équipe Projet

* **Thibaut Renard** : Chef de mission chez DWFA (Porteur du projet et validateur final).
* **Le Bailleur de Fonds** : Destinataire indirect de l'analyse pour l'octroi des subventions.
* **L'Équipe Data Engineering** : Fournisseur du dataset nettoyé.
* **Moi (Consultant Data Analyst)** : En charge du cadrage, du choix des KPIs, du design UX et du développement du dashboard.

---
