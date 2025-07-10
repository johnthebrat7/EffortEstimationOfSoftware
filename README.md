Effective software project management depends a lot on how well we can estimate the effort needed to build or maintain a software application.
This is a crucial part of any project because accurate estimates help with proper planning, assigning the right people, staying on schedule, and keeping within the budget .
This project explores how machine learning can help make effort estimation more accurate . Using the COCOMO81 dataset, we carry out a detailed study to better understand the challenges involved in the software development process. 
Machine learning has already been successfully used in real-life problems like predicting diabetes, and here we apply it for software effort estimation.
For our analysis, we used the COCOMO81 dataset, which is freely available from an open-source platform . Before using the data, we went through several preprocessing steps . 
These included handling missing values, converting text-based (categorical) features into a format suitable for our machine learning, and splitting the data into training and testing sets .
All these steps were important to make sure that the results of our analysis would be accurate and trustworthy.We have used three prominent machine learning regression algorithms – Linear Regression ,Random Forest Regression and Decision Tree Regression . 
Machine learning models are known for their usefulness in software effort estimation . What sets this study apart is the use of correlation-based feature selection, which helps pick the most relevant features to improve prediction accuracy. 
This step is especially important in software development, where many factors can affect project timelines and resources . We used evaluation metrics like R² ,MAE and RMSE to thoroughly measure how well the algorithms perform.
These metrics give us a complete picture of each model’s accuracy and efficiency. The subsequent sections are divided into following parts:

