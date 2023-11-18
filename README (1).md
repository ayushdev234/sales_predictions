
# Customer Segmentation

This project revolves around predicting sales for a mart, drawing insights from a comprehensive dataset. The dataset encompasses diverse factors, ranging from item attributes like weight, fat content, and visibility, to outlet details such as establishment year, size, location, and type. The key focus is on estimating item sales within each outlet, facilitating a deeper understanding of the factors influencing sales patterns. 



## Dependencies
* Python 2.7 or Python >3.4
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* jupyter notebook
## Dataset
| Item_Identifier | Item_Weight | Item_Fat_Content | Item_Visibility | Item_Type    | Item_MRP | Outlet_Identifier | Outlet_Establishment_Year | Outlet_Size | Outlet_Location_Type | Outlet_Type        |
|------------------|-------------|-------------------|------------------|--------------|----------|---------------------|---------------------------|-------------|-----------------------|--------------------|
| FDW58            | 20.75       | Low Fat           | 0.007564836      | Snack Foods  | 107.8622 | OUT049              | 1999                      | Medium      | Tier 1                | Supermarket Type1  |
| FDW14            | 8.3         | reg               | 0.038427677      | Dairy        | 87.3198  | OUT017              | 2007                      |             | Tier 2                | Supermarket Type1  |
| NCN55            | 14.6        | Low Fat           | 0.099574908      | Others       | 241.7538 | OUT010              | 1998                      |             | Tier 3                | Grocery Store      |

..
..
.....
## Screenshots

![App Screenshot]()
![App Screenshot]()
![App Screenshot]()


## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```



Run the code given in ipython notebook ``


## Features

## Features

**Linear Regression:**

- *Linearity:* Assumes a linear relationship between the independent and dependent variables.

- *Assumption of Homoscedasticity:* Assumes constant variance of errors across all levels of the independent variables.

- *Assumption of Independence:* Assumes that errors are independent of each other.

- *Sensitive to Outliers:* Linear regression is sensitive to outliers, which can disproportionately influence the model.

- *Limited Expressiveness:* Might not capture complex, non-linear relationships in the data.

**Random Forest:**

- *Ensemble Method:* Random Forest is an ensemble of decision trees, combining their predictions to improve accuracy and robustness.

- *Non-linearity:* Capable of capturing non-linear relationships in the data.

- *Reduced Overfitting:* Ensemble nature helps reduce overfitting, especially when compared to individual decision trees.

- *Handling Missing Values:* Can handle missing values in the dataset.

- *Outlier Robustness:* More robust to outliers compared to individual decision trees.

- *Versatility:* Suitable for both classification and regression tasks.

- *Highly Parametrizable:* Allows tuning hyperparameters for better performance.
