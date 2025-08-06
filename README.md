# regression-error-analysis


Project Name:  Linear Regression Error Analysis  
Brief objective: "Analyzed the errors of the regression model, tested several improvement approaches (1,3 features, polynomial and tree-based models)".  
Main steps: "First, a base model was built, then residual analysis was performed, then model improvements with metrics testing".  

Key results:    
 * What helped:    
     - Including polynomial feature interactions captured the relationship between predictors and calories effectively, leading to slightly better accuracy than Gradient Boosting.   
     - Features provided strong predictive power without requiring additional engineered variables.    
     - Residual analysis confirmed no major systematic bias and a moderate spread of errors.     
 * What didn’t help:  
    - Gradient Boosting did not outperform the simpler Polynomial Regression model on this dataset, despite its higher model complexity.   
    - Additional model complexity did not significantly reduce errors or change residual patterns.  
    - No clear improvement from advanced non-linear modeling compared to polynomial transformation of features.    
    
Jupyter Notebook is provided.    
Visual report in PDF (10 pages with graphs and comments). 
[View the report on Google Drive] (https://drive.google.com/file/d/1PSQwPMKl0qaa8Mdnq1gXBhRqPw3CJsxF/view?usp=share_link)

