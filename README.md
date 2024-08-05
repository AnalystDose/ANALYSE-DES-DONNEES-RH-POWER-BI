# ANALYSE-DES-DONNEES-RH-POWER-BI
Analyse des données des aspects cruciaux des ressources humaines (départs, formations, recrutements, performances)

![Capture d'écran 2024-08-05 114625](https://github.com/user-attachments/assets/41bb814e-bca8-45c1-8c32-0ea3d6f9d32c)
## Description

Dans un environnement économique et concurrentiel en constante évolution, la gestion efficace des ressources humaines est devenue cruciale pour les entreprises cherchant à maintenir leur compétitivité. Les entreprises doivent non seulement attirer et retenir les meilleurs talents, mais aussi optimiser les performances de leurs employés. Fournir à l'entreprise un outil puissant(POWER BI) pour visualiser, analyser et interpréter les données relatives aux employés facilitera ainsi la prise de décision stratégique. 

## Source et aperçu des données🚀
L'ensemble de données a été obtenu sur le site web Bi Learner  qui  propose des ensembles de données du monde réel.  
L'ensemble de données contient 7 fichiers Excel (Attendance, Business Unit,  Employee, Survey, Performance, Recruitment, Training ) qui font référence aux informations des ressources humaines d’une entreprise.

## Modelisation ⚡
![Capture d'écran 2024-07-03 115315](https://github.com/user-attachments/assets/1319a29f-349d-4d21-a148-66ae99cb7270)

Nous avons extrait dans la base de données les tables:
- Attendance
- Business Unit
- Employee
- Survey
- Performance
- Recruitment
- Training

À cela, s'ajoute la table temps (calendar) pour aboutir à un model en constellation.
 
## Quelques indicateurs clés ⚡

- **Rotation 12D mois (Taux de rotation sur 12 mois) :** permet d’évaluer la stabilité et la rétention des employés au sein de l’entreprise. Un taux de rotation élevé peut indiquer des problèmes de satisfaction au travail, de gestion ou de conditions de travail, nécessitant des interventions pour améliorer la rétention des employés.

- **Taux d’embauche vs AD (Taux d’embauche par rapport à l’année dernière) :** Comparer le taux d’embauche actuel avec celui de l’année précédente aide à évaluer l’efficacité des stratégies de recrutement et la trajectoire de croissance de l’entreprise.

- **Embauche et Départ 12D mois (Embauches et départs au cours des 12 derniers mois) : ** Suivre les embauches et les départs sur une année donne une image claire de la dynamique de la main-d'œuvre et peut indiquer si l’entreprise est en croissance ou connaît un taux d’attrition élevé.

- **%Nombre employé VS AD (Évolution du nombre d’employés par rapport à l’année dernière):** Suivre les changements dans le nombre total d’employés par rapport à l’année précédente aide à mesurer la croissance ou la contraction globale de la main-d'œuvre.
