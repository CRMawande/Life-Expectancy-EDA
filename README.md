# Life Expectancy EDA

![life_expectancy_gdp_scatterplot](https://github.com/user-attachments/assets/6800db41-343e-46c8-b722-a4f6ca2fa854)

*Example visualization: Life Expectancy vs. GDP, showing how GDP tends to correlate with higher life expectancy, differentiating between developed and developing countries.*

## Project Overview

This repository hosts an in-depth Exploratory Data Analysis (EDA) project focusing on the **Life Expectancy (WHO) dataset**. The goal is to comprehensively analyze various socio-economic and health factors influencing life expectancy across different countries and years. Through statistical methods and rich visualizations, this project aims to uncover patterns, trends, and relationships within the dataset.

## Dataset

The dataset used in this project is the "Life Expectancy (WHO)" dataset, which contains health and economic factors for 193 countries from 2000-2015.

* **Source:** [Kaggle - Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
* **File:** `Life Expectancy Data.csv` (This file should be placed in the root directory of the cloned repository.)

## Analysis Covered

The Jupyter notebook `Life_Expectancy_EDA.ipynb` performs the following key analyses:

1.  **Data Loading & Cleaning:** Initial inspection, handling of column names (stripping whitespace), and imputation of missing numerical values using the mean.
2.  **Descriptive Statistics:** Calculation of measures of central tendency (mean, median) and variability (standard deviation, quartiles, IQR) for all numerical features.
3.  **Distribution Analysis:** Visual exploration of the distribution of all numerical features using histograms, Kernel Density Estimate (KDE) plots, box-whisker plots, and violin plots to identify skewness, outliers, and overall shape.
4.  **Covariance & Correlation:** Quantification and visualization of linear relationships between all numerical features using a correlation matrix heatmap. Specific attention is given to the relationship between 'Life expectancy' and 'GDP'.
5.  **Time-Series Trends:** Analysis of average life expectancy over the years.

## Getting Started

To run this EDA project locally, follow these steps:

### Prerequisites

Ensure you have Python (3.7+) and pip installed.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/CRMawande/Life-Expectancy-EDA.git](https://github.com/CRMawande/Life-Expectancy-EDA.git)
    cd Life-Expectancy-EDA
    ```
2.  **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download the dataset:**
    Download the `Life Expectancy Data.csv` file from the [Kaggle dataset page](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who) and place it directly into the `Life-Expectancy-EDA` directory (the root of the cloned repository).

### Running the Notebook

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  Your web browser will open with the Jupyter interface. Navigate to and open `Life_Expectancy_EDA.ipynb`.
3.  Run all cells in the notebook to reproduce the analysis and visualizations.

## Key Insights

* Preliminary findings indicate the distribution of `Life expectancy` is somewhat negatively skewed.
* Strong correlations exist between `Life expectancy` and factors like `Schooling`, `Income composition of resources`, and `Adult Mortality`.
* Features like `infant deaths`, `under-five deaths`, `Measles`, and `HIV/AIDS` often show highly skewed distributions with significant outliers.
* The project provides a visual understanding of how various health and economic indicators interact to influence life expectancy trends.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please feel free to reach out.

* **GitHub:** [CRMawande](https://github.com/CRMawande)

---
