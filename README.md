# Sales Forecast Program

## Overview
The Sales Forecast Program is a Linear Regression ML model application designed to predict future sales based on historical data. By leveraging advanced algorithms and data visualization techniques, this program provides insights to help businesses make informed decisions.

## Technologies Used
- **Python**: The primary programming language used for development.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Scikit-Learn**: For implementing machine learning algorithms.
- **Google Colab**: For an easy-to-use cloud-based platform to run the notebook.

## Features
- Data preprocessing and cleaning
- Exploratory data analysis (EDA) with visualizations
- Multiple machine learning models for sales prediction
- Performance evaluation metrics to assess model accuracy
- User-friendly interface in Jupyter Notebook

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Anaconda, Jupyter Notebook, Google Colab or VsCode (choose what it fits better to you)

## How to Use the Program on Different Platforms

### Anaconda
To use the Sales Forecast Program with Anaconda, follow these steps:

1. **Install Anaconda**: If you haven't installed Anaconda yet, download it from [Anaconda's official website](https://www.anaconda.com/products/distribution#download-section).

2. **Clone the Repository**:
   Open Anaconda Prompt and run:
   ```bash
   git clone https://github.com/luanfelixcoding/SalesForecast-ML.git
   cd SalesForecast-ML

3. **Create a New Environment (optional,but recommended)**:
   ```bash
   conda create --name sales_forecast python=3.x
   conda activate sales_forecast

4. **Install required packages**: 
   ```bash
   pip install pandas matplotlib scikit-learn

5. **Launch Jupyter Notebook**
   ```bash
      jupyter notebook

Open ``Sales_Forecast.ipynb`` from the Jupyter interface.

### VSCode
To use the Sales Forecast Program in Visual Studio Code: 

1. **Install VSCode:** Download it from [VSCode's official website](https://code.visualstudio.com/download).

2. **Install Python Extension:** Make sure to install the Python extension for VSCode.

3. **Clone the Repository:** 
   
   Open a terminal in VSCode and run:
   ```bash
   git clone https://github.com/luanfelixcoding/SalesForecast-ML.git
   cd SalesForecast-ML

4. **Set Up a Virtual Environment (optional, but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   .\venv\Scripts\activate  # On Windows

5. **Install required packages:**
   ```bash
   pip install pandas matplotlib scikit-learn

6. **Open the Notebook** 
You can either open the notebook directly or convert it to a Python script. To run the notebook, you might need the Jupyter extension.


### Google Colab
To use the Sales Forecast Program on Google Colab:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/) website.

2. **Clone the Repository: In a new notebook cell, run:**
   ```bash
   !git clone https://github.com/luanfelixcoding/SalesForecast-ML.git

3. **Install Required Packages: Also in a new cell, run:**
   ```bash
   !pip install pandas matplotlib scikit-learn

4. **Navigate to the Notebook:**  
   You can either upload the Sales_Forecast.ipynb file or run it directly from the cloned repository:
   ```bash
   %cd sales_forecast

5. **Run the Notebook:**
Follow the cells in the notebook to execute the program.

### How to tweak this project for your own uses

Since this is a simple example project, I would encourage you to clone and rename this project to use your own purposes as well as have extra libraries in code for other cases.
