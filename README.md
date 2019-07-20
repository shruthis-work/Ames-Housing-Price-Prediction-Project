# General-Assembly-PROJECT-2 : Ames House Prediction Project
Welcome to my repository.
In this project I aimed to predict the house prices in Ames,Iowa. 
The file AMES PROJECT is the main file where I have explained my EDA and modelling so please refer to that file for the entire 
explanation of code
The AMES PROJECT- MODEL 2 is the second model I built for a kaggle competition and follows the same pre-processing, thus does not
have any explanation of code. I would like to highlight that I built a different model and this got one of my personal best scores.
The BEST MODEL file has the model for the highest kaggle score. Please feel free to take a look even though the pre-processing is 
same as explained in the AMES PROJECT notebook.
The csv files are the training test, testing test and the resulting output of the model which are named accordingly. 28447.csv and 
29407.csv are my submissions to obtain the respective scores.
The file named "original model" is the outcome stored by running the AMES PROJECT notebook, Sadly to say this obtained a terrible 
kaggle score and thus was the worst outcome from the same original code

I have used Linear Regression, Lasso CV and Ridge CV with Lasso CV working the best.
The pre-processing includes removing outliers, filling out null values with calculated values, feature engineering (Interaction 
columns, House Age etc), standardization. My feature selection was based on correlation between the features. Since corelation 
can only be obtained for numerical features I used the cramers-V test to obtain the corelation for categorical features as well. 
All features with a co-relation of above 0.5 were chosen to be in the design matrix. This can be considered as one of the
limitations of the model.
My model's accuracy was 86.7%

I will be adding a report with all visualizations produced.
Thankyou,
Regards,
Shruthi

