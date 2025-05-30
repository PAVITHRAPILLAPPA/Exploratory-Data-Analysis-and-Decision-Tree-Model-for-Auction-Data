# Exploratory-Data-Analysis-and-Decision-Tree-Model-for-Auction-Data

## 🎯 Objective
This project dives into auction data to uncover key drivers of auction competitiveness and applies a Decision Tree Classifier to predict competitive outcomes. The notebook showcases robust data exploration, insightful feature engineering, and model evaluation techniques that highlight the strengths and limitations of decision tree-based approaches in real-world scenarios.

## 🛠️ Tools & Technologies
- **Python (Jupyter Notebook)**
- **Libraries:** pandas, numpy, matplotlib
- **Machine Learning Model:** Decision Tree Classifier
- **Data Analysis & Visualization**

## 🔑 Key Features & Methodology
✅ **Real-Time Model Practicality**  
   - Uses only pre-auction data (open price, seller rating, category, currency, duration, and end day), making it feasible for live prediction scenarios.

✅ **Comprehensive Data Exploration**  
   - Assessed the impact of each feature on auction competitiveness and identified relationships and trends.

✅ **Feature Engineering**  
   - Developed meaningful thresholds and feature splits to enhance the decision tree’s predictive accuracy.

✅ **Model Interpretation & Visualization**  
   - Created clear visualizations of the decision tree and data distributions to understand the model’s logic and variable importance.

✅ **Key Insights & Actionable Takeaways**  
   - **OpenPrice** emerged as the most influential factor for predicting auction competitiveness.  
   - Auctions with low starting prices see increased competitiveness and bidding activity.  
   - Seller rating and category play a crucial role for high-price items, while currency and end day have minimal impact.  
   - Repetitive or overly granular decision tree splits highlight areas for model refinement.

✅ **Model Evaluation & Overfitting Awareness**  
   - Identified overfitting through comparison of RMSE values and box plots between training and validation sets.  
   - Proposed targeted strategies to reduce overfitting and improve generalizability.

## 📊 Results & Insights
- **OpenPrice** is the strongest predictor of auction success.  
- Lower opening prices drive more engagement, leading to higher final prices.  
- Seller rating and category are key differentiators for premium items.  
- Currency and end day show limited predictive value.  
- Model complexity can be managed through targeted pruning and hyperparameter tuning.

## 💡 Recommendations
✔️ Launch auctions with **lower opening prices** to spark competitive bidding and maximize final prices.  
✔️ **Maintain a strong seller rating** to improve auction outcomes, particularly in high-value listings.  
✔️ Focus resources on enhancing **core auction attributes** rather than minor variables like currency and end day.  
