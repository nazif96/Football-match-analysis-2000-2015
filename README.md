# ⚽ PySpark Football Data Analysis
Ce projet vise à analyser les performances des équipes de Bundesliga entre les saisons 2000 et 2015 à l’aide de PySpark, une solution Big Data adaptée au traitement de données volumineuses.

## 🎯 Objectifs :
Nettoyer et transformer les données de matchs à l’aide de PySpark

Créer des indicateurs : buts marqués, victoires, défaites, matchs nuls

Analyser les performances par saison et par équipe

Générer un tableau de résumé avec le classement, les différentiels de buts, et les taux de victoire

## 🛠️ Outils utilisés :
PySpark pour le traitement distribué

pandas pour l’affichage final des résultats

Google Colab pour l’environnement d’exécution

📊 Extrait des résultats :

Résumé des performances Bundesliga (2000-2015)

Ce tableau présente les statistiques clés (victoires, buts, classement) des champions de Bundesliga par saison.

📈 **Extrait des résultats :**

```
| Team           | Season | GoalsScored | GoalsAgainst | Win | Loss | Tie | GoalDifferentials | WinPercentage | TeamPosition |
|----------------|--------|-------------|---------------|-----|------|-----|-------------------|---------------|--------------|
| Bayern Munich  | 2000   | 62          | 37            | 19  | 9    | 6   | 25                | 55.88         | 1            |
| Leverkusen     | 2001   | 77          | 38            | 21  | 7    | 6   | 39                | 61.76         | 1            |
| Bayern Munich  | 2002   | 70          | 25            | 23  | 5    | 6   | 45                | 67.65         | 1            |
| Werder Bremen  | 2003   | 79          | 38            | 22  | 4    | 8   | 41                | 64.71         | 1            |
| Bayern Munich  | 2004   | 75          | 33            | 24  | 5    | 5   | 42                | 70.59         | 1            |
| Bayern Munich  | 2005   | 67          | 32            | 22  | 3    | 9   | 35                | 64.71         | 1            |
| Stuttgart      | 2006   | 61          | 37            | 21  | 6    | 7   | 24                | 61.76         | 1            |
| Bayern Munich  | 2007   | 68          | 21            | 22  | 2    | 10  | 47                | 64.71         | 1            |
| Wolfsburg      | 2008   | 80          | 41            | 21  | 7    | 6   | 39                | 61.76         | 1            |
| Bayern Munich  | 2009   | 72          | 31            | 20  | 4    | 10  | 41                | 58.82         | 1            |
| Dortmund       | 2010   | 67          | 22            | 23  | 5    | 6   | 45                | 67.65         | 1            |
| Dortmund       | 2011   | 80          | 25            | 25  | 3    | 6   | 55                | 73.53         | 1            |
| Bayern Munich  | 2012   | 98          | 18            | 29  | 1    | 4   | 80                | 85.29         | 1            |
| Bayern Munich  | 2013   | 94          | 23            | 29  | 2    | 3   | 71                | 85.29         | 1            |
| Bayern Munich  | 2014   | 80          | 18            | 25  | 5    | 4   | 62                | 73.53         | 1            |
| Bayern Munich  | 2015   | 80          | 17            | 28  | 2    | 4   | 63                | 82.35         | 1            |

``` 


## 📈 Analyse des tendances
Équipe dominante : Bayern Munich ressort comme la plus régulière avec une domination constante.

Meilleure performance : 2012 et 2013 avec un taux de victoire dépassant les 85%.

Autres prétendants : Dortmund et Wolfsburg montrent des pics de performance ponctuels.


## ✅ Conclusion
Ce tableau synthétique met en lumière la supériorité du Bayern Munich sur la période 2000-2015. Une analyse plus fine pourrait inclure des facteurs contextuels comme les transferts, blessures ou changements de coach.