
Heart Disease Prediction
--------------------------
Dataset
----------------------------
The dataset is in the xlsx file called- heart_disease.xlsx
You can find the data set in the repository

About the dataset
----------------------------
Content: This database contains 13 attributes (which have been extracted from
a larger set of 75)       

Attribute Information:
------------------------
      -- 1. age       
      -- 2. sex       
      -- 3. chest pain type  (4 values)       
      -- 4. resting blood pressure  
      -- 5. serum cholestoral in mg/dl      
      -- 6. fasting blood sugar > 120 mg/dl       
      -- 7. resting electrocardiographic results  (values 0,1,2) 
      -- 8. maximum heart rate achieved  
      -- 9. exercise induced angina    
      -- 10. oldpeak = ST depression induced by exercise relative to rest   
      -- 11. the slope of the peak exercise ST segment     
      -- 12. number of major vessels (0-3) colored by flourosopy        
      -- 13.  thal: 3 = normal; 6 = fixed defect; 7 = reversable defect     

Attributes types
-----------------

Real: 1,4,5,8,10,12
Ordered:11,
Binary: 2,6,9
Nominal:7,3,13

Variable to be predicted
------------------------
Absence (1) or presence (2) of heart disease

Code for the project
--------------------------
The notebook for this project can be found in Heart Disease Prediction.ipynb

Classification model
----------------------------
Build a KNN classifier and a logistic regression classifer. Based on their performance on the training and validtion dataset.
Apply the best classifer and test perfomance on the test set.
