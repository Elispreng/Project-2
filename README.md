# Project-2: Jumping into the Middle Class 
![alt text](https://github.com/Elispreng/Project-2/blob/main/US%20Income.jpg)

# Data Science and American Middle Class
## Anazlyzing US Incomes Greater and Less Than 50K

**Eli Spreng**: 

### Topic:

This dataset looks at US residents who make more or less than fifty thousand dollars, a benchmark for lower middle class life. Interested parties may wonder what is
/are the most significant facors for entry into US middle class. 

### Data:
Adult Income Datat Set: [https://www.kaggle.com/datasets/wenruliu/adult-income-dataset]


## Methods
- To perform this analysis the data was cleaned and then exploratory and explanatory visuals offer insights
- Machine learning using classification metrics provides another way to understand the income group. 

## Results

#### Visual 1: Barplot Graph Showing Income and Age
![alt text](https://github.com/Elispreng/Project-2/blob/main/Income%20and%20Age.png)

This barplot shows a relationship between income and age. More specifically, the liklihood of earning more than 50K occurs in the mid-forties. 

#### Visual 2 Bar  Graph Showing Outlet Year and MRP

![alt text](https://github.com/Elispreng/Project-2/blob/main/Income_Education%20and%20Gender.png)


These two provide a surprising outcome. They show that the most important factor is age in achieving a 50K income: neither gender or education affect this economic
outcome

## Machine learning and metrics
- Baseline Model
- Logistic Regression with PCA Model
- Random Forest Model


### Random Forest Model Test Scores (Best Model)

------------------------------------------------------------
[i] CLASSIFICATION REPORT FOR: Test Data
------------------------------------------------------------
              precision    recall  f1-score   support

       <=50K       0.87      0.93      0.90      8638
        >50K       0.73      0.58      0.65      2853

    accuracy                           0.84     11491
   macro avg       0.80      0.76      0.77     11491
weighted avg       0.84      0.84      0.84     11491

         
     
## Recommendations:

From these metrics, the random forest model is the best model with the lowest error and highest R2. For interested stakeholders, more attention should be paid to age a
and educating people about wealth management and increasing their financial literacy regardless of educational status. Another recommendation is to aim these programs
at females to help move into the moiddle class sooner. Both  of these focused educational efforts  could help more people  attain greater finacial security earlier
in life. 

## Limitations & Next Steps

This project will include more graphics. Another limitation is the dataset which does not match US Census statistics. 

### For further information


For any additional questions, please contact **doctor.eemail@gmail.com**
