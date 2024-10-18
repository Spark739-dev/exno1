# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
![command to display the data using read csv command 1](https://github.com/user-attachments/assets/414306e7-2a31-4aad-bb67-3cf3b0d5004e)
![image](https://github.com/user-attachments/assets/5e6386b4-659c-4fa9-8bcf-71f1ceaf217f)
![df describe() command 3](https://github.com/user-attachments/assets/d66d5671-6ff0-452e-aae5-09be3e1556d0)
![df head(6)](https://github.com/user-attachments/assets/3a9f745e-85b9-4fc1-9820-cbc8319516d5)
![df tail(5)](https://github.com/user-attachments/assets/9d47492c-80f7-4a7a-9e02-145b0bb30327)
![df isnull()](https://github.com/user-attachments/assets/424f044a-7d5a-4a00-96fa-31b7198cc56d)
![df notnull()](https://github.com/user-attachments/assets/a87a5053-6f54-4001-a92c-e3fa03922f94)
![df dropna(axis=0)](https://github.com/user-attachments/assets/b87c72ff-dd34-4e23-a2dc-ce5d7abb0ce5)
![df dropna(axis=1)](https://github.com/user-attachments/assets/f197ae1b-eeed-47cb-be08-d44f1f63a4bc)
![df df 'numofeps'  greater than 20](https://github.com/user-attachments/assets/b837498c-df60-4153-8530-f3f0f571d4da)
![df 'noofeps  greater than 20 but not  table](https://github.com/user-attachments/assets/dd3e312d-9a97-4d04-a85c-f2d6220527e5)
![df fillna(0)](https://github.com/user-attachments/assets/c79ec1e0-7d16-48d6-97e3-eaabe2b88438)
![df fillna(df 'ratings' mean())](https://github.com/user-attachments/assets/3008a7d6-01ea-49e6-bd7e-fe010388e8cc)
![df iloc display only 1,2,3 rows and colums without using index value](https://github.com/user-attachments/assets/7f5f8953-799e-47a8-9930-f5f807aab3ba)
![df iloc 3,3 ,To display only 0,1,2 rows and colums](https://github.com/user-attachments/assets/990eb862-3de2-4f21-810d-9e868f649f80)
![df fillna(method='bfill')](https://github.com/user-attachments/assets/db50f715-4cff-47fa-99c0-e64f68fc25eb)
![image](https://github.com/user-attachments/assets/f2dac7b0-102a-4955-904b-5e1fe28014b5)
![df show() command 2](https://github.com/user-attachments/assets/a42c6c85-90ad-4481-8455-cddbbe82dbb2)
![df shape](https://github.com/user-attachments/assets/aa4fa985-d9dd-496b-88eb-185f0efcdcb8)
![sns boxplot](https://github.com/user-attachments/assets/fa371415-3bca-4d7a-b58e-d82e04241971)
![sns scatterplot](https://github.com/user-attachments/assets/5774dd70-544d-4d61-b064-f48deb03b0ef)
![outliers dectection 1](https://github.com/user-attachments/assets/79650156-f409-4c15-882b-35e38bce4255)
![outliers dectection 2](https://github.com/user-attachments/assets/70363a8f-f5d1-45bf-99f9-2f007be21b4c)
![outliers fixed 1](https://github.com/user-attachments/assets/faf3abba-bb11-43bd-809c-22c4cbbd8707)
![outliers fixed 2](https://github.com/user-attachments/assets/deace4e5-2bb1-4b75-8147-4c7756534a65)
![image](https://github.com/user-attachments/assets/a3499e99-6718-4b01-ae46-f8fa86a8fa73)
![image](https://github.com/user-attachments/assets/24297e38-e7d5-4e10-a29d-e62faed8a4d5)
![image](https://github.com/user-attachments/assets/9b759ae4-032d-44a1-896c-a622693d8d05)
![image](https://github.com/user-attachments/assets/f2585bd0-8ec6-47f1-8aeb-6542cf39ed2e)





























# Result
Thus we have read and cleaned the data and also removed the outliers by detection using IQR and Z-score method.
