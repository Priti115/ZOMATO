# 🍽️ Zomato Restaurant Data Analysis

This project is a data-driven exploration of restaurant trends on **Zomato**, one of India's leading food delivery and discovery platforms.  
Using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, we uncover insights about restaurant types, ratings, spending patterns, and online ordering behavior.

---

## 🔍 Project Overview

The goal of this analysis is to understand:

- 🏷️ Popular restaurant types
- ⭐ Common customer ratings
- 💸 Typical spending patterns
- 🌐 Impact of online ordering
- 💬 Customer engagement through votes

---

## 📊 Solved Questions

1. **What is the most common restaurant type listed on Zomato?**
2. **Which type of restaurant receives the highest number of customer votes?**
3. **What is the most common rating range received by restaurants?**
4. **What is the most common spending range for couples dining at restaurants?**
5. **Which mode receives higher ratings: Online vs Offline?**
6. **How does the availability of online ordering vary across restaurant types?**

---

## 🧪 Tools & Libraries Used

- 🐍 Python 3
- 📊 Pandas & NumPy
- 🎨 Matplotlib & Seaborn
- 📓 Jupyter Notebook

---

## 🗂️ Dataset Features

| Column Name                   | Description                              |
|------------------------------|------------------------------------------|
| `name`                       | Restaurant name                          |
| `online_order`               | Whether online order is available        |
| `book_table`                 | Table booking availability               |
| `rate`                       | Average customer rating (e.g., 4.1/5)    |
| `votes`                      | Number of customer votes                 |
| `approx_cost(for two people)`| Average cost for two people (in ₹)       |
| `listed_in(type)`            | Type of restaurant (Dining, Buffet, etc) |

---

## 📈 Visual Insights

- 📦 **Countplots** to show majority restaurant types  
- 🎯 **Votes** comparison by restaurant category  
- ⭐ **Rating distribution histogram**  
- 💸 **Spending range analysis**  
- 🌐 **Heatmap** showing online order availability by restaurant type

---

## 📌 Key Insight Example

> "Most restaurants are listed under **Dining**, and they also receive the **highest number of customer votes**. A majority of ratings fall between **3.5 to 4.0**, with ₹300 being the most common spending range for two people." 

---

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/zomato-analysis.git
   cd zomato-analysis
