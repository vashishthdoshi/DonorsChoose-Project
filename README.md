**Machine Learning Project: Predictive Modeling with 2011 and 2013 Data**

**Project Overview**
This repository contains a machine learning project that analyzes educational data from 2003 to 2011 and 2013. The project involves merging multiple datasets, performing exploratory analysis,  building predictive models and using techniques for handling imbalanced data.
 ![image](https://github.com/user-attachments/assets/6a14158a-b006-4b90-9738-0d4ffbe47274)

**Key Files**

1.**Source Data:**
o	donations.csv: contains information about donations to each project.
o	essay.csv: contains teacher-written project descriptions about each project.
o	resources.csv: contains information about requested materials and costs.
o	projects.csv: contains information about each project.
o	outcomes.csv: contains information about the outcomes of projects.

2.	**Notebooks:**
o	merge_data.ipynb: Combines the five source files
o	EDA_data.ipynb: Exploratory data analysis
o	final_model_2011.ipynb: 2011 predictive model
o	final_model_2013.ipynb: 2013 predictive model

4.	**Processed Data:**
finalml_file.csv: Cleaned merged dataset for modeling

**Dependencies**

•	Data Processing: pandas, numpy
•	Machine Learning: scikit-learn, xgboost, imbalanced-learn
•	Visualization: matplotlib, seaborn
•	Environment: jupyter

**Modeling Approach**

•	Uses SGDClassifier, RandomForestClassifier and XGBoost for predictive performance
•	Implements imbalanced-learn techniques using(SMOTE)  for class imbalance
•	Includes thorough feature engineering
•	Contains model evaluation metrics

**MIT License**

Copyright (c) [2025] Anna Sene, Vashishth Doshi, David Forson
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.





