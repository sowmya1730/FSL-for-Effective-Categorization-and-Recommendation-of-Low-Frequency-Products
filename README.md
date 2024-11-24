# Few-shot learning for Effective Product Categorization and Recommendation 🔍

📚 **Project Overview**
=========================
This project leverages Few-Shot Learning (FSL) to improve the categorization of low-frequency products with minimal labeled data and enhances recommendations using Contextualized Late Interaction over BERT (ColBERT) combined with session-based and product-specific features. 

**Approach**
=========================
- **Dataset and Preprocessing:** We use the Amazon M2 dataset, focusing specifically on low-frequency product categories. Initial steps include exploratory data analysis (EDA) and extensive preprocessing, such as removing duplicates, handling missing values, tokenization, and feature extraction.

- **Few-Shot Learning Model Development:** To classify low-frequency products, we will fine-tune a GPT-based model using few-shot learning techniques, enriched by contrastive learning and meta-learning. This approach allows the model to adapt to new categories quickly and distinguish between similar categories, creating a robust classifier for underrepresented products.

- **Custom Ranking System:** Post-categorization, we employ ColBERT for ranking, with feature engineering to capture session-specific and item-specific characteristics. We also incorporate XGBoost for shallow ranking, providing a blend of deep and shallow learning techniques for efficient recommendation.

- **Evaluation:** The models will be evaluated based on MRR@100 and runtime, with the aim of outperforming baseline models such as CatBoost Fusion and MGTV-REC, as shown in our anticipated results.

**Project Structure**
=========================


**Expected Results**
=========================
We anticipate that our approach, combining Few-Shot Learning for categorization with ColBERT for recommendation, will yield a high MRR@100, indicating effective recommendations for low-frequency products. The results are expected to demonstrate the advantages of Few-Shot Learning in handling data scarcity and ColBERT’s potential in delivering accurate, session-based recommendations for niche categories in e-commerce.

This project presents a scalable solution for low-frequency product recommendation in e-commerce, advancing beyond traditional approaches to meet the nuanced needs of users engaging with less common, niche items.


👥 **Authors**
===

🌟 **Acknowledgment**
===
