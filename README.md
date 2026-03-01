# 🏥 Healthcare Dashboard - Analyse de la Performance Hospitalière

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📌 Contexte

Dans un secteur de la santé en constante évolution, la capacité à analyser et interpréter les données hospitalières est devenue un enjeu stratégique majeur. Ce projet vise à transformer des données brutes de santé en insights actionnables pour aider les décideurs à optimiser la gestion hospitalière.

---

## 🎯 Objectif

Concevoir un dashboard interactif complet permettant d'analyser la performance d'un réseau hospitalier sous **4 angles complémentaires** : vue globale, financier, patients et pathologies.

---

## 🗂️ Source des données

Les données proviennent d'un dataset public disponible sur Kaggle :

🔗 [Healthcare Dataset - Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset?resource=download)

Le dataset contient **+10 000 patients** sur plusieurs années avec des informations sur :
- Les admissions et types d'admission
- Les pathologies diagnostiquées
- Les assurances des patients
- Les hôpitaux et médecins
- La facturation et les recettes

---

## 📊 Les pages du Dashboard

### 1️⃣ Vue Générale
Vue d'ensemble rapide avec les KPI's clés :
- Nombre de patients
- Recettes totales
- Montant moyen par patient
- Âge moyen
- Durée moyenne de séjour
- Répartition des patients par assurance (donut)
- Évolution du nombre de patients par mois (courbe)
- Recettes par hôpital (barres horizontales)
- Analyse détaillée par pathologie (tableau)

### 2️⃣ Analyse Financière
Suivi des performances financières :
- Recettes totales, moyennes, journalières, max et min
- Recettes par mois avec comparaison année précédente (YoY)
- Recettes par type d'admission
- Montant moyen par pathologie
- Répartition des recettes par assurance

### 3️⃣ Analyse Patients
Compréhension du profil démographique des patients :
- Nombre de patients, âge moyen, âge max/min, durée de séjour
- Répartition par tranche d'âge
- Répartition par genre (donut)
- Répartition par groupe sanguin
- Évolution YoY du nombre de patients par mois

### 4️⃣ Analyse Pathologies
Identification et analyse des pathologies :
- Nombre de patients et pathologies, recettes, durée de séjour
- Évolution des pathologies : année en cours vs année précédente
- Durée de séjour vs montant moyen par pathologie (scatter plot)
- Pathologies par nombre de patients (treemap)
- Contribution de chaque pathologie aux recettes (waterfall)

---

## 💡 Insights Clés

| Insight | Valeur |
|---------|--------|
| 🦠 Pathologie la plus fréquente | OBESITY (1 850 patients) |
| 💰 Type d'admission le plus rentable | EMERGENCY (94M€) |
| 👥 Répartition Hommes/Femmes | 49,79% / 50,21% |
| 🏥 Hôpital le plus performant | JOHNSON INC (0,36M€) |
| 👴 Tranche d'âge majoritaire | 50-70 ans (3 300 patients) |
| 📅 Durée moyenne de séjour | 15,49 jours |

---

## 🛠️ Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| **Power BI Desktop** | Visualisation et création du dashboard |
| **DAX** | Mesures calculées (YoY, moyennes, KPI's) |
| **Power Query (M)** | Transformation et nettoyage des données |

---

## 📁 Structure du projet

```
healthcare-dashboard/
│
├── Project_healthcare_Dashboard.pbix   # Fichier Power BI principal
├── README.md                           # Documentation du projet
└── screenshots/                        # Captures d'écran du dashboard
    ├── vue_generale.png
    ├── analyse_financiere.png
    ├── analyse_patients.png
    └── analyse_pathologies.png
```

---

## 🚀 Comment utiliser ce projet

1. Téléchargez et installez **Power BI Desktop** (gratuit)
2. Clonez ce repository
3. Ouvrez le fichier `Project_healthcare_Dashboard.pbix` dans Power BI Desktop
4. Explorez les différentes pages du dashboard

---

## 👤 Auteur

**Votre Nom**
🔗 [LinkedIn](https://www.linkedin.com/in/votre-profil)

---

> 💼 *Projet réalisé dans le cadre d'une recherche de stage en Data Analytics*
