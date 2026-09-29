# 🏛️ Platform Pattern Catalog (PPC)

> Un catalogue interactif et un outil de conception d'architecture SI basés sur la stratégie de plateforme et les concepts de **Gregor Hohpe** (*Platform Strategy: Innovation through Harmonization*, *The Software Architect Elevator*, *Cloud Strategy*).

![Platform Pattern Catalog](https://img.shields.io/badge/Architecture-Platform%20Engineering-0284c7?style=for-the-badge)
![No-Build](https://img.shields.io/badge/Build-Single%20HTML%20File-10b981?style=for-the-badge)

---

## 📌 Présentation

**Platform Pattern Catalog** est une application web monopage (Single File Web App) conçue pour les **Architectes SI, Solution Architects et Leader Tech**. Elle permet d'explorer, de structurer et d'enseigner les principaux patterns d'architecture de plateforme moderne et d'intégration à l'échelle de l'entreprise.

---

## ✨ Fonctionnalités Principales

### 🔍 1. Catalogue de Patterns Interactif
* **Filtrage par Domaine :** Stratégie de Plateforme, Platform Engineering, Architecture & Intégration, Gouvernance & Conformité.
* **Moteur de Recherche Dynamique :** Recherche instantanée par titre, mots-clés, problèmes ou solutions.
* **Schémas Visuels SVG Intégrés :** Représentation fonctionnelle claire affichée directement sur chaque carte de pattern.
* **Fiches Détaillées (Modal) :**
  * **Problèmes & Enjeux** (mise en avant visuelle dédiée).
  * **Solution de Plateforme**.
  * **Effets Négatifs & Compromis (Trade-offs)**.
  * Citations clés et références aux ouvrages de **Gregor Hohpe**.
  * Modèle d'exportation rapide au format **Markdown** pour vos comptes-rendus ou ADR (Architecture Decision Records).

### 🛗 2. Matrice "Software Architect Elevator"
* Représentation visuelle des patterns selon les étages de l'ascenseur de l'architecte (de Gregor Hohpe) :
  * **Penthouse :** Stratégie Business & Valeur Produit.
  * **Étage Intermédiaire :** Organisation & Expérience Développeur (DX).
  * **Étage Technique :** Architecture Logicielle & Intégration.
  * **Sous-Sol (Basement) :** Infrastructure Cloud & Control Plane.

### 🛠️ 3. Composer de Blueprint d'Architecture
* **Modélisation en Couches :** Assemblez vos patterns dans les 4 couches fondamentales du SI (Developer Experience, Control Plane, Integration & Events, Data & Runtime).
* **Export Markdown Instantané :** Générez une synthèse lisible à intégrer directement dans vos Dossiers d'Architecture Technique (DAT), README de projet ou wikis d'entreprise.

### 🎨 4. Design & Expérience Utilisateur
* **Thème Clair par Défaut** reprenant l'élégance visuelle des catalogues d'architecture de référence (*Enterprise Integration Patterns*).
* **Switch Thème Sombre / Clair** personnalisable avec mémorisation de la préférence (`localStorage`).
* **Responsive & Mobile-Friendly :** Optimisé pour la consultation sur desktop, tablette et smartphone (iOS / Safari).

---

## 🚀 Prise en main & Installation

L'application est **100% Zero-Build** (sans Node.js, sans npm, sans étape de compilation).

### Option 1 : Utilisation Locale
1. Clonez ce dépôt GitHub :
   ```bash
   git clone https://github.com/votre-compte/platform-pattern-catalog.git
   ```
2. Ouvrez simplement le fichier `index.html` dans votre navigateur web préféré.

### Option 2 : Déploiement via GitHub Pages (Recommandé)
1. Allez dans les paramètres de votre dépôt GitHub (`Settings` > `Pages`).
2. Dans **Source**, sélectionnez la branche `main` (ou `master`) et le dossier `/ (root)`.
3. Cliquez sur **Save**. Votre catalogue est immédiatement en ligne !

---

## 📚 Patterns Inclus dans le Catalogue

| Pattern | Catégorie | Concept Clé |
| :--- | :--- | :--- |
| **Salade de Fruits vs Panier de Fruits** | *Platform Strategy* | L'harmonie et le contexte partagé plutôt qu'un empilement d'outils hétérogènes. |
| **Le Paradoxe de la Plateforme** | *Platform Strategy* | Restreindre le choix sur le non-différenciant pour accélérer l'innovation métier. |
| **Platform Sandwich** | *Platform Strategy* | Isoler la complexité entre un plan de contrôle cloud et un plan d'expérience développeur. |
| **Platform as a Product** | *Platform Strategy* | Traiter la plateforme comme un produit interne basé sur l'attractivité et l'adoption volontaire. |
| **Plateforme Flottante vs Coulante** | *Platform Strategy* | S'assurer que le gain de vitesse surpasse le coût de maintenance de la plateforme. |
| **La Voie Dorée (Golden Path)** | *Platform Engineering* | Proposer des autoroutes auto-service clé en main pour 80% des cas d'usage. |
| **Abstractions, Pas des Illusions** | *Platform Engineering* | Simplifier l'infrastructure sans masquer la réalité des pannes et du réseau. |
| **Smart Endpoints, Dumb Pipes** | *Architecture & Integration* | Placer la logique dans les microservices et garder le réseau de transport simple. |
| **Figuier Étrangleur (Strangler Fig)** | *Architecture & Integration* | Remplacer progressivement un monolithe legacy sans projet "Big Bang". |
| **Méfiez-vous de l'Enrobeur Funeste** | *Architecture & Integration* | Éviter la fausse modernisation par simple surcouche d'API sur du legacy bancal. |
| **Gouvernance par le Code (Policy as Code)** | *Gouvernance & Compliance* | Remplacer les comités manuels par des garde-fous automatisés dans le CI/CD. |
| **Des Mécanismes, Pas de la Magie** | *Gouvernance & Compliance* | Préférer le modèle déclaratif et explicite à la magie noire opaque. |

---

## 🛠️ Spécifications Techniques

* **HTML5 & Vanilla JavaScript (ES6+)**
* **Tailwind CSS** (via CDN)
* **Lucide Icons** (via CDN)
* Compatible avec tous les navigateurs modernes (Chrome, Firefox, Safari, Edge)

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE). Libre réutilisation et adaptation pour vos besoins d'entreprise ou formations d'architecture.
