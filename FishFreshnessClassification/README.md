# 🐟 Fish Freshness Classification  
A machine learning classification project to identify the freshness level of fish (fresh or rotten) using sensor-based aroma data, aiding faster and more accurate quality control in the fisheries industry.

## 📌 Project Description  
This project aims to classify the freshness of fish using aroma sensor data by building and evaluating several machine learning models. The classification helps automate quality detection for better efficiency in the fish supply chain.  

Objectives include:
- Understanding aroma sensor feature patterns.
- Preprocessing and analyzing numerical data from sensors.
- Building ML models (SVM, Random Forest, KNN, Decision Tree).
- Evaluating performance through confusion matrix and accuracy metrics.

## 📈 Dataset  
Source: Internal dataset provided by university lecturer.  
Content:
- 80 samples of fish labeled as Fresh (A) or Rotten (B).
- 24 numeric features from 8 aroma sensors (each has mean, max, auc).

## Feature details:
- `fn_mean`: average sensor response (stability & intensity).
- `fn_max`: peak response (spoilage spikes).
- `fn_auc`: area under the curve (accumulated aroma intensity).

## 🚀 Key Results  
- Models tested: SVM, Random Forest, KNN, Decision Tree.
- Dataset showed balanced class distribution between fresh and rotten.
- Random Forest gave the best performance (details in notebook).
- Some features like `f2_mean`, `f6_max` had low discriminatory power.
- Correlation analysis revealed strong intra-sensor consistency.

## 🛠️ Tools  
- Python (Jupyter Lab)  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

## 📊 Visualizations  
The project includes:
- Distribution plots of each feature.
- Class balance visualization.
- Correlation heatmap between sensor features.
- Feature-wise distribution vs. class label.

## 🎯 Insights  
- Support Vector Machine (SVM) outperformed other models in classifying fish freshness, indicating its strength in handling overlapping sensor feature spaces.
- Normalization and proper preprocessing were crucial due to the wide range of feature values and presence of outliers.
- Despite high correlation among some features, tree-based models like Random Forest still performed competitively, but not as accurate as SVM.
- Data-driven automation using aroma sensors can significantly improve freshness detection efficiency in fisheries.

## 💡 Conclusion  
This project strengthened my skills in preprocessing sensor data, model comparison, and feature evaluation for small classification problems. It demonstrates a practical application of ML in quality assurance in fisheries.

## 📬 Contact  
If you have questions about this project, feel free to reach out:

- 📧 Email: azzahmst@gmail.com  
- 🌐 LinkedIn: www.linkedin.com/in/azzah-m-165867214
