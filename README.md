# waferfautydetection

Problem statement  : - To build a classification methodology to predicts the quality of wafer sensor based on the given training data.This is a binary classification problem ,the wafer which is working indicates as +1 and for not working it indicates as -1.The prediction on the basis of sensor reading for each wafer and finally got the output.

flow chart :

![wafer architecture](https://user-images.githubusercontent.com/104580397/194740835-b46bcd40-a0ab-4856-921f-5206d147ec4d.png)

The architecture model showned above.

In this project we detect the fault wafer,if a wafer is faulty then we get it by through alarm system and stop the production after rectify it we shall continue to the production .

For Prediction the UI looks :

![prediction](https://user-images.githubusercontent.com/104580397/194746351-5d57f75f-f928-4e40-acec-534499fa118b.png)



 
 Technologies used in this project,

Python
Numpy and OpenCV for data cleaning
Matplotlib & Seaborn for data visualization
Sklearn for model building
Jupyter notebook, visual studio code and pycharm as IDE
Algorithms used is Random Forest and XGBoost,we got better performance in Random Forest than XGBoost on the basis of roc_auc score ,along with accuracy.
Python flask for http server
HTML/CSS/Javascript for UI
