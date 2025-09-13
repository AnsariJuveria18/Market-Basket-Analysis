🛒 Market Basket Analysis

This project demonstrates Market Basket Analysis using the Apriori algorithm and Association Rule Mining.
It identifies frequent itemsets and discovers hidden patterns in transactional data to recommend products often bought together.



🚀 Features

• Transaction dataset transformation into **binary dataframe**
• Apriori Algorithm for frequent itemset mining
• Association Rules generation (support, confidence, lift)
• Easy-to-understand output of item correlations
• Works on any transactional dataset

---

🛠 Tech Stack

• Python
• Pandas → transaction encoding & data handling
• mlxtend → Apriori algorithm & association rules

---

🔎 Workflow

1. Dataset Creation

   • Represent customer transactions as item lists.
   • Convert dataset into a binary dataframe (1 = item bought, 0 = not bought).

2. Frequent Itemset Mining

   • Apply Apriori algorithm with minimum support threshold.

3. Association Rule Generation

   • Extract rules based on confidence and lift.
   • Identify product combinations for recommendations.

---

📊 Example Output

Frequent Itemsets:

  • {Bread, Milk}, {Beer, Diaper}, {Bread, Milk, Diaper}
• Association Rules:

  • If {Diaper} → {Beer} (Confidence: 0.75, Lift: 1.20)

