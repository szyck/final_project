<h1>Module 20: Mobile-Price-Classification-kaggle</h1>

This project has been implemented using python libraries like Numpy,Pandas to import and design the data. Matplotlib and Seaborn were used for visualization of the data.

A dataset consisting of various parameters to predict the price score/range of a mobile phone based on certain inputs such as following:

*id:ID
*battery_power:Total energy a battery can store in one time measured in mAh
*blue:Has bluetooth or not
*clock_speed:speed at which microprocessor executes instructions
*dual_sim:Has dual sim support or not
*fc:Front Camera mega pixels
*four_g:Has 4G or not
*int_memory:Internal Memory in Gigabytes
*m_dep:Mobile Depth in cm
*mobile_wt:Weight of mobile phone
*n_cores:Number of cores of processor
*pc:Primary Camera mega pixels
*px_height:Pixel Resolution Height
*px_width:Pixel Resolution Width
*ram:Random Access Memory in Megabytes
*sc_h:Screen Height of mobile in cm
*sc_w:Screen Width of mobile in cm
*talk_time:longest time that a single battery charge will last when you are
*three_g:Has 3G or not
*touch_screen:Has touch screen or not
*wifi:Has wifi or not

<h2>analysis</h2>

We studied the entire dataset we had for the topic on Kaggle found all the important information on the data we were going to work on
* The Data Preprocessing
* Description of Data
* Info about the data
* The Correlation between the attributes
* The attributes that are most correlated with the Price Range ( Our target )
* Outlier Analysis of Non-categorical Data
* Histogram of all the attributes
The idea of implementing svm classifier in Python is to use the phone specification features to train an SVM classifier and use the trained SVM model to predict the price_range.

<img width="438" alt="image_4" src="https://user-images.githubusercontent.com/104687817/195239752-4eef2aef-046b-4a55-bc7c-ff5e95676798.PNG">


Next we tried a total of 9 Machine Learning Algorithms for each we made a confusion matrix and the most contributing features were found:
* Logistic Regression
* Decision Tree(gini)
* Decision Tree(entropy)
* Random Forest
* Naive Bayes
* SVM

We compared the accuracies of all the models and found that SVM is the best classifier for our project

<img width="404" alt="final_6" src="https://user-images.githubusercontent.com/104687817/195238735-156e9e10-0920-4e75-a45b-5a3c49651d1c.PNG">
<h2>Final Presentation</h2>

A copy our final presentation and related dashboards can be found here:

https://docs.google.com/presentation/d/1orviC2ZUsLyrI1QI4nqv4Cy3B4yMkgYy9hqao11yCwU/edit#slide=id.p

https://public.tableau.com/app/profile/john.m.ratcliff/viz/Final_Project_16642168942350/Dashboard-Data

https://public.tableau.com/app/profile/john.m.ratcliff/viz/Model_Results/Dashboard-ModelResults
