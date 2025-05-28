# 🎓 School Performance Classification Model

This project was developed as part of the *IFT 511 – Analyzing Big Data* course at Arizona State University, in collaboration with Amit Vasudev, Sanjana C Shekar, Vinayakswamy Kakoor, and Thilak Sujatha Krishnamurthy under the guidance of Prof. Asmaa Elbadrawy.

## 📌 Objective

The goal of this project is to build a machine learning model that classifies schools into high or low performance categories based on their English language and math scores. By leveraging historical academic data, our model helps identify patterns and key factors influencing student outcomes.

This project aims to aid educators, policymakers, and stakeholders in making data-driven decisions to improve academic achievement and promote equitable education.

## 🧠 Models Used

We experimented with three machine learning algorithms:

- **Support Vector Machine (SVM)**: Achieved up to 93% accuracy on validation data. Effective in handling non-linear boundaries using RBF kernel but struggled with class imbalance.
- **Artificial Neural Network (ANN)**: Achieved 80.12% accuracy with deeper feature learning, but showed higher variance across data splits.
- **Decision Tree (DT)**: Highly interpretable with 88.33% average accuracy, but prone to overfitting.

SVM was selected as the best performer due to its superior generalization and scalability potential.

## 📊 Key Learnings

- Data preprocessing (handling nulls, duplicates, feature scaling) significantly improved model performance.
- Model evaluation with metrics like accuracy, precision, recall, and F1-score provided deep insights into model behavior.
- Hyperparameter tuning was critical for boosting performance and avoiding overfitting.
- Visualizations played a key role in interpreting and presenting findings to non-technical stakeholders.

## 🚀 Future Improvements

- Balance dataset classes
- Tune SVM kernel and class weights
- Explore ensemble methods for better recall on minority classes

---

📁 Explore the codebase to dive deeper into how ML can enhance educational equity and support impactful decision-making.
