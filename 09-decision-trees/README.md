# Module 09: Decision Trees & Ensemble Learning – CART, Random Forest, and XGBoost

## Objective  
This module introduces decision trees and ensemble learning as powerful, nonlinear models for both classification and regression. It begins with CART (Classification and Regression Trees), then extends to ensemble techniques like Bagging, Random Forests, and Gradient Boosting. These models prioritize predictive power while balancing interpretability, overfitting, and performance — essential tools for modern data-driven decision-making.

---

## Learning Outcomes  
- Build classification and regression trees (CART)  
- Interpret tree visualizations, splits, and terminal nodes  
- Explain decision trees to stakeholders and non-technical audiences  
- Understand Gini impurity for binary classification  
- Evaluate and compare models using RMSE, MAE, and OSR²  
- Implement ensemble methods including Bagging, Random Forest, and XGBoost  
- Tune hyperparameters and evaluate model overfitting or underfitting  
- Analyze variable importance and model interpretability  

---

## Techniques Covered  
- CART (Classification and Regression Trees)  
- Gini coefficient for classification impurity  
- Mean Squared Error (MSE) for regression splitting  
- Decision rules and region partitioning  
- Bagging and bootstrap resampling  
- Random Forests (decorrelated tree ensembles)  
- Gradient Tree Boosting (sequential error correction)  
- XGBoost (regularized gradient boosting with hyperparameter tuning)  
- Cross-validation and grid/random search  
- Tree stumps, depth control, and shrinkage for boosting  

---

## Tools Used  
- Python  
- Scikit-learn (DecisionTreeClassifier, RandomForest, GradientBoostingRegressor)  
- XGBoost (XGBClassifier / XGBRegressor)  
- Matplotlib, Seaborn  
- Sklearn metrics: MAE, RMSE, OSR²  
- Visualizations: decision trees, feature importance plots  

---

## Personal Reflection

CART models were the first algorithms that felt both powerful and human. Unlike the linear models I’d worked with previously, these trees allowed for simple, explainable logic: “If this, then that.” But the real power came when I moved into ensembles — understanding how models could collaborate like a team.

Working with **Random Forests** helped me see how diversity in decision-making improves results. In health coaching, this is natural — no single signal explains progress, but many weak ones together can. In modeling terms, that’s Bagging: building diverse models and averaging them to reduce variance.

The transition to **Gradient Boosting and XGBoost** reminded me of coaching iteration: fail fast, learn, adapt. Boosting trains weak learners sequentially to fix past mistakes. This is exactly how I approach habit change in clients — building strength by **targeting weaknesses one at a time**.

What stood out most was the trade-off between interpretability and performance. CART is easy to explain. Random Forests and XGBoost are harder to unpack — but deliver dramatically better results. This tradeoff is real in business and healthcare: Do you want answers you can explain or answers that perform better? I want to build systems that can **do both**.

---

## Example Case Studies  
- **Graduate Admissions Prediction with CART**  
  Modeled interview outcomes using CART. Visualized splits and terminal node predictions. Found that GPA and relevant work experience were the strongest splitters.

- **CTR Prediction for Ads (XGBoost)**  
  Used XGBoost to predict click-through rate (CTR) based on ad type, user history, and time of day. Boosting outperformed logistic regression by 7% OSR² and 12% reduction in RMSE.

- **Ensemble Tuning for Classification Accuracy**  
  Trained models with different numbers of trees and depth. Demonstrated that increasing depth in Random Forest improves fit up to a point — after which boosting performs better by focusing on hard-to-classify examples.

---

## Key Takeaways  
- CART offers intuitive, interpretable structure for regression and classification  
- Gini impurity and MSE help trees make smart splits  
- Bagging (Random Forests) improves stability by reducing variance  
- Boosting (XGBoost) improves accuracy by correcting errors over time  
- Hyperparameter tuning, validation, and visual analysis are critical to avoid overfitting  
- Tree-based models work well on messy, nonlinear, and categorical datasets — especially when interpretability or ensemble power is needed

---

## Notebook: `decision_tree_models.ipynb` *(coming soon)*
