# Win_Predictor
This is our capstone project, named as Win_Predictor

1.In this code fistly we imported the required libaries

2.then imported data '/content/drive/MyDrive/Win_Predict_Data.xlsx' and droped un essential columns("Card-1","Card-2" and 
"Tie")

3.then converted letter based data into numerical to implement the model.
      ----In this we converted {'D': 0, 'T': 1, 'TIE': 2}----.
then spreated Feactures ('P1 -Amount','P2 -Amount','Sq-1', 'Sq-2', 'Sq-3', 'sq-4', 'Sq-5', 'Sq-6', 'Sq-7', 'Sq-8', 'Sq-9')
and Target values 'Sq-10'.

4.then applied SMOTE funtion to make balance of data.

5.then splited the data into training and testing sets.

6.then Created a Random Forest regressor, Train the classifier on the training data and set test data to predict.

7.then Evaluate the model.

8.At the end implementation section.


