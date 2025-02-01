# 🍷 Wine-Market-Insights-Dashboard

## 📌 The Dataset
This project employs a dataset that compiles comprehensive data from various sources on **red and white wine** quality ratings, pricing, origin, etc. The primary goal is to analyze **how price and quality metrics influence consumers' willingness to pay** for wines from different geographical origins. The dataset includes attributes like:

- **Average rating (`Ratingnum`)**
- **Total ratings (`Ratings`)**
- **Aggregated sum of all ratings (`Ratingsum`)**

These features enable extensive comparisons across different dimensions.

---

## 🎯 Who It’s For
This dashboard is designed for:
- 🍷 **Wine Enthusiasts** – Understand which wines offer the best value for money.
- 📊 **Business Analysts** – Gain insights into wine market economics.
- 🏷️ **Wine Sellers** – Make informed pricing and marketing decisions.

The goal is to provide users with analytical insights into wine economics, helping both buyers and sellers make optimal decisions.

---

## ⚙️ Data Operations
1️⃣ **Data Merging and Cleaning**  
   - Combined `winequality_red.csv` and `winequality_white.csv` into a unified dataset.  
   - Standardized wine type and region naming for consistency.  

2️⃣ **Calculated Fields**  
   - Created **`Value_for_money = Ratingnum / Price`**, quantifying cost-effectiveness.  
   - Introduced **`Weighted_rating = Ratingsum * Ratings`**, capturing both popularity and user preferences.  

3️⃣ **Categorizing Quality**  
   - Introduced a new **"Quality"** column, categorizing wines into **High Quality** and **Low Quality** based on predefined thresholds.  

4️⃣ **Filtering & Column Creation**  
   - Created a **"Type of Wine"** column (`red` / `white`), filtering data accordingly for targeted analysis.  

---

## 📊 Justifications for Visualizations
- **Value for Money by Country** – A bar chart immediately highlights regions offering noteworthy wine quality relative to price, answering key consumer & seller questions.  
- **Taste Characteristics Dashboard** – Helps wine lovers understand properties such as **sweetness, acidity, and tannin levels**, guiding better purchasing decisions.  

---

## 🔍 Key Insights
🔹 **Tasting Characteristics & Quality**  
   - Higher-quality red wines often exhibit a well-balanced tannin profile, which could serve as a guide for identifying premium wines.  

🔹 **Regional Value for Money**  
   - Wines from **Bordeaux, Napa Valley, and other premium regions** are often expensive, but price alone does not necessarily correlate with **high value-for-money scores**.  
   
🔹 **Market Preferences & Quality Estimation**  
   - The relationship between **Weighted Rating vs. Price** reveals **non-linearity in quality scores**, suggesting that mid-priced wines with **high ratings** may be the best-value purchases.  

---

### 🚀 **Next Steps**
- Further explore **market segmentation** based on price sensitivity.  
- Implement **predictive modeling** for wine recommendations.  
- Develop a **real-time dashboard** for dynamic market insights.  

📌 **Check out the project repository for more details!**  
