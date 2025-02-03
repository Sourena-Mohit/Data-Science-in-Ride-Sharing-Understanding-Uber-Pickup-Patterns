# Data-Science-in-Ride-Sharing-Understanding-Uber-Pickup-Patterns
## Uber Data Analysis

## **Context**
Uber Technologies, Inc. is an American multinational transportation network company based in San Francisco and has operations in approximately 72 countries and 10,500 cities. In the fourth quarter of 2021, Uber had **118 million monthly active users worldwide** and generated an average of **19 million trips per day**.

Ridesharing is a highly volatile market, where demand fluctuates due to factors such as **time, location, weather, and local events**. To succeed in this business, it is essential to detect patterns in these fluctuations and strategically adjust supply to meet demand.

As a **Data Scientist** at Uber's **New York Office**, you have been assigned the task of extracting insights from data to help the business understand **demand patterns** and make **data-driven decisions**.

## **Objective**
The goal of this project is to **extract actionable insights** around demand patterns across various factors and recommend strategies to Uber management for optimizing operations and capitalizing on fluctuating demand.

## **Key Questions**
1. **What are the different variables that influence pickups?**
2. **Which factor affects the pickups the most? What could be plausible reasons for that?**
3. **What are your recommendations to Uber management to capitalize on fluctuating demand?**

## **Methodology**
To analyze the data effectively, the following steps will be performed:

1. **Univariate Analysis**
   - Understand the distribution of each variable.
   - Identify trends, outliers, and missing values.

2. **Bivariate Analysis**
   - Explore relationships between different variables.
   - Identify the most significant factors affecting demand.

3. **Visualization**
   - Create meaningful visual representations of data trends.
   - Use plots to support findings and enhance interpretability.

## **Data Dictionary**
The dataset contains information about **weather conditions, locations, and pickup counts**. Below are the available variables:

| Column Name | Description |
|-------------|-------------|
| **pickup_dt** | Date and time of the pickup |
| **borough** | NYC borough where the pickup occurred |
| **pickups** | Number of pickups recorded during that period |
| **spd** | Wind speed in miles per hour |
| **vsb** | Visibility in miles (nearest tenth) |
| **temp** | Temperature in Fahrenheit |
| **dewp** | Dew point temperature in Fahrenheit |
| **slp** | Sea level pressure |
| **pcp01** | 1-hour liquid precipitation (inches) |
| **pcp06** | 6-hour liquid precipitation (inches) |
| **pcp24** | 24-hour liquid precipitation (inches) |
| **sd** | Snow depth in inches |
| **hday** | Whether it is a holiday (Y/N) |

## **Technologies Used**
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Data Visualization Tools**

## **Expected Outcomes**
- Identify **which factors impact Uber pickups the most**.
- Provide **data-driven recommendations** for Uber to improve service efficiency.
- Visualize patterns and trends to support business decisions.

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/Sourena-Mohit/Data-Science-in-Ride-Sharing-Understanding-Uber-Pickup-Patterns.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Data-Science-in-Ride-Sharing-Understanding-Uber-Pickup-Patterns
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## **Contributing**
Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request.

## **License**
This project is licensed under the **MIT License**.

---


