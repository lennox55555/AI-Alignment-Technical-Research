# Interpretable Machine Learning with Heart Attack Risk Prediction

Welcome to the **Heart Attack Prediction** repository, where I focus on using interpretable machine learning models to predict heart attack risk based on patient data. The primary goal of this project is to explore and compare models that maintain both high performance and interpretability. I used a heart attack dataset and applied models like **C45TreeClassifier**, **RuleFitClassifier**, and **TaoTreeClassifier** to derive insights from the data.

## Insights from the Analysis

- **C45 Tree Classifier**: This classic decision tree algorithm provides a deep tree with many nodes, offering insight into the various decision paths that lead to a prediction of heart attack risk. Its structure, however, can become complex, making it harder to interpret when the tree grows large.
  
- **RuleFit Classifier**: By generating clear IF-THEN rules, the RuleFit model offers a more interpretable approach to predicting heart attack risk. This model highlights key risk factors such as high cholesterol or lack of exercise through simple rules.

- **TAO Tree Classifier**: The TaoTreeClassifier optimizes the tree structure by reducing unnecessary splits, leading to a more compact and efficient model. This approach provides a balance between interpretability and accuracy, offering a concise view of the most important features.

## Conclusion

This repository serves as a comparison of interpretable models applied to heart attack prediction. While each model offers different trade-offs between complexity and interpretability, the **C45TreeClassifier**, **RuleFitClassifier**, and **TaoTreeClassifier** provide valuable insights into risk prediction, allowing for the possibility of real-world application in healthcare scenarios where transparency is key.
