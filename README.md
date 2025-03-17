# ***ML-Assignment-4-Classification Problem***  

#      ***Breast-Cancer-Prediction***
***Import Libraries***
![image](https://github.com/user-attachments/assets/23f1f95e-f347-4921-a7f7-a6534a008240)
# ***1.	Loading and Preprocessing*** 

***Loading and Preprocessing--
Load the breast cancer dataset from sklearn using the load_breast_cancer function from sklearn***
![image](https://github.com/user-attachments/assets/5bbb8166-bc3f-4999-b401-c060467dcfb5)
![image](https://github.com/user-attachments/assets/ed38ea0c-1692-4ef9-b9fc-42e3a842b493)
![image](https://github.com/user-attachments/assets/32d1b953-b29d-4603-9381-1bff3661d50c)
![image](https://github.com/user-attachments/assets/b18ef361-a20e-4bc5-9a52-db402fa2fb7e)
***There is no missing values in the dataset,so need not imputation for this dataset.***
![image](https://github.com/user-attachments/assets/5cc941ab-64c3-4045-b6c7-1b7662db249f)
***check the number of duplicate rows***
![image](https://github.com/user-attachments/assets/f48d88c5-e585-4385-ae95-df6f6b9e6dc4)
![image](https://github.com/user-attachments/assets/9847a181-3720-4456-9b4e-04f3c3208d7c)
# Breast cancer wisconsin (diagnostic) dataset


**Data Set Characteristics:**

***:Number of Instances: 569***

***:Number of Attributes: 30 numeric, predictive attributes and the class***

***:Attribute Information:
    - radius (mean of distances from center to points on the perimeter)  
    - texture (standard deviation of gray-scale values)  
    - perimeter  
    - area  
    - smoothness (local variation in radius lengths)  
    - compactness (perimeter^2 / area - 1.0)  
    - concavity (severity of concave portions of the contour)  
    - concave points (number of concave portions of the contour)  
    - symmetry  
    - fractal dimension ("coastline approximation" - 1)***  

***The mean, standard error, and "worst" or largest (mean of the three
    worst/largest values) of these features were computed for each image,
    resulting in 30 features.  For instance, field 0 is Mean Radius, field
    10 is Radius SE, field 20 is Worst Radius.***

***- class:
        - WDBC-Malignant  
            - WDBC-Benign***   



            
***The above details are available by executing the code block "print(cancer.DESCR)"***

![image](https://github.com/user-attachments/assets/584733be-ce64-47ba-9782-758fe08cf9cb)

# ***2. Classification Algorithm Implementation***

![image](https://github.com/user-attachments/assets/1b5f8efe-57da-49b8-9307-d2f236f5b4ec)
***Standarize the feature***
![image](https://github.com/user-attachments/assets/a0198791-769e-492a-9cd8-30477479c566)
# ***3. Logistic Regression***
![image](https://github.com/user-attachments/assets/803de034-3c26-4e81-87b2-315035fab717)
![image](https://github.com/user-attachments/assets/2997ec2d-5088-4375-9852-7b7598d6ea56)
# ***4.Decision Tree Classifier***
![image](https://github.com/user-attachments/assets/e097f873-924b-43d4-82c3-25222b64622a)
![image](https://github.com/user-attachments/assets/57f4cbf3-713c-4872-b66c-897232b3c147)
# ***5. Random Forest Classifier***
![image](https://github.com/user-attachments/assets/e9730ba5-08ac-46c1-b017-a86d553503b9)
![image](https://github.com/user-attachments/assets/513fa95c-8af7-4d0c-88f2-a87ed5863199)
# ***6. Support Vector Machine (SVM)***
![image](https://github.com/user-attachments/assets/60a7f85c-d4bd-47b5-9137-8d350cf4a9e8)
![image](https://github.com/user-attachments/assets/d7d98347-97fe-4d48-a320-74a727a51352)
#  ***7. k-Nearest Neighbors (k-NN)***
![image](https://github.com/user-attachments/assets/37b25664-cbda-4b8f-8264-3dfbb1a16caa)
![image](https://github.com/user-attachments/assets/d90e66d5-1aba-4406-8419-6bcb6ec25d74)
# ***8. Compare the performance of the five classification algorithms. Which algorithm performed the best and which one performed the worst?***
![image](https://github.com/user-attachments/assets/a985f25d-11d4-4773-82f7-e68a965a01e0)

