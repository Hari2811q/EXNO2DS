# EXNO2DS
## NAME: HAROPRASATH R
## REG NO: 212223040059
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        ```
        import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv('titanic_dataset.csv')
df
<img width="855" height="489" alt="Screenshot 2025-09-15 113637" src="https://github.com/user-attachments/assets/92799724-2c98-4a4a-a6ff-5263f22aeda4" />
<img width="854" height="445" alt="Screenshot 2025-09-15 113647" src="https://github.com/user-attachments/assets/b043191a-d76e-4437-94ba-2dc9ca509c63" />
<img width="868" height="639" alt="Screenshot 2025-09-15 113659" src="https://github.com/user-attachments/assets/d0c43ea7-f1bf-4afe-b7f2-968c4e03e522" />
<img width="847" height="93" alt="Screenshot 2025-09-15 113708" src="https://github.com/user-attachments/assets/beb2db6d-c726-4347-9c6b-bc2f6c41cd12" />
<img width="843" height="638" alt="Screenshot 2025-09-15 113720" src="https://github.com/user-attachments/assets/213ef51c-c5ad-4da9-92d7-921d01c6fc2b" />
<img width="843" height="650" alt="Screenshot 2025-09-15 113738" src="https://github.com/user-attachments/assets/51f67f86-65a1-4c93-b0bd-a88c5e674161" />
<img width="873" height="669" alt="Screenshot 2025-09-15 113911" src="https://github.com/user-attachments/assets/473d52e7-6ea5-4583-9506-95d7276ad90c" />
<img width="779" height="575" alt="Screenshot 2025-09-15 113919" src="https://github.com/user-attachments/assets/851847ad-c323-48a6-95bc-2bbb3bc6b31e" />
<img width="815" height="571" alt="Screenshot 2025-09-15 114024" src="https://github.com/user-attachments/assets/49288e97-c472-45af-ae0d-5f036ebd1205" />
<img width="1381" height="663" alt="Screenshot 2025-09-15 114043" src="https://github.com/user-attachments/assets/33047610-67ca-4b0d-904d-42eb4149151f" />
<img width="934" height="669" alt="Screenshot 2025-09-15 114057" src="https://github.com/user-attachments/assets/5b5cb9b1-d3a0-49d5-bfd1-5000799b6941" />
<img width="887" height="651" alt="Screenshot 2025-09-15 114111" src="https://github.com/user-attachments/assets/c71cff5d-cc07-4f56-9d43-61c546c2d7b3" />
<img width="842" height="585" alt="Screenshot 2025-09-15 114602" src="https://github.com/user-attachments/assets/9369675c-64c3-4136-8d3c-a0c547f5d1e8" />
<img width="860" height="585" alt="Screenshot 2025-09-15 114627" src="https://github.com/user-attachments/assets/80c49b61-dba3-4ed0-8bdd-f9c77eb2e781" />
<img width="1398" height="652" alt="Screenshot 2025-09-15 114651" src="https://github.com/user-attachments/assets/3426727a-5895-457e-bf31-434c6b554c1a" />
<img width="824" height="633" alt="Screenshot 2025-09-15 114659" src="https://github.com/user-attachments/assets/f994c0a9-d39e-464c-adbc-f05526138351" />
```

# RESULT
           Hence the program to perform Exploratory Data Analysis on the given data set has been done successfully.
