# Overview

Link to project for - CI: Set Up Azure Cloud Shell
https://github.com/Ryuujiw/udacity-ci-cd-project

CD project: 
An API to predict housing price

Sample payload:
```
POST

{
   "CHAS":{
      "0":0
   },
   "RM":{
      "0":6.575
   },
   "TAX":{
      "0":296.0
   },
   "PTRATIO":{
      "0":15.3
   },
   "B":{
      "0":396.9
   },
   "LSTAT":{
      "0":4.98
   }
}
```

## Project Plan
Link to trello: https://trello.com/invite/b/OnwSbPTf/ATTI935f9a454b2833fe180d5eeadb146403FBE2DB89/udacity
Link to spreadsheet: https://docs.google.com/spreadsheets/d/1_rhcfjAOl7dXIherlrdMl8I6kfwdVTwJ1VVk62JUHbc/edit?usp=sharing

## Instructions

![image](https://user-images.githubusercontent.com/32730247/220159120-86ea9242-9186-4d0b-906a-2c6aaad57e6f.png)

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* The project is running on azure app service
* ![image](https://user-images.githubusercontent.com/32730247/220159471-1e85231b-fbe5-4337-b327-b939df9e1b5a.png)

To debug locally, launch the app.py
```python3 app.py```
and execute the make_prediction.sh on a separate terminal. Ensure that the port number is correct.
```./make_prediction.sh```

* Successful deploy of the project in Azure Pipelines.
![image](https://user-images.githubusercontent.com/32730247/220160077-662a9c76-0cb2-43ec-bc1e-272756bc5da1.png)

* Running Azure App Service from Azure Pipelines automatic deployment
![image](https://user-images.githubusercontent.com/32730247/220160157-b8bad8b4-e89b-485f-a478-12845c188edf.png)

* Successful prediction from deployed flask app
![image](https://user-images.githubusercontent.com/32730247/220160216-12983024-3c34-49db-b469-8339d6e8d8a0.png)

## Enhancements

We could consider to containerize our Flask web app in the event of having more microservices in the future

## Demo 
First take:
https://youtu.be/sv6VVPJ2PuU

Second take with azure cloud shell demo:
https://youtu.be/WjsH5PaGpMw
