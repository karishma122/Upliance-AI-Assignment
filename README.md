# Upliance-AI-Assignment

This assignment analyzes user behavior, cooking preferences, and order trends to uncover actionable insights for enhancing user engagement and optimizing platform offerings. 

## Objectives
- Understand the relationship between cooking sessions and order patterns.
- Identify the most popular dishes and user preferences.
- Explore the impact of demographic factors (age, location) on user behavior.
- Provide actionable recommendations to enhance user engagement and boost orders.

---

## Assignment Workflow

### 1. Importing Libraries and Loading the Datasets
The project begins by importing essential libraries like `pandas`, `matplotlib`, and `seaborn`. Data from three datasets is loaded:
- `UserDetails` 
- `CookingSessions` 
- `OrderDetails`

### 2. Cleaning and Standardizing
- Columns are standardized to ensure consistent formatting across datasets.
- Missing values are handled appropriately:

### 3. Merging Datasets
Datasets are merged using common keys (`user_id` and `session_id`) to create a unified dataset that provides a comprehensive view of user behavior, cooking habits, and order details.

### 4. Exploratory Data Analysis
- **Conversion Rate**: Analyzed the percentage of cooking sessions that resulted in orders.
- **Dish Popularity**: Identified the top 5 most frequently ordered dishes.
- **Demographic Factors**:
  - Explored the influence of age and location on order behavior.
  - Analyzed the distribution of orders across different cities and age groups.

### 5. Visualizations
Visualizations were created to highlight key trends and insights:
- **Top 5 Popular Dishes**: Bar chart showing the most frequently ordered dishes.
- **Orders by Age Group**: Bar chart illustrating engagement across age groups.

### 6. Insights and Recommendations
Based on the analysis, key insights were derived, and actionable recommendations were provided to optimize the platform’s offerings and improve user retention. 

---

## Insights
1. **Perfect Conversion Rate**:
   - The platform achieved a **100% conversion rate**, meaning every cooking session resulted in an order.
2. **Top Dishes**:
   - The most frequently ordered dishes include **Spaghetti**, **Grilled Chicken**, **Caesar Salad**, **Pancakes**, and **Veggie Burger**, with Spaghetti and Grilled Chicken being the top choices.
3. **Demographic Trends**:
   - Users aged **18-30** and **30-50** dominate order activity, while engagement from **under 18** and **over 50** users remains low.
4. **Regional Trends**:
   - Cities like **New York**, **Chicago**, and **Los Angeles** are high-performing, whereas **Austin**, **Miami**, and **Boston** show lower engagement.

---

## Recommendations
1. **Capitalize on Popular Dishes**:
   - Highlight top dishes like **Spaghetti** and **Grilled Chicken** in promotions and meal bundles.
   - Introduce premium or localized variations of these dishes.
2. **Target Underperforming Demographics**:
   - **Under-18 Users**: Launch kid-friendly snack kits and meal prep activities.
   - **50+ Users**: Add health-focused options like low-sodium or diabetic-friendly meals.
3. **Boost Low-Order Cities**:
   - Run geo-targeted campaigns in **Austin**, **Miami**, and **Boston** with first-time order discounts.
   - Include regional or localized dishes to resonate with user preferences.
4. **Enhance Retention**:
   - Implement a loyalty program rewarding frequent orders and consistent engagement.
   - Offer "cook and earn" credits for converting cooking sessions into orders.
5. **Maintain 100% Conversion Rate**:
   - Use personalized recommendations during cooking sessions to suggest complementary orders (e.g., sides or desserts).

---




