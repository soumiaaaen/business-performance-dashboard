# 📊 Interactive Business Performance Dashboard — Power BI

Un tableau de bord interactif Power BI pour le suivi en temps réel des performances commerciales d'une entreprise (chiffre d'affaires, ventes par produit/région/catégorie, rentabilité, tendances), réalisé dans le cadre du projet académique *"Mise en place de tableau de bord interactif pour le suivi des performances d'une entreprise"*.

---

## 🎯 Objectifs du projet

Développer un tableau de bord permettant de répondre à des questions stratégiques :
- L'entreprise est-elle en croissance ?
- Quels produits ou régions sont les plus rentables ?
- Où observe-t-on une baisse de performance ?
- Les objectifs sont-ils atteints ?

Le tableau de bord couvre :
- 📈 Le suivi en temps réel des indicateurs clés de performance (KPIs)
- 🔍 L'analyse multidimensionnelle des ventes et performances financières
- 🎯 La comparaison des performances avec les objectifs fixés
- 🧭 L'aide à la prise de décision stratégique
- 🤖 L'intégration d'analyses prédictives simples

---

## 🗂️ Structure du dépôt

```
business-performance-dashboard/
│
├── data/
│   └── Superstore_Data.csv          # Jeu de données source (ventes, produits, régions...)
│
├── dashboard/
│   └── Business_Dashboard.pbix      # Fichier Power BI (2 pages : vue d'ensemble + prévisions/segmentation)
│
├── docs/
│   ├── project_description.pdf      
│   └── screenshots/                 # Captures d'écran des pages du dashboard
│
└── README.md                        # Ce fichier
```

---

## 🗃️ Données

**Source :** [Sample Superstore Dataset](https://www.kaggle.com/code/hamdy17298/sample-superstore/notebook) (données de ventes retail, format CSV)

| Caractéristique | Détail |
|---|---|
| Lignes | 9 994 commandes |
| Période couverte | 2014 – 2017 |
| Colonnes | 21 (ID commande, dates, client, segment, région, produit, catégorie, ventes, quantité, remise, profit...) |
| Régions | Central, East, South, West |
| Catégories | Furniture, Office Supplies, Technology (17 sous-catégories) |
| Chiffre d'affaires total | ≈ 2 297 200 $ |
| Profit total | ≈ 286 397 $ |

---

## 📐 Modélisation & KPIs suivis

- **Chiffre d'affaires** global, par période, produit, catégorie et région
- **Profit / Marge** et rentabilité par segment
- **Quantité vendue** et évolution des ventes (tendances mensuelles/annuelles)
- **Top produits / sous-catégories** les plus performants et les moins rentables
- **Répartition géographique** des ventes (carte par région/État)
- **Comparaison YoY** (Year-over-Year) et suivi d'objectifs

## 🖱️ Fonctionnalités interactives

- Filtres dynamiques par **année, région, catégorie, segment client**
- **Drill-down** sur les KPIs (Année → Trimestre → Mois → Jour)
- Cartes géographiques cliquables
- Tableaux dynamiques triables

---

## 🛠️ Outils & technologies

| Outil | Usage |
|---|---|
| **Power BI Desktop** | Modélisation, DAX, visualisations, tableau de bord |
| **Power Query** | Nettoyage et transformation des données (dates, valeurs manquantes, colonnes calculées) |
| **DAX** | Mesures et indicateurs calculés (CA, marge, croissance %, etc.) |
| **CSV** | Source de données brute |

---

## 🚀 Comment utiliser ce dashboard

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/soumiaaaen/business-performance-dashboard.git
   ```
2. Ouvrir `dashboard/Business_Dashboard.pbix` avec **Power BI Desktop** .
3. Si Power BI demande de reconnecter la source de données, pointer vers `data/Superstore_Data.csv`.
4. Rafraîchir les données (`Accueil > Actualiser`) et explorer le rapport.

---

## 📸 Aperçu

```
<img width="878" height="386" alt="img4" src="https://github.com/user-attachments/assets/c8f05faf-440d-499d-91d5-ccfabebb5dfd" />
<img width="874" height="382" alt="img3" src="https://github.com/user-attachments/assets/d313a4c7-c305-424a-b053-aa662477859d" />
<img width="878" height="388" alt="img2" src="https://github.com/user-attachments/assets/a9a1ffcd-1b4e-4753-b24e-4db658c055a1" />
<img width="878" height="386" alt="img1" src="https://github.com/user-attachments/assets/f9e38b24-ec3e-4453-94c5-0d1346958d59" />

```
## 🤖 Composante IA intégrée
 
Le rapport `.pbix` est organisé en **2 pages** :
 
| Page | Contenu |
|---|---|
| **Page 1 — Vue d'ensemble** | KPIs, CA par période/produit/région, tendances, carte géographique, filtres dynamiques |
| **Page 2 — Prévisions & Segmentation** | Prévision des ventes + segmentation client (clustering) |
 
Ces deux fonctionnalités prédictives ont été implémentées **nativement dans Power BI** (DAX + visuels IA intégrés) :
 
- **Prévision des ventes** — projection du chiffre d'affaires sur les prochains mois via la fonctionnalité de forecasting native de Power BI (visuel courbe avec intervalle de confiance).
- **Segmentation client** — regroupement des clients par comportement d'achat à l'aide des visuels IA de Power BI (clustering).
- 
---

## 👤 Auteur

Projet réalisé en équipe de 4 dans le cadre du module *DataWareHouse* 
Encadré par : Prof. Meryem Fakhouri Amr.
 
| Nom | GitHub |
|---|---|
| AMERKAD SOUMIA | [@username]([https://github.com/username](https://github.com/soumiaaaen)) |
| _Nom Prénom_ | [@username](https://github.com/username) |
| _Nom Prénom_ | [@username](https://github.com/username) |
| _Nom Prénom_ | [@username](https://github.com/username) |

