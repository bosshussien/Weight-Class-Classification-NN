# 🥊 UFC Weight Class Classification using Fighter Stats

This project explores how a UFC fighter's physical and performance characteristics — such as height, weight, striking efficiency, and grappling efficiency — influence their weight class. It also builds a machine learning model to predict the most suitable weight class for a fighter.

---

## 📊 Data Insights

Notebook: `weightClass-insghts.ipynb`

- Load and explore the cleaned dataset `final_df.csv`
- Visualize feature distributions across weight classes using box plots
- Analyze key features like:
  - Height
  - Weight
  - Reach
  - Striking and Grappling statistics
- Generate interquartile ranges and full-range statistics for weight class differentiation

---

## 🤖 Neural Network Classification Model

Notebook: `weightclass_nnmodel.ipynb`

- Preprocessing:
  - MinMax scaling of numerical features
  - One-hot encoding for weight class labels
- Model:
  - Built with Keras (TensorFlow backend)
  - Input: Fighter stats
  - Output: Predicted weight class
- Evaluation:
  - Train/test split
  - Classification report
  - Model summary and architecture diagram

---

## 🧠 Why This Project Matters

- **Optimizes fighter performance** through smart weight class suggestions
- **Data-driven insights** into physical attributes across weight classes
- Demonstrates **real-world multi-class classification** with neural networks

---

## 📁 Files Included

- `final_df.csv` — Processed dataset with weight classes
- `weightClass-insghts.ipynb` — EDA and visualization
- `weightclass_nnmodel.ipynb` — Classification model
- `model_structure.png` — Visual summary of the model architecture

---

## 🔗 Resources

- 📂 GitHub Repo: [Project Repository](https://github.com/bosshussien/Weight-Class-Classification-NN.git)
- 📊 Raw Dataset (Before preprocessing): [Kaggle UFC Data](https://www.kaggle.com/datasets/rajeevw/ufcdata)

---

## 🏷 Hashtags for LinkedIn

```
#MachineLearning #DeepLearning #UFC #DataScience #SportsAnalytics #NeuralNetworks #Keras #Python #MLProjects #DataVisualization #AthletePerformance
```
