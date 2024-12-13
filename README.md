# Few-shot learning for Effective Product Categorization and Recommendation 🔍

📚 **Project Overview**
=========================

This project leverages Few-Shot Learning (FSL) to enhance the categorization of low-frequency products in e-commerce platforms, addressing the challenge of limited labeled examples in niche categories. Additionally, it integrates a custom recommendation system combining Contextualized Late Interaction over BERT (ColBERT) with session-based and product-specific features, aiming to improve recommendation accuracy while maintaining computational efficiency.

## Objectives  
- **Improve Categorization Accuracy:** Leverage Few-Shot Learning to classify low-frequency product categories with minimal labeled examples.  
- **Enhanced Recommendations:** Design a ranking and recommendation system using ColBERT, focusing on relevance and efficiency.  
- **Baseline Comparison:** Evaluate performance against existing models on metrics like accuracy, MRR@100, and runtime efficiency.  

## Approach  
1. **Dataset and Preprocessing:**  
   - Utilize the Amazon M2 dataset, focusing on low-frequency product categories.  
   - Perform exploratory data analysis (EDA) and preprocessing, including tokenization, feature extraction, and handling missing data.  

2. **Few-Shot Learning for Categorization:**  
   - Fine-tune a GPT-based model with few-shot learning techniques, integrating contrastive learning and meta-learning to classify underrepresented products.  

3. **Custom Recommendation System:**  
   - Implement a ColBERT-based ranking system with session-specific and product-specific features for precise recommendations.  
   - Incorporate XGBoost for shallow ranking to complement deep learning techniques.  

4. **Evaluation:**  
   - Assess the system using metrics such as MRR@100 and runtime efficiency.  
   - Benchmark against baseline models like CatBoost Fusion and MGTV-REC.  


## Expected Results  
The project aims to demonstrate:  
- Improved categorization accuracy for low-frequency product categories.  
- High relevance in recommendations with competitive MRR@100 scores.  
- A scalable and computationally efficient solution for niche e-commerce products.  

🔧 **Installation|running**
===========================
**Google colab:** This is the recommended way to run the code. 
- download the dataset from kaggle using this  [link](https://www.kaggle.com/datasets/marquis03/amazon-m2)
- install or requirements in the requirements.txt file
- run the code in init_thought_process step by step. you can skip steps based
- or you can run the entire code once using initial_training_cleaning
- **code is still in progress**
  
** To run the code locally **
- set up the environment 
'''bash 
#on windows
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -r requirements.txt  

#On Linux
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -r requirements.txt 

```
The Two commands are of the same structure
- Activate the python environment
- Upgrade pip to it current version
-  install the requirements located in requirements.txt: You should be at the root of your env

👥 **Authors**
===
- Sylvester Ampomah
- Sai Sowmya 

🌟 **Acknowledgment**
===
We express our profound gratitude to Professor Qu of GWU for his profound support in handling this project
