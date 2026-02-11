# Generative Adversarial Networks (GANs) & Neural Networks Implementation 🧠🎨

This repository explores image generation and data classification using **Deep Learning** frameworks. It showcases the implementation of generative models and multi-layer perceptrons.

## 🚀 Project Highlights
* **Generative Modeling:** Utilizing Adversarial training to synthesize data.
* **Hybrid Frameworks:** Leveraging both **PyTorch** for deep custom networks and **Scikit-Learn** for robust baseline classifiers.
* **Optimization:** Fine-tuning models using `GridSearchCV` and advanced optimizers like `Adam`.

## 🧠 Technical Workflow
* **Data Preprocessing:** Feature scaling using `MinMaxScaler` and `StandardScaler` to ensure stable gradient descent.
* **Architecture:** * Implementation of **MLP (Multi-Layer Perceptron)** for classification tasks.
    * Custom **Neural Network (nn.Module)** structures in PyTorch.
* **Evaluation:** Comprehensive performance analysis using `classification_report`, `accuracy_score`, and detailed `confusion_matrix` visualizations.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch (`torch`, `nn`)
* **Machine Learning:** Scikit-Learn
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📈 Evaluation Metrics
The project focuses on high-precision results, visualized through:
1. **Confusion Matrices:** To track misclassifications between generated vs. real data.
2. **Loss Curves:** Monitoring the convergence of Generator and Discriminator networks.
