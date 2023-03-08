# Project-2: Jumping the Middle Class Gap
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
![alt text](https://github.com/Elispreng/Project-2/commit/b399030782a8d414d26eb52cabd743cab0c78107)

This barplot shows a relationship between income and age. More specifically, the liklihood of earning more than 50K occurs in the mid-forties. 

#### Visual 2 Bar  Graph Showing Outlet Year and MRP

![alt text](https://github.com/Elispreng/Project-2/commit/b399030782a8d414d26eb52cabd743cab0c78107)


These two provide a surprising outcome. They show that the most important factor is age in achieving a 50K income: neither gender or education affect this economic
outcome

## Machine learning and metrics
- Baseline Model
- Logistic Regression with PCA Model
- Random Forest Model

### Baseling Metrics:
 precision    recall  f1-score   support

       <=50K       0.76      1.00      0.86     27831
        >50K       0.00      0.00      0.00      8761

    accuracy                           0.76     36592
   macro avg       0.38      0.50      0.43     36592
weighted avg       0.58      0.76      0.66     36592


### Logistic Regression with PCA Metrics Test Scores
    precision    recall  f1-score   support

       <=50K       0.87      0.93      0.90      9278
        >50K       0.72      0.56      0.63      2920

    accuracy                           0.84     12198
   macro avg       0.80      0.75      0.77     12198
weighted avg       0.84      0.84      0.84     12198


### Random Forest Model Test Scores
             precision    recall  f1-score   support

       <=50K       0.87      0.93      0.90      9278
        >50K       0.71      0.57      0.63      2920

    accuracy                           0.84     12198
   macro avg       0.79      0.75      0.77     12198
weighted avg       0.83      0.84      0.84     12198

## Recommendations:

From these metrics, the random forest model is the best model with the lowest error and highest R2. However, there is still some variance in this model. 

## Limitations & Next Steps

This project will include more graphics. Another limitation is the dataset which does not match US Census statistics. 

### For further information


For any additional questions, please contact **doctor.eemail@gmail.com**
