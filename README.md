# TD-Hospital-Exploration

Automated decision-making systems play a significant role in our lives, and understanding how these models work is crucial. Modern AI and machine learning algorithms often pose challenges
in explaining their outcomes, leading to the "black box" problem. This report addresses the need to gain insights into the survival factors of patients and improve the transparency of the decision making process.

# Description
TD Hospital has sought assistance in rectifying issues with their patient data, accumulated over several years, without clear documentation of flaws. The objective is to understand the information contained in the dataset and identify the factors contributing to patient survival. This process may involve making modifications to the dataset and utilizing machine learning techniques to predict outcomes.

We systematically trained and fine-tuned a variety of machine learning models, rigorously assessing their performance. By comparing the accuracies of these models, we identified and
selected the best-performing model for our analysis.

| MODEL | ACCURACY | BEST PARAMETER |
|----------|----------|----------|
| Random Forest | 0.87 | max_depth: None, n_estimaters: 100 |
| Ada Boost | 0.84 | learning_rate: 1.0, n_estimaters: 50 |
| Gradient Boosting | 0.87 | learning_rate: 0.1, n_estimators: 100 |
| Bagging | 0.87 | max_samples: 0.6, n_estimators: 200 |
| CatBoostClassifier | 0.94 | Iterations=100, verbose=0 |
