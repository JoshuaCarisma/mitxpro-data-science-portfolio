# Module 07: Collaborative Filtering – Recommender Systems & Archetypal Modeling

## Objective
This module introduces collaborative filtering (CF) as a technique to build recommendation systems from sparse user-item data. You’ll learn to construct archetypes that represent user preferences and use them to predict unobserved behavior, such as product ratings, clicks, or choices.

---

## Learning Outcomes
- Identify examples and use cases of recommendation systems in business and daily life  
- Construct archetypal user models using collaborative filtering  
- Predict missing ratings using least-squares matrix factorization  
- Evaluate CF performance using out-of-sample R²  
- Understand the effect of choosing too few or too many archetypes (underfitting/overfitting)  
- Apply recentering and scaling to standardize collaborative filtering inputs  
- Combine CF with regression in ensemble models  

---

## Techniques Covered
- Matrix decomposition using least squares  
- Archetype creation (latent user and item factors)  
- Recenter-and-rescale transformations  
- Collaborative filtering prediction formulation  
- Ensemble modeling with logistic or linear regressions  
- Out-of-sample validation and R² optimization  
- Choosing optimal k (number of archetypes)

---

## Tools Used
- Python  
- NumPy, Pandas  
- Scikit-learn (matrix factorization, regression)  
- Matplotlib / Seaborn for visualization  
- Custom loss minimization for sparse matrices

---

## Personal Reflection

> “Collaborative filtering taught me that even with sparse information, we can still make powerful and useful predictions — if we model structure wisely.”

As someone who works in coaching and tech-forward wellness, I immediately saw how collaborative filtering applies to more than movies or playlists. Whether it's recommending exercises based on client preferences, nudging healthy behaviors, or designing a better content experience — **grouping users by unseen similarities** can improve engagement and personalization dramatically.

I was especially intrigued by the idea of **archetypes** — not just statistical models, but representations of behavior. In my work, clients often fall into recognizable patterns: weekend warriors, slow-and-steady practitioners, or data-driven optimizers. Collaborative filtering made it possible to model those patterns **mathematically** and predict how someone new might behave based on others like them.

> “When you can't ask someone what they want, show them what others like them have loved.”

The process of tuning the number of archetypes (K) and testing out-of-sample R² helped reinforce my understanding of model generalization and overfitting. And the idea of combining CF with linear regression opened up possibilities for **hybrid models** that integrate both behavior and metadata — something I’d love to apply in health tech or product recommendation systems in the future.

---

## Example Case Studies
- **Music Recommendation System (Synthetic Dataset)**  
  Used observed ratings to build an archetype-based CF model that predicted unknown ratings. Tuned the number of archetypes for best out-of-sample performance and visualized results using heatmaps.

- **Ensemble Recommender Model**  
  Built a hybrid model combining CF with metadata using linear regression. Predicted movie ratings as a function of collaborative signals, genre, and user demographics. Improved performance and interpretability.

---

## Key Takeaways
- Collaborative filtering enables prediction without explicit labels — relying only on co-behavior  
- Archetypes act as interpretable user “clusters” that reduce complexity and noise  
- Validation with held-out data is essential to prevent overfitting  
- Ensemble models combine the power of CF with feature-rich modeling  
- Recommender systems drive **personalization, retention, and engagement** — across industries

---

## Notebook: [`collaborative_filtering.ipynb`](./collaborative_filtering.ipynb) *(coming soon)*
