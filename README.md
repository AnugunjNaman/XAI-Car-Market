# CS 573 Term Project

We will use Jupyter Notebooks (.ipynb) and pandas and sklearn for preprocessing and model building.

## Data Preprocessing:
1. Model Name & Clean Title - get rid of these columns in both datasets
2. Used Car Dataset (Split Engine - HP, Liter, Cylinder into three columns) - Replace any missing cylinder counts with the mode of the cylinder counts for that car's brand. Replace any missing horsepower with mean of the horsepower for that brand.
3. For Color - This column has a set of normal colors. If the color is a weird name with a normal color name in it, replace the weird color name with the normal color name. For example, "Glacier White Metallic" becomes "White".
4. Transmission Column - Split this into 2 columns, number of gears and whether it is automatic or manual. Replace any missing values with the mode of the value for the same brand.
5. Bucket the continuous prices into equally sized classes

Nikhil:
- Data Preprocessing 2
- Build 2 linear regression models (1 for each dataset)
- Do LIME, SHAP, and Counterfactuals analysis for the models

Soham:
- Get access to Purdue GitHub
- Build 2 decision tree models (1 for each dataset)
- Do LIME, SHAP, and Counterfactuals analysis for the models

Yubin:
- Get access to Purdue GitHub
- Data Preprocessing 4
- Build 2 random forest models (1 for each dataset)
- Do LIME, SHAP, and Counterfactuals analysis for the models

Anugunj:
- Get access to Purdue GitHub
- Data Preprocessing 1, 3, and 5
- Build 2 decision XG Boost (1 for each dataset)
- Do LIME, SHAP, and Counterfactuals analysis for the models
