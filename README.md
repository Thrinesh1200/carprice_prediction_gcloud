# carprice_prediction_gcloud

## Steps involved for the prediction of car selling price
* Data understanding and exploration 
* Data cleaning
* Data preparation: Feature Engineering and Scaling
* Feature Selection
* Used Random Forest Regressor for prediction and RamdomizedSearchCV for hyperparametric tuning

## Deployment on Google cloud platform
* Install and initialize the Cloud SDK. 
* create a project by running 'gcloud projects create PROJECT_NAME' command.
* create a app by running 'gcloud app create' command
* Make sure that billing is enabled for your project.
## Structuring web service files
* building-an-app/
1-app.yaml
2-main.py
* requirements.txt
* static/
1-script.js
2-style.css
* templates/
1-index.html. (space)
** create the Github repository and clone it to the google cloud **
