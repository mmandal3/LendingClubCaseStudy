# Project Name
> Lending Club Loan data analysis


## Table of Contents
- Overview
- Understanding and scope of the assignment
- Analysis
- Preliminary observation and recommendation

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To assess the risk and identify applicants a data driven approach is needed to establish a model that can segregate with defined confidence level between possible defaulter and non-defaulter cases
- As a first step towards building a model from a representative dataset (population) – the data needs to be understood, analysed and made ready for subsequent step of model building
- The current scope of assignment is limited to perform data cleaning and analysis, which follows a preliminary recommendation based on data analysis
- An Exploratory Data Analysis (EDA) needs to be performed to preliminary screening of risky loan application from sample data set
- A representative data set in comma separated file format consisting of past sanctioned loan details
- Each loan record contains representative loan information containing key information like:
	Applicant’s demographic info (e.g., Residential status, Employment info, Salary etc.)
	Applied loan details (e.g., Type, Description, Interest rate, Terms, Grade, Applied Amount etc.)
	Sanctioned amount (e.g., Loan invested amount etc.)
	Repayment status
- There are 111 columns and 39717 rows available in provided datase
## Conclusions
- Applicant applying for lower interest rate scheme - chances of defaulting less
- Applicant without defined ownership defaulting - hence risk is high such applicants
- Chances of Applicant issued with longer term period of loan is high compared to lower term period - hence should invest in loan with less term period
- Higher the loan amount greater the risk of defaulting for applicant
- Better chances of full repayment is loan amount between 5000 to 14000. Hence should investing in this range less risky
- Investing in loan applied for business is more risky than loan applied for any other purpose

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
