# DS-2: Data Visualization – Stroke Risk Analysis

## Project Overview

This project focuses on exploring and visualizing a Stroke Risk Prediction dataset using Python. The objective is to understand patterns and relationships in healthcare data through different types of visualizations.

Interactive charts are created using Plotly to make data exploration easier.

## Dataset Description

- **Dataset Name:** Stroke Risk Prediction
- **Number of Records:** 5,110
- **Number of Columns:** 12
- **Domain:** Healthcare Data Analytics
- **Target Variable:** `stroke`

The dataset contains information about age, gender, hypertension, heart disease, average glucose level, BMI, smoking status and other attributes related to stroke prediction.

## Tools and Technologies Used

| Tool / Library | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Plotly Express | Interactive charts |
| Plotly Graph Objects | Visualization library |
| Jupyter Notebook | Development environment |

## Data Preparation

The following data preparation steps were performed:

- Loaded the dataset using Pandas.
- Examined the dataset structure and data types.
- Checked for missing values and duplicate records.
- Removed duplicate records.
- Filled missing BMI values using the median.
- Created a `stroke_status` column to represent stroke categories as No Stroke and Stroke.

## Visualizations

Five different types of visualizations were created:

1. **Bar Chart:** Compares stroke distribution across genders.
2. **Histogram:** Shows age distribution based on stroke status.
3. **Scatter Plot:** Explores the relationship between BMI and average glucose level.
4. **Box Plot:** Compares glucose-level distributions between stroke categories.
5. **Correlation Heatmap:** Displays correlations among selected numerical and binary features.

## Interactive Features

The charts are created using Plotly. Users can:

- Hover over chart elements to view additional information.
- Zoom in and zoom out.
- Pan across charts.
- Explore patterns interactively.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy plotly jupyter
   ```

3. Keep `stroke_dataset.csv` in the same folder as the Jupyter Notebook.
4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `DS2_Stroke_Visualization.ipynb` and run all cells.

## Project Structure

```text
DS-2-Data-Visualization/
│
├── DS2_Stroke_Visualization.ipynb
├── stroke_dataset.csv
├── TASK2_DATAVISUALIZATION.html
└── README.md
```

## Conclusion

This project demonstrates how data visualization helps explore healthcare datasets. Different visualization techniques provide insights into distributions, relationships and correlations among selected attributes. Interactive charts make the analysis easier to explore and understand.

---

