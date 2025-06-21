# Clustering Individuals Based on Food Preferences

## Problem Statement
Cluster individuals into different groups (e.g., Healthy Eaters, Junk Food Lovers) based on their food habits and lifestyle choices using unsupervised machine learning.

## Dataset Description
The data was collected using a Google Form. Each respondent provided:
- Sleep time (in hours)
- Interest in healthy eating (scale of 1–5)
- Frequency of eating outside food (categorical: Low, Medium, High)
- Daily water intake (in litres)
- Food preference (Veg / Non-Veg )

The dataset was preprocessed to encode categorical variables and normalize numerical values for effective clustering.

## Machine Learning Approach

- **Algorithm Used**: K-Means Clustering
- **No. of Clusters**: 3 (determined using the Elbow Method)
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, joblib

## 📈 Visualizations

-  **Elbow Method**: Helps identify the optimal number of clusters.
-  **Scatter Plot**: Shows clustering based on Sleep Hours vs Water Intake.


## Output Sample
The model assigns each individual to a cluster. For example:

```
| SleepHours | WaterIntake | Cluster |
|------------|-------------|---------|
|     7      |     3       |    0    |
|     5      |     3       |    1    |
|     8      |     1       |    0    |
```

## Conclusion
The K-Means model successfully grouped individuals based on similarities in their food and lifestyle habits. These clusters can be used to offer targeted health recommendations.

## Team Info
**Team Name**: TEAM 14- DTM  
**Department**: Computer Science and Engineering  
**Institution**: Kamaraj College of Engineering and Technology

##  Submission Format
Please refer to `form_link.txt` and `problem_statement.txt` for project metadata.
