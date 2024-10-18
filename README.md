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
![command to display the data using read csv command 1](https://github.com/user-attachments/assets/a0ff4d70-97db-4843-8537-2e0a01f3943f)
![Screenshot 2024-10-18 140410](https://github.com/user-attachments/assets/a4d39ae2-ae67-47b1-8cca-256ec13d8be0)
![df show() command 2](https://github.com/user-attachments/assets/9b281c35-5d74-41c2-8a97-c4dd4bf4ec54)
![df describe() command 3](https://github.com/user-attachments/assets/0409d224-c978-4639-a968-c6c19ba0b67d)
![df head(6)](https://github.com/user-attachments/assets/822299a6-810f-4c34-8853-3093ee60e003)
![df tail(5)](https://github.com/user-attachments/assets/91382fcd-cf44-4c49-837b-7cd52555491a)
![df isnull()](https://github.com/user-attachments/assets/39309923-d658-46a1-89a8-b1380e4d8aff)
![df notnull()](https://github.com/user-attachments/assets/ac345b67-f028-4c42-8686-312d7d303ce1)
![df dropna(axis=0)](https://github.com/user-attachments/assets/111e2a74-33fd-42d2-9ada-fd2097fb157e)
![df dropna(axis=1)](https://github.com/user-attachments/assets/a5a78d8d-0437-44d9-9e92-7f57d4047cc6)
![df df 'numofeps'  greater than 20](https://github.com/user-attachments/assets/3e2548c3-826b-4afd-9c77-4f368ce2ae57)
![df df 'numofeps'  greater than 20](https://github.com/user-attachments/assets/a58dacf1-e6d9-4126-a91c-23328ef5d760)
![df iloc display only 1,2,3 rows and 1,3,5 colums without using index value](https://github.com/user-attachments/assets/08a896c1-2d2d-4352-aab3-8d20c9d100dc)
![df iloc 3,3 ,To display only 0,1,2 rows and colums](https://github.com/user-attachments/assets/4c2c4c64-4f42-41a6-a8b5-28b66188da2c)
![df fillna(0)](https://github.com/user-attachments/assets/a8531bca-ab9d-4648-9a81-35e7873c790c)
![df fillna(method='bfill')](https://github.com/user-attachments/assets/b0bf0a61-22cb-4519-9e02-d4105547e902)
![Screenshot 2024-10-18 141827](https://github.com/user-attachments/assets/005ff9a5-b84c-4d07-8400-5b8c7db2436e)
![df fillna(df 'ratings' mean())](https://github.com/user-attachments/assets/2f4cd279-36e9-4c9c-b984-88a7f9018691)
![df shape](https://github.com/user-attachments/assets/e46c3987-ac2a-4995-abb4-0b0157c0436e)
![sns boxplot](https://github.com/user-attachments/assets/898cb214-a38e-4db0-ac0f-9fda7ede0545)
![sns scatterplot](https://github.com/user-attachments/assets/249ee372-0cb4-478c-a547-e6a950c42e9d)
![outliers dectection 1](https://github.com/user-attachments/assets/31d42d06-9c4c-4960-8997-dd05a030c466)
![outliers dectection 2](https://github.com/user-attachments/assets/826b10ba-570b-4880-a1c7-5e01cc9b533d)
![outliers fixed 1](https://github.com/user-attachments/assets/966be6fa-b584-4821-97a2-e90a462da056)
![outliers fixed 2](https://github.com/user-attachments/assets/a5b15c5c-50c1-4a19-953f-8026cef32d38)
![display fixed outliers using boxplot](https://github.com/user-attachments/assets/24416bc7-c8d2-49b2-a29d-82209938af36)
![Screenshot 2024-10-18 142449](https://github.com/user-attachments/assets/a9d35d13-1554-428d-83c2-2246f40dd923)
![image](https://github.com/user-attachments/assets/98ae6ab0-9507-4865-ad47-158c11f71128)
![Screenshot 2024-10-18 142700](https://github.com/user-attachments/assets/342d896f-e01f-4a29-89d6-e461849d6c4f)
![Screenshot 2024-10-18 141827](https://github.com/user-attachments/assets/95edfd5d-5103-4599-a7bb-dc6c451d23c6)


































# Result
Thus we have read and cleaned the data and also removed the outliers by detection using IQR and Z-score method.
