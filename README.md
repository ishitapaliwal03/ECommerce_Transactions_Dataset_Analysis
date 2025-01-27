**eCommerce Transactions Data Science Assignment**

This repository contains the solution to the **Data Science Intern Assignment** involving an eCommerce transactions dataset. The project includes exploratory data analysis (EDA), a lookalike model, and customer segmentation tasks.

** Project Structure**

The project is divided into the following tasks:

### 1. **Exploratory Data Analysis (EDA)**
- **Objective**: Analyze the provided dataset to extract meaningful business insights.

### 2. **Lookalike Model**
- **Objective**: Build a model to recommend 3 similar customers for the first 20 customers (C0001–C0020) based on their profile and transaction history.

### 3. **Customer Segmentation / Clustering**
- **Objective**: Segment customers using clustering techniques to group them based on profiles and transaction information.

## Dataset Description

The dataset consists of three files:
1. **Customers.csv**  
   Contains customer profiles, including:
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Customer's continent.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**  
   Contains product details, including:
   - `ProductID`: Unique product identifier.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Price in USD.

3. **Transactions.csv**  
   Contains transaction details, including:
   - `TransactionID`: Unique transaction identifier.
   - `CustomerID`: ID of the customer making the transaction.
   - `ProductID`: ID of the purchased product.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity purchased.
   - `TotalValue`: Total value of the transaction.


## Getting Started

### Prerequisites
- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

### Setup
1. Clone this repository:
   ```
   git clone <repository_url>
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

### Running the Notebooks
1. Open the notebooks (`.ipynb`) in Jupyter Notebook or a compatible IDE.
2. Follow the instructions and execute cells to reproduce the results.


## Results

### EDA
The EDA results are documented in `Ishita_Paliwal_EDA.pdf`, highlighting key business insights derived from the dataset.

### Lookalike Model
The recommendations for the top 3 similar customers are saved in `Ishita_Paliwal__Lookalike.csv`.

### Clustering
The clustering results, along with the DB Index value and visualizations, are detailed in `Ishita_Paliwal__Clustering.pdf`.



