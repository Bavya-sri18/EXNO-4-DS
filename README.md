# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
 
![1](https://github.com/user-attachments/assets/e06c77c4-305b-4d82-a42d-1c8e3ee8dfe2)
![2](https://github.com/user-attachments/assets/21f15d09-5c48-4602-84dc-32618d3a866b)
![3](https://github.com/user-attachments/assets/d1c9e931-9504-4e78-ad49-e09732660e98)
![4](https://github.com/user-attachments/assets/0aedd806-1367-43bd-823b-0b37757d79c7)
![5](https://github.com/user-attachments/assets/76638307-3561-45cf-90d3-88da6a65e86e)
![6](https://github.com/user-attachments/assets/6d3067ae-4d6f-4964-9c45-6decfb6f15bf)
![7](https://github.com/user-attachments/assets/42ffecee-6e79-4ef1-8fb9-d13c661bd01b)
![8](https://github.com/user-attachments/assets/dc7a7f61-c400-4e4a-be0e-123477df4b7e)
![9](https://github.com/user-attachments/assets/88dc267a-748c-4c91-9e27-2a65709097d9)
![10](https://github.com/user-attachments/assets/a5ddb17a-f803-48d4-bd5e-1a063a2b519c)
![11](https://github.com/user-attachments/assets/90cbc85a-a2b9-4b75-b9c8-cdcb20fd22c8)
![12](https://github.com/user-attachments/assets/c8690dbb-c97b-4f95-a052-83a3530b1bac)
![13](https://github.com/user-attachments/assets/23016fe3-a08c-4655-a638-4dbbc4c6f273)
![14](https://github.com/user-attachments/assets/c373c736-9c9d-4ae7-86ac-784b6012e12d)
      
       
# RESULT:
       Thus, feature scaling using `StandardScaler` and selection using `SelectKBest` are performed, and the result is saved as a CSV file.
