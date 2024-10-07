# Bike Purchase Analysis

## Project Overview

This project focuses on analyzing a dataset related to the purchase of bikes by different individuals, exploring key factors such as marital status, gender, income, commute distance, and other demographics. The dataset was cleaned and transformed, and various insights were drawn from pivot tables and visualizations. Additionally, a dashboard was created to allow users to interact with the data through slicers.

## Dataset

The dataset includes the following attributes for each individual:
- **ID**: Unique identifier for each individual
- **Marital Status**: Marital status of the individual (Married/Single)
- **Gender**: Gender of the individual (Male/Female)
- **Income**: Annual income of the individual in dollars
- **Children**: Number of children the individual has
- **Education**: Educational attainment level (e.g., Bachelors, Partial College)
- **Occupation**: Type of occupation (e.g., Professional, Clerical, Skilled Manual, etc.)
- **Home Owner**: Indicates whether the individual owns a home (Yes/No)
- **Cars**: Number of cars the individual owns
- **Commute Distance**: Distance traveled to work (ranges from 0-1 Miles to more than 10 Miles)
- **Region**: Geographical region where the individual resides
- **Age**: Age of the individual
- **Age Ranges**: Categorical grouping of age (e.g., Adolescent Adult, Adult, Middle Age, Older Adult)
- **Purchased Bike**: Indicates whether the individual purchased a bike (Yes/No)

## Data Cleaning

Before performing analysis, certain transformations were made:
1. Gender was encoded as "M" for Male and "F" for Female.
2. Income values were standardized to a fixed decimal format for consistency.
3. Age was grouped into categorical ranges to simplify analysis (Adolescent Adult, Adult, Middle Age, Older Adult).
4. The Marital Status was reduced to single-letter codes (M for Married, S for Single).

## Analysis Summary

### Pivot Table Insights

1. **Average Income by Gender and Bike Purchase**
   - A pivot table was created to calculate the average income for individuals who purchased a bike, broken down by gender.
   - **Findings**:
     - Female: Average income of $53,440 (No purchase) vs $55,774 (Purchased a bike)
     - Male: Average income of $56,208 (No purchase) vs $60,124 (Purchased a bike)

2. **Count of Bike Purchases by Commute Distance**
   - This pivot table showed the distribution of bike purchases across different commute distances.
   - **Findings**:
     - The highest number of purchases came from individuals with a commute distance of 0-1 Miles (366 total individuals).
     - The lowest number of purchases was for individuals commuting more than 10 Miles (111 individuals).

3. **Count of Bike Purchases by Age Range**
   - This analysis grouped individuals by their age range to see how bike purchases vary by life stage.
   - **Findings**:
     - Middle Age (41-60 years) had the highest count of bike purchases, with 566 individuals in total.

### Dashboard

To provide more interactive insights, I developed a dashboard with slicers. The dashboard allows for filtering data based on:
- **Marital Status**: Married or Single
- **Education**: Bachelors, Partial College, or Manual
- **Region**: Europe or Pacific

The slicers help visualize how bike purchases and other factors shift when segmented by different demographic attributes.

## Tools & Technologies Used

- **Excel**: Data cleaning, pivot table generation, and dashboard creation
- **Dashboard**: Built-in Excel dashboard features with slicers for interactive filtering
- **Pivot Tables**: Used to calculate averages and counts for different demographic groups

## Future Improvements

1. **Data Enrichment**: Additional data such as exercise habits or environmental factors could provide more context for bike purchasing decisions.
2. **Predictive Modeling**: Building a machine learning model to predict whether an individual is likely to purchase a bike based on the provided features.
3. **Visualization Enhancement**: Implementing more complex visualizations, such as scatter plots or histograms, using tools like Tableau or Power BI for a more sophisticated dashboard.

## Conclusion

This project provided valuable insights into the factors influencing bike purchases, especially highlighting the roles of income, commute distance, and age. The use of pivot tables and an interactive dashboard enabled in-depth exploration of the data, making it easier to understand trends and relationships between different variables.
