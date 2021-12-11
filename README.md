# heart-disease-prediction
Deployed Application:
link - https://10monica.pythonanywhere.com/

Introduction-
This is a fully validated multi-user application, where a user can check if he/she has heart disease or not by filling a short form which collects data from the heart disease prediction model and returns with a response based on the dataset used. 

Keywords- 
ML, Flask, RandomForestClassifier, HTML, CSS, Bootstrap

Dataset-
Heart Disease Prediction dataset from kaggle.com
Link - https://www.kaggle.com/rishidamarla/heart-disease-prediction

Machine Learning - 
Made use of Random Forest Classifier Algorithm, used random state = 3136

Model prediction Accuracy - 
87%

Flask-
Backend of the entire web application has been programmed in Flask, with a app.py controlling the major functionalities and the connections to all pages. 
Used Flask mail for sending randomly generated passwords to users when they try to sign in, and will then be redirected to the login page as soon as we send the email containing the password of the particular user. 
Re-using the same username won't be possible as it has been set as the primary key. 
A forgot password page has been made just in case the user forgets their password to the application.
All the forms are fully validated, including the quiz form inside which is the main functionality of the application. Responses to the form are used alongside the data present in the dataset to make the prediction.

HTML, CSS, BOOTSTRAP -
The entire frontend of the application have been made using html, css and bootstrap. And the application is fully responsive and is fully functional on all device widths.

Database-Sqlite3
name - monicaheart.db
table name - user

Screenshots-
Signup page-
![image](https://user-images.githubusercontent.com/82702672/145677319-294c2f3f-3384-42d0-848a-2ecdae03e70b.png)

Login page-
![image](https://user-images.githubusercontent.com/82702672/145677364-c4020995-e143-463b-9c46-652ab26eb8b2.png)

Forgot Password-
![image](https://user-images.githubusercontent.com/82702672/145677379-0a27c60a-0abc-4ca1-9254-c8910b96d66b.png)

Home Page-
![image](https://user-images.githubusercontent.com/82702672/145677406-a3940c4a-a6e2-451c-b790-a9df910e899f.png)
![image](https://user-images.githubusercontent.com/82702672/145677419-c6f720a2-bf2f-4f8c-9a46-0babb0cc28a1.png)
![image](https://user-images.githubusercontent.com/82702672/145677424-c5497e31-1f57-406c-b838-287f54a12112.png)
![image](https://user-images.githubusercontent.com/82702672/145677431-91c5cf18-25ce-49a6-be78-e47f2b23355f.png)

Quiz Page-
![image](https://user-images.githubusercontent.com/82702672/145677438-292c9ddd-a508-4fe7-9f3e-234b9beb7446.png)

Contributors-
Solo Project - Monica Gullapalli

Deployed Web Application link -
https://10monica.pythonanywhere.com/signup







