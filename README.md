# IBM-AI
# Market Basket Analysis

This project performs Market Basket Analysis using the Apriori algorithm to discover patterns in customer purchase behavior. Follow these steps to run the code in a Jupyter Notebook environment.


## Dataset Description
The dataset used for this project is available on __[Kaggle Market Basket Analysis Dataset](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)__. It contains transaction data from a retail store. The dataset comprises information about customer transactions, including details about the items purchased, their quantities, prices, customer IDs, and the country where the transaction occurred. Here is a brief overview of the dataset's key attributes:

<div class="alert alert-block alert-info">
    <ul>
        <li><b>Itemname:</b> The name or description of the product or item purchased.</li>
        <li><b>Quantity:</b> The quantity of each item purchased in a transaction.</li>
        <li><b>Price:</b> The price of each item.</li>
        <li><b>CustomerID:</b> Unique identifier for each customer.</li>
        <li><b>Country:</b> The country where the transaction took place.</li>
        <li><b>BillNo:</b> A unique identifier for each transaction or bill.</li>
        <li><b>SumPrice:</b> The total price for each item in a transaction (calculated as Quantity * Price).</li>
    </ul>
</div>

## Prerequisites

1. Make sure you have Anaconda installed on your computer.

## Getting Started

1. Open Anaconda Navigator.
2. Launch Jupyter Notebook from Anaconda Navigator.
3. In the Jupyter Notebook, navigate to the directory where you want to save this project.
4. In your web browser, go to the GitHub repository where the project files are hosted: [GitHub Repository Link](https://github.com/suhaibpalli/IBM-AI).
5. Click on the "Code" button and select "Download ZIP" to download the entire project as a ZIP file.
6. Extract the ZIP file to your chosen directory.
7. Inside the extracted folder, you will find the Jupyter Notebook file named `AI_Phase5.ipynb`. Open this file by clicking on it.

## Running the Code

1. Once the Jupyter Notebook is open, you will find all the project code and documentation.
2. In the Jupyter Notebook, run each cell one by one. Make sure to execute them in sequential order.
3. The code will start by importing an Excel file from your computer. 
5. Review the project documentation within the Jupyter Notebook for insights and results.

## Dependencies

Ensure that you have the following Python packages installed within your Anaconda environment:
- pandas
- numpy
- matplotlib
- mlxtend
- mpld3

You can install these packages using the Anaconda Navigator environment or by running the following commands in a Jupyter Notebook cell:

```python
!pip install pandas numpy matplotlib mlxtend mpld3
```

> [!NOTE]
> __This README file includes instructions for downloading the Jupyter Notebook from a GitHub repository, importing an Excel file, and running the code in a Jupyter Notebook environment.__
