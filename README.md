# 🍽️ Zomato Restaurant Data Analysis

An exploratory data analysis (EDA) project on Zomato restaurant data to uncover trends in customer preferences, dining habits, ratings, and ordering behavior across various restaurant types.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Analysis & Key Findings](#analysis--key-findings)
- [Visualizations](#visualizations)
- [Conclusions](#conclusions)
- [Getting Started](#getting-started)

---

## Overview

This project performs a comprehensive exploratory analysis of Zomato restaurant data to answer key business questions such as:

- Which type of restaurant is most popular?
- Do customers prefer online or offline ordering?
- What is the typical spending pattern for couples dining out?
- How do ratings differ between online and offline orders?
- Which restaurant has the highest number of votes?

---

## Dataset

The dataset (`Zomato data.csv`) contains information about restaurants listed on Zomato, including:

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `rate` | Customer rating (out of 5) |
| `votes` | Number of votes/reviews received |
| `online_order` | Whether online ordering is available (Yes/No) |
| `listed_in(type)` | Category/type of restaurant |
| `approx_cost(for two people)` | Approximate cost for two people (in INR) |

> **Note:** The dataset contains no null values, ensuring clean and reliable analysis.

---

## Technologies Used

- **Python 3**
- **Pandas** — Data manipulation and preprocessing
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization

---

## Analysis & Key Findings

### 1. 🍴 Restaurant Type Distribution
A count plot of restaurant categories reveals that **Dining restaurants dominate** the platform, making up the majority of listings.

### 2. 🗳️ Votes by Restaurant Type
When aggregating total votes per restaurant type, **Dining restaurants receive the most votes**, indicating they attract the highest customer engagement.

### 3. 🏆 Most Voted Restaurant
Identified the restaurant with the **maximum number of votes** from the entire dataset.

### 4. 📱 Online vs. Offline Orders
Analysis of the `online_order` column shows that a **majority of restaurants do not accept online orders**.

### 5. ⭐ Ratings Distribution
A histogram of restaurant ratings indicates that **most restaurants are rated between 3.5 and 4.0**, reflecting generally positive customer satisfaction.

### 6. 💰 Spending Patterns for Couples
The approximate cost distribution for two people shows that **₹300 is the most common spending point** for couples.

### 7. 📦 Online vs. Offline Order Ratings
A box plot comparing ratings across order modes reveals:
- **Online orders** tend to receive higher/more excellent ratings.
- **Offline orders** generally receive comparatively lower ratings.

### 8. 🔥 Heatmap — Order Mode by Restaurant Type
A pivot table heatmap comparing restaurant types against online/offline ordering shows:
- **Dining restaurants** primarily receive **offline** orders.
- **Cafes** predominantly receive **online** orders.

---

## Visualizations

The notebook includes the following visualizations:

- Count plot of restaurant types
- Line plot of votes per restaurant type
- Count plot of online order availability
- Histogram of ratings distribution
- Count plot of approximate cost for two
- Box plot of ratings vs. order mode
- Heatmap of restaurant type vs. order mode

---

## Conclusions

> **Dining restaurants** are the most popular category on Zomato, attracting the most listings and customer votes. Most restaurants still operate via offline ordering. Customers dining at restaurants tend to visit in person, while **cafes are more suited to online ordering**. Restaurants that accept online orders tend to receive better ratings, suggesting a positive link between online accessibility and customer satisfaction. The sweet spot for couple dining is around **₹300**.

---

## Getting Started

### Prerequisites

```bash
pip install pandas matplotlib seaborn
```

### Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/zomato-eda.git
   cd zomato-eda
   ```

2. Place the `Zomato data.csv` file in the project directory.

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook zomato.ipynb
   ```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Nikhil**  
Feel free to connect or raise an issue if you have any questions or suggestions!
