# Zomato Data Analysis

This project focuses on analyzing Zomato's restaurant and customer behavior data to uncover trends and insights. The primary goal is to address key business questions about customer preferences, restaurant ratings, ordering modes, and spending habits.

---

## Objectives

The analysis addresses the following questions:  
1. **What type of restaurant do the majority of customers order from?**  
   - Identify the most popular types of restaurants based on customer orders.  
2. **How many votes has each type of restaurant received from customers?**  
   - Analyze customer feedback (votes) to determine which restaurant types are most liked.  
3. **What are the ratings that the majority of restaurants have received?**  
   - Find the most common ratings among restaurants on Zomato.  
4. **What is the average spending on each order for couples who order online?**  
   - Analyze the spending behavior of couples who order food online.  
5. **Which mode (online or offline) has received the maximum rating?**  
   - Compare customer ratings for online and offline orders.  
6. **Which type of restaurant received more offline orders, so Zomato can provide good offers to those customers?**  
   - Identify restaurant types with higher offline orders to design promotional strategies.

---

## Dataset

The dataset includes the following key attributes:  
- **Restaurant Type**: Categories like casual dining, quick bites, cafes, etc.  
- **Votes**: Number of votes each restaurant has received.  
- **Ratings**: Average customer ratings for restaurants.  
- **Order Mode**: Online vs. Offline ordering options.  
- **Cost for Two**: Average spending for two people.  
---

## Analysis Workflow

### 1. Data Cleaning  
- Handle missing values in key columns like ratings and votes.  
- Normalize text data (e.g., converting categories to lowercase).  

### 2. Exploratory Data Analysis (EDA)  
The following steps were performed:  
- **Restaurant Types**: Used bar plots to visualize the most popular restaurant types based on orders.  
- **Votes Analysis**: Aggregated votes by restaurant type to identify the most liked categories.  
- **Ratings Analysis**: Examined the distribution of ratings across all restaurants.  
- **Couples' Spending Behavior**: Filtered data to analyze average spending for couples ordering online.  
- **Online vs. Offline Mode Ratings**: Compared ratings using mean and median calculations.  
- **Offline Orders**: Identified restaurant types with the highest offline orders.  

### 3. Visualizations  
- Bar charts for order trends and vote distributions.  
- Pie charts to show the split between online and offline ratings.  
- Histograms for rating distributions.  
- Box plots for analyzing average spending trends.  

---

## Tools and Technologies Used

- **Python**:
  - `pandas` for data cleaning and manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for visualizations.
  - `plotly` for interactive charts.  

---

## How to Run the Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/Jaikumar2406/zomato-data-analysis.git
   cd zomato-data-analysis
