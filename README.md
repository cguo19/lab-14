# lab-14
Lab 14
Section 1: Software and Platform
This project uses Python for data analysis and visualization.
Python version: 3.8 or higher recommended

Required packages:
pandas (for data handling)
numpy (for numerical operations)
matplotlib (for plotting)
statsmodels (for regression modeling)
scipy (for statistical tests)

You can install these packages using pip or conda:
pip install pandas numpy matplotlib statsmodels scipy

Platform: The scripts should work on any platform with Python and the above packages installed.

Hardware/software requirements:
A computer with at least 4GB of RAM is recommended for smooth execution.

ProjectFolder/
│
├── analysis.ipynb          # Main Jupyter notebook with analysis code
│
├── dataset_1.csv           # Dataset files (1 to 10)
├── dataset_2.csv
├── dataset_3.csv
├── dataset_4.csv
├── dataset_5.csv
├── dataset_6.csv
├── dataset_7.csv
├── dataset_8.csv
├── dataset_9.csv
└── dataset_10.csv

Steps:
1. Clone the repository to your local machine
git clone https://github.com/yourusername/lab-14.git
cd your-repo
2. Ensure you have Python 3.8+ installed along with the required packages
3. Open the Jupyter notebook in your preferred environment
4. Run the notebook cells in order. The notebook reads each dataset file (dataset_1.csv through dataset_10.csv) and performs the following for each:

Plots a scatter plot of Y vs X with an OLS regression line.
Generates a Q-Q plot to assess residual normality.
Performs a Shapiro-Wilk normality test on residuals.
If residuals pass normality, computes bootstrap confidence intervals for the regression coefficients.
Prints conclusions about statistical significance of the association between X and Y.

5. View the plots and printed output after running each analysis step to interpret the results.
