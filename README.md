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
# Importing pandas library and reading csv file

<img width="723" height="103" alt="image" src="https://github.com/user-attachments/assets/0f81bc46-3ff4-4a46-b7ec-d004f859c3d2" />

# Displaying information about csv file and performing basic data analysis functions

<img width="492" height="460" alt="image" src="https://github.com/user-attachments/assets/9b50e8c4-7295-4daf-a969-8e07804f1d18" />

<img width="1258" height="315" alt="image" src="https://github.com/user-attachments/assets/f0101415-b2c7-4c0a-89ba-3ae6c50f254b" />

<img width="1260" height="312" alt="image" src="https://github.com/user-attachments/assets/ed7c4703-a125-447a-89c8-4b242d8a6cfe" />

<img width="125" height="87" alt="image" src="https://github.com/user-attachments/assets/b8ddd127-1357-46c9-a8c0-97d60e95f1f6" />

# Checking for NULL values in the dataset

<img width="822" height="592" alt="image" src="https://github.com/user-attachments/assets/0d2cca92-0776-4a2c-bfa1-21dbba39f725" />

# Display the sum of NULL values in each row

<img width="351" height="327" alt="image" src="https://github.com/user-attachments/assets/874c8d80-1a1d-4aa4-b8fd-4090428e7e65" />

# Drop NULL values

<img width="842" height="603" alt="image" src="https://github.com/user-attachments/assets/1d7d095a-cd28-45c5-8800-4a34dbba5fea" />

# Fill NULL values with constant value "O"

<img width="1362" height="566" alt="image" src="https://github.com/user-attachments/assets/2db0ac98-6b0b-433d-b9ec-d11b254e0c53" />

# Fill NULL values with ffill or bfill method

<img width="850" height="590" alt="image" src="https://github.com/user-attachments/assets/dbe3e036-9eac-416c-a2da-38c164430627" />

<img width="832" height="603" alt="image" src="https://github.com/user-attachments/assets/b05c0c43-f513-46ec-8969-2d9b21198f09" />

# Calculate mean value of a column and fill NULL values with it

<img width="760" height="307" alt="image" src="https://github.com/user-attachments/assets/7d52a0fa-48c5-4c4e-a202-c75e5b09e4a6" />

# Use boxplot function to detect outlier

<img width="857" height="666" alt="image" src="https://github.com/user-attachments/assets/fc149882-6ca5-48b0-aeff-e27d29d8974b" />

# Perform IQR method and detect outlier values

<img width="419" height="614" alt="image" src="https://github.com/user-attachments/assets/554dc3ab-1f7e-4047-a8e1-43823101bee1" />

# Use boxplot function again to check if outlier is removed

<img width="847" height="607" alt="image" src="https://github.com/user-attachments/assets/41fbd5fb-d2cf-4dd4-9a8b-d266751e1460" />

# Applying stats method to implement Z Score method

<img width="1114" height="666" alt="image" src="https://github.com/user-attachments/assets/5ddb658f-9618-4ea1-a2b1-dac2787c904a" />

# Perform Z Score method and detect outlier values

<img width="366" height="332" alt="image" src="https://github.com/user-attachments/assets/5050c716-f561-44c1-97de-a93b2fcda330" />

# Use boxplot function here to check if outlier is removed

<img width="812" height="603" alt="image" src="https://github.com/user-attachments/assets/a9732a8b-eac5-495f-9b7b-bec4db8ee1aa" />

# Result
Therefore, data cleaning steps are successfully executed to prepare data for further processing.  
