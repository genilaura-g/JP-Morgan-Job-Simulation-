# JP-Morgan-Job-Simulation-
JP Morgan Job Simulation for quantitative research Task 2 &amp; 3 
## README: JP Morgan - Quant Researcher Simulation

This project simulates two financial tasks:

**1. Natural Gas Storage Contract Pricing**

This section describes a prototype function for pricing natural gas storage contracts. The function considers various factors like injection/withdrawal dates, purchase/sale prices, storage costs, injection/withdrawal costs, and potential transportation costs.

**Key Inputs:**

- Injection dates
- Withdrawal dates
- Commodity prices (purchase/sale) on those dates
- Injection/withdrawal rate
- Maximum storage volume
- Storage costs

**Function:**

The `trade_agreement` function calculates the contract value by subtracting the purchase price and additional costs (storage, injection/withdrawal, transportation) from the sale price, all scaled by the volume (1 million MMBtu).

**Testing:**

The provided code demonstrates usage with sample inputs.

**2. Loan Default Prediction Model**

This section explores building a model to predict loan default probability (PD) for a risk manager. The model is trained using historical loan data that includes borrower details like income, outstanding loans, and past default history.

**Data:**

The data is assumed to be in a CSV file (`/content/Task 3 and 4_Loan_Data.csv`) containing borrower properties and a label indicating past defaults.

**Model:**

The code implements a decision tree classifier (`DecisionTreeClassifier`) to predict loan default based on borrower characteristics.

**Evaluation:**

The model is evaluated using training and test sets. Classification accuracy, confusion matrix, and classification report are presented.

**Further Exploration:**

The code includes comments for exploring alternative methods like GradientBoostingClassifier.

**Libraries:**

* pandas
* seaborn
* numpy
* matplotlib.pyplot
* sklearn (various modules)

**Note:**

This is a basic simulation for educational purposes. Real-world financial applications might require more complex models and risk management considerations.
