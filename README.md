# Cyber Crime Prediction and Analysis Using Machine Learning

The rise of digital platforms has brought with it an increase in cyber crimes, making prediction and prevention critical challenges. This project leverages Python for data analysis and machine learning to predict cyber crime trends based on historical data. Additionally, Tableau is used to create interactive dashboards, enabling stakeholders to explore insights effectively. Using techniques like Support Vector Regression (SVR) and Linear Regression, this project provides actionable insights to forecast trends and identify high-risk regions.
## Features

**Data Analysis and Insights**
* Analysis of cyber crime trends across districts and states over multiple years.
* Insights into crime distribution by categories (e.g., fraud, hacking, identity theft).
* State-wise and year-wise comparisons to identify high-crime regions and periods.

**Predictive Modeling**
* Implementation of Support Vector Regression (SVR) to predict future crime trends.
* Use of Linear Regression for comparative analysis and evaluating prediction accuracy.
* Prediction of crime counts for specific districts, states, or overall trends.

**Data Visualization**

* **Static Visualizations:** : Python-based visualizations using Matplotlib and Seaborn for exploring trends and distributions.
* **Interactive Dashboards:** : Tableau dashboards enabling users to interactively filter and explore:
    * Crime types
    * States/districts
    * Year-wise trends

**User-Friendly Workflow**

* Easy-to-follow steps for data preprocessing, modeling, and visualization using Python.
* Cleaned and transformed data ready for analysis and machine learning.

**Comprehensive Reporting**

* Predictive insights presented as graphs and charts for decision-making.
* Tableau dashboards providing actionable visual reports for stakeholders.

**Scalability and Customization**

* Modular design allowing for integration of additional crime categories or datasets.
* Flexibility to extend prediction models to other crime-related data.
## Tech Stack
**Data Analysis and Machine Learning:**
* **Python**: For data processing, analysis, and implementing machine learning models.
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical computations.
* **Scikit-learn**: For machine learning algorithms, particularly for implementing Support Vector Regressor (SVR) and Linear Regression.
* **Matplotlib / Seaborn**: For data visualization and plotting insights from the data.
**Data Visualization:**

* **Tableau**: For interactive and insightful visualizations in the Crime Analysis.twb workbook.
* **Dataset:**
    * **CSV File**: districtwise-cyber-crimes-2017-onwards.csv is the dataset I'm using for exploratory data analysis and training my models.
## Run Locally


Clone the repository:
   ```bash
   git clone https://github.com/anubhavlal07/Cyber-Crime-Analysis-And-Prediction.git
   cd Cyber-Crime-Analysis-And-Prediction
   ```
## Screenshots
**Tableau Dashboard**

![App Screenshot](https://raw.githubusercontent.com/anubhavlal07/Cyber-Crime-Analysis-And-Prediction/refs/heads/main/cyberCrimeDashboard.png?token=GHSAT0AAAAAACYRDV5RTS2IB2BSNQ32UC46Z4XSHJA)

## Contributing

We welcome contributions to this project. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.