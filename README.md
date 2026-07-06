<!-- <i class="fa-brands fa-twitter"></i> -->
# 🐶 Twitter Data Wrangling & Analysis: WeRateDogs

This project focuses on wrangling, cleaning, analyzing, and visualizing Twitter data from the [WeRateDogs™](https://twitter.com/dog_rates) account. It follows the data wrangling process taught in the [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002).

📄 **Final Report**: [Dog Rates.pdf](./Dog%20Rates.pdf)  
📓 **Notebook**: [wrangle_act.ipynb](./wrangle_act.ipynb)

---

## 🧾 Project Summary

The project uses data from three different sources:

1. **Twitter Archive** – a CSV file of basic tweet data
2. **Image Predictions** – provided by Udacity via a neural network classifier
3. **Tweet JSON data** – programmatically gathered from the Twitter API

The datasets are cleaned, merged, and analyzed to uncover insights about dog breeds, ratings, and social engagement.

---

## 🛠️ Tools & Libraries Used

- Python (pandas, numpy, requests, json)
- Jupyter Notebook
- Tweepy (for Twitter API access)
- Matplotlib / Seaborn (for visualizations)

---

## 🧹 Wrangling Steps

The wrangling process follows these stages:

1. **Gathering** data from multiple sources
2. **Assessing** data for quality and tidiness issues (both visually and programmatically)
3. **Cleaning** data using defined rules
4. **Storing** cleaned data in a master DataFrame
5. **Analyzing and visualizing** to derive insights

---

## 📊 Key Insights

> Full analysis and visuals are in [Dog Rates.pdf](./Dog%20Rates.pdf), but here are some highlights:

- Most dogs were rated **above 10/10**, showing the account’s humorous style.
- **Golden Retriever**, **Labrador Retriever**, and **Pembroke** were among the most popular breeds.
- There’s a positive correlation between **favorites** and **retweets**.
- Dog ratings and breed predictions provided fun and engaging insights about what makes tweets go viral.

---

## 📁 Project Structure


---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmedshekooo/twitter_project.git
   cd twitter_project


