# E-Commerce Data Analysis Project

This project analyzes e-commerce transaction data to derive business insights and build customer segmentation models.

## Project Structure

- `EDA.ipynb`: Jupyter notebook containing all analysis and models
- `requirements.txt`: Required Python packages
- Generated files:
  - `Lookalike.csv`: Contains lookalike customer recommendations
  - Various visualization outputs

## Setup and Running

1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Run the Jupyter notebook:
```bash
jupyter notebook EDA.ipynb
```

## Key Components

1. **Exploratory Data Analysis (EDA)**
   - Customer demographics analysis
   - Product category analysis
   - Transaction patterns
   - Business insights

2. **Lookalike Model**
   - Customer similarity scoring
   - Top 3 similar customers for first 20 customers

3. **Customer Segmentation**
   - K-means clustering
   - Davies-Bouldin Index optimization
   - Cluster visualization

## Results

The analysis provides:
- 5 key business insights
- Lookalike customer recommendations
- Optimal customer segments with visualization