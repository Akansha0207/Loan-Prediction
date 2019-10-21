Problem Statement:
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.
The company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


The Data:
Variable	                        Description
Loan_ID	                          Unique Loan ID
Gender	                          Male/ Female
Married	                          Applicant married (Y/N)
Dependents	                      Number of dependents
Education	                        Applicant Education (Graduate/ Under Graduate)
Self_Employed                   	Self employed (Y/N)
ApplicantIncome                  	Applicant income
CoapplicantIncome                	Coapplicant income
LoanAmount	                      Loan amount in thousands
Loan_Amount_Term                  Term of loan in months
Credit_History	                   credit history meets guidelines
Property_Area	                     Urban/ Semi Urban/ Rural
Loan_Status	                       Loan approved (Y/N)

Performed EDAs to make inferences about the data followed by distribution analysis, data cleaning, feature engineering, and model building.

I have applied PCA algorithm to reduce the data into two dimensions to visualize the classification of data using some classification techniques such as Logistic Regression, Decision Tree, Random Forest Classifier,SVM, Naive Bayes in order to predict the accuracy.
