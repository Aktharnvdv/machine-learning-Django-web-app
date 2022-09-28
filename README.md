# *Machine Learning - Django Web App*

    logistic regression model was trained on Titanic dataset and deployed using Django to predict if a person can survive or not.

# *Files*:

    Titanic
    
           views.py: code for generating prediction using model and showing result to the user.
    
           machine learning model :titanic_survival_ml_model.sav:scalar.sav
           
           urls.py : specifiying the url and page connection

    templates: contains HTML code for taking input from user and showing the output to the user.
    
    machine learning.py: code for developing dateset preperation and model training
    
# *Libraries and framework used*:

    pandas           == 1.5.0
    numpy            == 1.23
    sklearn          == 1.0.2
    HTML,CSS,django  == 2.2
    python           == 3.8

# *Webapp and deployment:*

    this application contains 2 pages
    
    1)first page is used to take inputs from the user those are "pclass , Sex , Age , Sibsp , Parch ,
                                                                 Fare , Embark Category C , Embark Category Q ,
                                                                 Embark Category S".
    
    2)second page is used to show the output to the user that is survived or not.
    
    
    

