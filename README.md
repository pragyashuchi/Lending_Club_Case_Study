# Lending-Club-Case-Study

The organisation **Lending Club** is as a peer-to-peer company that acts as a marketplace for matching possible investors with available loan applicants. 
Once an Applicant applies for a loan, the company performs a risk assessment based on the applicant's profile.
Approving loans on risky applicants can lead to financial losses, while rejecting loan approvals for safe applicants lead to loss of business.

This Case Study aims at determining the driving factors behind Loan Defaulting.
<br/>
<br/>
### Table of Contents inside the Notebook:

- **Data Exploration and Cleaning:** Data types, Missing Values, Variance etc.
- **Univariate Analysis:** Distribution plots, barplots, boxplots, pie charts etc.
- **Segmented Univariate Analysis:** Segmented Univariate Plots
- **Bivariate Analysis:** Bivariate Boxplots and Side-by-Side barplots.
- **Multivariate Analysis:** Multiplot side-by-side bargraphs, Clustermaps etc.
- Final Observations and Inference

<br/>
<br/>

**Background:** This Case Study is a Part of Statistics Essentials Course of the Exec. Post Graduate Programme by IIIT-Bangalore in Association with UpGrad.
<br/>
<br/>

**Dataset:** The Dataset is provided by the Institute and contains the historical Customer Demographic and Loan Information data of the applicants. It has 39717 rows and 111 columns. 

_Note:_
_- Unzip the data loan.csv from 'input_files/' before running the notebook_


<br/>
<br/>

**Technology/Libraries used:**
- NumPy: 1.20.1
- Pandas: 1.2.4
- Matplotlib: 3.3.4
- Seaborn: 0.11.1


<br/>
<br/>

**Final Observation and Inference** _[Also available at the end of the notebook]_ <br/>
- The Probability of Defaulting increases for applicants with a higher loan to income ratio (> 25% of their yearly income). <br/>
- The Probability of Defaulting increases for applicants with a higher installment to income ratio (>9% of their monthly income)<br/>
- The Probability of Defaulting Increases for applicants with a Credit Utilisation Rate of greater than 0.77 (or 77%)<br/>
- A loan lent out at a higher term of 60 months has more probability of being defaulted <br/>
    + For applicants with more than 25% loan_to_income_ratio, the percentage of defaulting is around 30%. <br/>
    + For applicants with installment amounts greater than 8% of their monthly income, the percentage of defaulting is 30-40%. <br/>
    + When the interest rate is more than 14%, the percentage of defaulting is around 30%. <br/>
- Applicants who live on Rent or Mortgaged property have higher chances of defaulting when the loan amount is high. <br/>
- Applicants with purpose of loan as Small Business, Credit-Card loan or Debt Consolidation have higher chances of defaulting when the loan amount is high. <br/>
