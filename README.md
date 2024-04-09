
# Optimization Problem for New England Feed Supply Company

## Problem Description:
The optimization problem involves determining the best mix of feed ingredients for New England Feed Supply Inc. (NEFS) to meet nutritional requirements while minimizing costs. The company produces three types of feed products: 15% pig feed, 40% pig feed, and 17% caged chicken feed.

## Data Preparation:
- **Nutrient Requirement Matrix (df1):**
    - Contains the nutritional requirements for each product and nutrient type.
- **Nutrient Lower Bound Matrix (b):**
    - Extracts the nutrient lower bounds for each product.
- **Product Demand Vector (demand):**
    - Extracts the demand for each product.
- **Nutrient Content Matrix for Raw Materials (df2):**
    - Contains the nutrient content and cost of various raw materials.
- **Price Vector for Raw Materials (p):**
    - Extracts the prices of different raw materials.

## Optimization Process:
1. **Optimization Model:**
    - Defines a decision matrix for ingredient proportions and sets constraints based on nutrient requirements and inventory limits.
2. **Loop Implementation:**
    - Iterates over increasing market prices for meat powder to observe changes in the optimal strategy.
3. **Solver and Results:**
    - Utilizes an optimization solver to minimize total production costs and outputs the best ingredient proportions for each scenario.

## Visualizations:
- Generates a plot showing the relationship between market prices for meat powder and total production costs.
- Marks key price points where optimal strategies change.

