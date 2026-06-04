# HR Analytics Dashboard — Power BI

## 🇫🇷 Version française

## Contexte

Ce projet consiste à construire un tableau de bord RH interactif avec Power BI à partir d’un jeu de données sur les salariés d’une entreprise.

L’objectif est d’analyser les départs salariés, les salaires, les profils employés et les facteurs de risque associés au départ.

## Objectifs

- suivre les principaux indicateurs RH ;
- analyser la part des salariés partis selon différents profils ;
- comparer les salaires selon les postes, départements et statuts ;
- identifier des profils potentiellement plus exposés au départ ;
- créer un dashboard interactif avec Power BI.

## Outils utilisés

- Power BI Desktop
- Power Query
- DAX
- GitHub

## Compétences démontrées

- import et préparation de données ;
- nettoyage avec Power Query ;
- création de mesures DAX ;
- création de colonnes calculées ;
- conception d’un dashboard interactif ;
- storytelling data ;
- création d’indicateurs RH.

## Données

Dataset : IBM HR Analytics Employee Attrition & Performance.

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Structure du dashboard

Le rapport Power BI est composé de 4 pages :

1. Vue d’ensemble RH
2. Analyse des départs salariés
3. Salaires et profils employés
4. Profil RH et facteurs de risque

## Aperçu du dashboard

### Vue d’ensemble RH

<img width="1514" height="822" alt="vue_ensemble" src="https://github.com/user-attachments/assets/29f26ace-44fe-4122-bafc-f5f7cf950448" />

### Analyse des départs salariés

<img width="1508" height="823" alt="analyse_departs" src="https://github.com/user-attachments/assets/4a7022aa-84a2-4047-b72b-ace89fb0d951" />


### Salaires et profils employés

<img width="1505" height="819" alt="salaires_profils" src="https://github.com/user-attachments/assets/2202c2f9-309f-4353-8eb5-ba208ba99358" />


### Profil RH et facteurs de risque

<img width="1495" height="820" alt="facteurs_risque" src="https://github.com/user-attachments/assets/fa583f6a-f87a-4d6e-b0e8-5ea719e941cc" />


## Indicateurs clés

- Effectif total
- Nombre de départs
- Taux de départ
- Salaire mensuel moyen
- Ancienneté moyenne
- Taux de départ par poste
- Taux de départ par ancienneté
- Taux de départ par niveau de risque

## Note de lecture

Les graphiques de la page “Analyse des départs salariés” affichent la part des salariés partis au sein de chaque groupe.

Par exemple, un taux de 30 % pour les salariés avec heures supplémentaires signifie que 30 % des salariés de ce groupe ont quitté l’entreprise.

Ces pourcentages ne représentent donc pas une répartition globale des départs et ne sont pas destinés à totaliser 100 %.

## Score de risque RH

Un score de risque simple a été construit à partir de plusieurs facteurs :

- heures supplémentaires ;
- faible satisfaction ;
- faible ancienneté ;
- déplacements professionnels fréquents.

Ce score permet de classer les salariés en trois niveaux de risque : faible, modéré et élevé.

## Conclusion

Ce projet démontre l’utilisation de Power BI pour construire un dashboard RH interactif, depuis la préparation des données jusqu’à la création d’indicateurs, de visualisations et d’une lecture orientée aide à la décision.

---

# 🇬🇧 English version

## Context

This project consists of building an interactive HR dashboard with Power BI using an employee dataset.

The goal is to analyze employee departures, salaries, workforce profiles and potential risk factors associated with employee attrition.

## Objectives

- monitor key HR indicators;
- analyze the share of employees who left across different profiles;
- compare salaries by role, department and employee status;
- identify profiles potentially more exposed to departure;
- build an interactive dashboard with Power BI.

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- GitHub

## Skills Demonstrated

- data import and preparation;
- data cleaning with Power Query;
- DAX measures;
- calculated columns;
- interactive dashboard design;
- data storytelling;
- HR KPI creation.

## Data

Dataset : IBM HR Analytics Employee Attrition & Performance.

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Dashboard Structure

The Power BI report contains 4 pages:

1. HR Overview
2. Employee Departure Analysis
3. Salaries and Employee Profiles
4. HR Profile and Risk Factors

## Dashboard Preview

### HR Overview

<img width="1514" height="822" alt="vue_ensemble" src="https://github.com/user-attachments/assets/29f26ace-44fe-4122-bafc-f5f7cf950448" />


### Employee Departure Analysis

<img width="1508" height="823" alt="analyse_departs" src="https://github.com/user-attachments/assets/4a7022aa-84a2-4047-b72b-ace89fb0d951" />


### Salaries and Employee Profiles

<img width="1505" height="819" alt="salaires_profils" src="https://github.com/user-attachments/assets/2202c2f9-309f-4353-8eb5-ba208ba99358" />

### HR Profile and Risk Factors

<img width="1495" height="820" alt="facteurs_risque" src="https://github.com/user-attachments/assets/fa583f6a-f87a-4d6e-b0e8-5ea719e941cc" />


## Key Indicators

- Total employees
- Number of departures
- Departure rate
- Average monthly salary
- Average tenure
- Departure rate by role
- Departure rate by tenure
- Departure rate by risk level

## Reading Note

The charts on the “Employee Departure Analysis” page show the share of employees who left within each group.

For example, a 30% departure rate for employees working overtime means that 30% of employees in that group left the company.

These percentages do not represent the overall distribution of departures and are not expected to add up to 100%.

## HR Risk Score

A simple risk score was created using several factors:

- overtime;
- low satisfaction;
- low tenure;
- frequent business travel.

This score classifies employees into three risk levels: low, moderate and high.

## Conclusion

This project demonstrates the use of Power BI to build an interactive HR dashboard, from data preparation to KPI creation, visual reporting and decision-oriented analysis.
