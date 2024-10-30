# Few-shot learninng for Effective Product Categorization and Recommendation 🔍

📚 **Project Overview**
=========================
In the ever-growing e-commerce landscape, platforms like Amazon host an extensive catalog of products spanning a multitude of categories. However, a significant proportion of these categories, especially those with niche products, suffer from a low frequency of labeled examples, making them challenging for traditional supervised learning models, which rely on abundant labeled data to achieve accurate predictions. This scarcity of labeled instances in low-frequency categories not only impacts categorization accuracy but also hinders the effectiveness of recommendation systems for such products, ultimately reducing user satisfaction.

Our project addresses these challenges by leveraging Few-Shot Learning (FSL) to improve the categorization of low-frequency products, enabling the model to generalize from limited labeled examples. In addition, we implement a custom recommendation system that combines Contextualized late interaction over BERT (ColBERT) with session-based and product-specific features. This dual approach—categorizing low-frequency products with Few-Shot Learning and enhancing recommendations with ColBERT—aims to achieve higher recommendation accuracy while remaining computationally efficient.

**Objectives**
=========================
- Improve Categorization Accuracy: Using Few-Shot Learning techniques, we aim to enhance the categorization of products in low-frequency categories, allowing the model to learn effectively from minimal labeled examples.

- Enhanced Recommendations: Our goal is to design a ranking and recommendation system that efficiently suggests low-frequency products using ColBERT, evaluated against standard benchmarks like MRR@100 to measure relevance.

- Comparison to Baselines: To validate the efficacy of our approach, we will compare our model’s performance with existing baseline models on accuracy, efficiency, and relevance metrics.

**Approach**
=========================
- Dataset and Preprocessing: We use the Amazon M2 dataset, a large-scale, multilingual e-commerce dataset, focusing specifically on low-frequency product categories. Initial steps include exploratory data analysis (EDA) and extensive preprocessing, such as removing duplicates, handling missing values, tokenization, and feature extraction.

- Few-Shot Learning Model Development: To classify low-frequency products, we will fine-tune a GPT-based model using few-shot learning techniques, enriched by contrastive learning and meta-learning. This approach allows the model to adapt to new categories quickly and distinguish between similar categories, creating a robust classifier for underrepresented products.

- Custom Ranking System: Post-categorization, we employ ColBERT for ranking, with feature engineering to capture session-specific and item-specific characteristics. By leveraging ColBERT, we enable more accurate recommendations of low-frequency products based on contextual interaction. We also incorporate XGBoost for shallow ranking, providing a blend of deep and shallow learning techniques for efficient recommendation.

- Evaluation: The models will be evaluated based on MRR@100 and runtime, with the aim of outperforming baseline models such as CatBoost Fusion and MGTV-REC, as shown in our anticipated results.

**Expected Results**
=========================
We anticipate that our approach, combining Few-Shot Learning for categorization with ColBERT for recommendation, will yield a high MRR@100, indicating effective recommendations for low-frequency products. The results are expected to demonstrate the advantages of Few-Shot Learning in handling data scarcity and ColBERT’s potential in delivering accurate, session-based recommendations for niche categories in e-commerce.

This project presents a scalable solution for low-frequency product recommendation in e-commerce, advancing beyond traditional approaches to meet the nuanced needs of users engaging with less common, niche items.

📖 **Table of contents**
=========================

🔧 **Installation|running**
===========================
Describe how the program can be ran

👥 **Authors**
===

🌟 **Acknowledgment**
===
