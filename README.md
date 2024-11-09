# Tata Group Data Visualisation: Empowering Business with Effective Insights

This project is a job simulation for Tata Group's Data Visualization task. The primary objective is to create meaningful data insights for executive decision-making, focusing on revenue trends, customer segmentation, and market demand analysis. The deliverables include data visualizations tailored to answer key business questions from the CEO and CMO.

## Project Overview

In this simulation, I analyzed a dataset to answer questions posed by Tata Group's CEO and CMO. The goal was to present insights that aid in decision-making, such as expansion strategy and customer retention plans. Visualizations were created in either **Tableau** or **Power BI**, using cleaned data to ensure accuracy.

## Data Cleaning Process

Before creating the visuals, data cleaning was performed to remove incorrect or irrelevant entries:
- **Negative Quantities:** Removed records with a quantity less than 1, as these indicate returns or data entry errors.
- **Negative Unit Prices:** Excluded records with a unit price below $0, which likely represent data entry errors.

This cleaned dataset was used to create accurate and reliable visualizations.

## Visualizations

The visualizations were created to address specific questions from Tata Group's CEO and CMO:

### Question 1: Monthly Revenue Time Series for 2011
- **Objective:** Help the CEO analyze monthly revenue trends for 2011, providing insights into seasonal sales patterns.
- **Visual Type:** Line Chart
- **Description:** Displays monthly revenue for 2011, highlighting seasonal trends and revenue peaks.

### Question 2: Top 10 Revenue-Generating Countries (Excluding the UK)
- **Objective:** Show the top 10 countries by revenue (excluding the UK) and include quantity sold, helping the CMO understand global performance.
- **Visual Type:** Bar Chart with Dual Axis for Quantity and Revenue
- **Description:** Ranks the top 10 countries by revenue and displays quantity sold, giving the CMO insight into high-performing markets.

### Question 3: Top 10 Customers by Revenue
- **Objective:** Enable the CMO to identify the top 10 revenue-generating customers to focus on retention efforts.
- **Visual Type:** Descending Bar Chart
- **Description:** Displays the top 10 customers by revenue, sorted in descending order to prioritize high-value customers.

### Question 4: Demand by Country (Excluding the UK)
- **Objective:** Help the CEO understand demand distribution globally (excluding the UK) to identify regions for potential expansion.
- **Visual Type:** World Map with Heatmap Overlay
- **Description:** Shows demand by country with color gradients, allowing quick identification of high-demand regions.

## Tools Used

- **Power BI**: Used to create data visualizations in an interactive and insightful format.
- **Data Cleaning:** Performed within Tableau/Power BI using conditional filters and data transformation techniques.

## File Structure

- `README.md`: Project overview and descriptions.
- `data/`: Contains the original dataset and any cleaned data files.
- `visualizations/`: Contains Tableau `.twbx` or Power BI `.pbix` files with each visualization saved in its respective tab.

## Conclusion

This project demonstrates the use of data visualization to provide strategic insights for business leaders. By understanding revenue trends, customer segments, and market demand, Tata Group's executives can make informed decisions to enhance customer satisfaction and expand into new markets.

---

**Note:** This is a simulation project for educational purposes, based on a sample dataset provided as part of the Tata Group job simulation.
