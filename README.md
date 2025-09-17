
# SyriaTel Customer Churn Prediction

## Contexte
Ce projet vise à aider **SyriaTel**, entreprise de télécommunications, à réduire le **churn** (clients qui quittent le service).  
Le stakeholder principal est le **département Ventes et Marketing**, qui souhaite identifier les clients à risque pour mettre en place des actions ciblées.

## Objectif
Construire un **modèle de classification** capable de prédire si un client risque de quitter l’entreprise.  
Le projet permet de :
- Comprendre les comportements associés au churn.
- Identifier les clients à risque.
- Fournir des recommandations pour améliorer la fidélisation.

## Dataset
- Nom : **Syriatel Customer Churn**  
- Source : [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset)  
- Description : Données historiques des clients incluant leur statut de churn (`True`/`False`).

## Étapes du projet
1. Exploration des données (Data Understanding)  
2. Préparation des données (Data Preparation)  
3. Modélisation (Machine Learning)  
4. Évaluation et sélection du modèle final  
5. Interprétation des résultats  
6. Recommandations pour le département Ventes et Marketing

## Résultats principaux
- **Modèle final : Gradient Boosting**  
- **Recall = 0.598** → ~60% des clients à risque correctement identifiés  
- **Precision = 0.879** → parmi les clients identifiés comme churn, 88% le sont réellement  
- **F1-score = 0.712** → bon compromis Recall/Precision  

### Facteurs clés influençant le churn
- Nombre d’appels au service client  
- Total facturé en journée  
- Absence de plan international  
- Durée totale des appels en journée et soirée  

###  Conclusion
Le modèle développé constitue un outil d’aide à la décision pour la **réduction du churn chez SyriaTel**.  
En mettant en œuvre les recommandations proposées, l’entreprise peut : 
- Cibler les clients à risque,
- Optimiser les actions marketing et de fidélisation,
- Diminuer le taux de résiliation.  
- Améliorer l’expérience client.  
- Consolider sa compétitivité sur le marché des télécommunications.



