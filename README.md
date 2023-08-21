# Credit Card Fraud Detection

## Problem Statement
In contemporary banking, retaining high-value customers is a paramount goal, driving strategic operations. However, the looming threat of banking fraud poses a significant challenge across banks, impacting not just financial losses but also trust. The adoption of machine learning and deep learning for credit card fraud detection is a necessity now. These technologies empower banks to establish proactive monitoring and fortified fraud prevention mechanisms, reducing manual reviews, chargebacks, and transaction denials. Machine learning optimizes operations, mitigates resource burdens, and addresses financial strains, enhancing overall efficiency.

The primary objective of this project is to employ advanced machine learning models to detect fraudulent credit card transactions. Leveraging customer-level data acquired and analyzed through a collaborative effort between Worldline and the Machine Learning Group, the project seeks to address the critical challenge of credit card fraud.

## Dataset Description
The dataset encompasses credit card transactions executed by European cardholders during September 2013. This dataset encompasses a total of 284,807 transactions over a two-day timeframe, with 492 instances flagged as fraudulent, constituting a mere 0.172% of the total transactions.

Notably, the dataset exclusively comprises numerical input variables, meticulously generated through a PCA transformation. Unfortunately, the original features and supplementary contextual insights remain undisclosed due to confidentiality constraints. Specifically, the features denoted as V1 through V28 correspond to principal components resulting from PCA analysis. It's important to highlight that the attributes 'Time' and 'Amount' have not undergone the PCA transformation.

- **Time**: Represents the seconds elapsed between the current transaction and the first transaction in the dataset.
- **Amount**: Represents the total transaction value.

The response variable, **Class**, has two values:
- 1 for fraudulent cases
- 0 for non-fraudulent cases
