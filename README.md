
# SALE-DATA-VISULIZATION-202401100300165
# Sales Data Visualization

## Overview
This project provides a simple way to analyze and visualize total revenue for different products using Python. It reads sales data, processes it with Pandas, and generates a bar chart using Matplotlib.

## Features
- Reads sales data directly from a defined dataset
- Aggregates total revenue per product
- Generates a bar chart to visualize revenue distribution
- Uses Pandas for data manipulation and Matplotlib for visualization

## Methodology
1. **Data Collection**: The sales data is defined as a string containing Product Name, Quantity Sold, and Revenue.
2. **Data Preprocessing**: The data is read into a Pandas DataFrame using `StringIO()`.
3. **Data Aggregation**: Revenue is grouped and summed by product category.
4. **Data Visualization**: A bar chart is created to display total revenue per product.
5. **Output Interpretation**: The chart provides insights into which products generate the most revenue.

## Installation & Usage
### Prerequisites
Make sure you have Python installed along with the required libraries:
```sh
pip install pandas matplotlib
```

### Running the Script
Run the following command in your terminal or Python environment:
```sh
python sales_data_viz.py
```

## Example Output
The script generates a bar chart that visualizes total revenue per product.

## License
This project is licensed under the MIT License.

## Author
Your Name

