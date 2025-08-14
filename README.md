# Banking Data Analysis 📊

An exploratory data analysis (EDA) project focused on a banking dataset to uncover insights into customer demographics, behavior, and campaign outcomes.

---

## 📝 Project Overview

This project performs a comprehensive analysis of a dataset containing information about a bank's customers and their response to a marketing campaign. The primary goal is to identify key factors that influence whether a customer subscribes to a term deposit. The analysis involves data cleaning, visualization, and statistical exploration to extract actionable insights for the bank's marketing team.

---

## Dataset

The dataset used in this analysis contains anonymized information about bank clients. Key attributes include:

* **Demographics:** Age, job, marital status, education.
* **Financial Profile:** Default status, housing loan, personal loan.
* **Campaign History:** Contact type, last contact duration, number of contacts.
* **Outcome:** `y` - whether the client has subscribed to a term deposit (Yes/No).

*(You can add a link to the source of your dataset here, e.g., Kaggle or UCI Machine Learning Repository).*

---

## 💡 Key Analyses and Insights

The analysis, conducted in the main Jupyter Notebook (`analysis.ipynb`), explores several key questions:

* **Customer Demographics:** What is the profile of the bank's average customer? Visualizations explore distributions of age, job, and marital status.
* **Campaign Effectiveness:** How do factors like contact duration and the number of contacts affect the subscription rate?
* **Financial Health:** Is there a correlation between having existing loans (housing, personal) and subscribing to a new deposit?
* **Predictive Features:** Identification of the most influential features that determine whether a customer will subscribe.

---

## 💻 Technologies Used

* **Python**: Core language for data analysis.
* **Pandas**: For data manipulation and cleaning.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For creating static and interactive visualizations.
* **Jupyter Notebook**: As the primary environment for the analysis.

---

## 🚀 Getting Started

To run this analysis on your local machine, follow these steps.

### Prerequisites

* Python 3.8+
* pip package manager

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Rajangshu/banking_data_analysis.git](https://github.com/Rajangshu/banking_data_analysis.git)
    cd banking_data_analysis
    ```
2.  **Install required packages:**
    (It's recommended to create a `requirements.txt` file with your dependencies)
    ```bash
    pip install -r requirements.txt
    ```
    If you don't have a `requirements.txt` file, install the packages manually:
    ```bash
    pip install pandas numpy matplotlib seaborn jupyterlab
    ```

### Usage

1.  **Launch Jupyter Lab:**
    ```bash
    jupyter lab
    ```
2.  **Open and run the notebook:**
    Open the `analysis.ipynb` (or your notebook's name) file and run the cells sequentially to see the full analysis.

---

