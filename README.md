
ML to App (Gradio)

Customer Churn Prediction App with Gradio

Introduction

A churn prediction app built with Gradio and wrapped around a classification machine learning model. This project is more like a quest to discover how to embeded it into a web app with a user-friendly interface, in this case, Gradio. 

Process Description

The process begins with exporting the necessary items from the notebook, building an interface that works correctly, importing the necessary items for modelling, and then writing the code to process inputs. The process can be summarized as:

Export machine learning items from notebook,
Import machine learning items into the app script,
Build an interface,
Write a function to process inputs,
Pass values through the interface,
Recover these values in backend,
Apply the necessary processing,
Submit the processed values to the ML model to make the predictions,
Process the predictions obtained and display them on the interface.

SetUp

Since I used Colab, I just had to 
!pip install gradio
In my console and follow the process as indicated above 

NB: On your local machine,
To setup and run this project you need to have Python3 installed on your system. Then you can clone this repo. At the repo's root, use the code from below which applies:

Windows:

  python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  
Linux & MacOs:

  python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

You can then run the app (still at the repository root):

App built with Gradio Blocks

  python Churn_Prediction_App_with_grBlocks.py
App built with the simple Gradio Interface

  python Churn_Prediction_App_with_grInterface.py
With inbrowser = True defined, it should open a browser tab automatically. If it doesn't, type this address in your browser: https://localhost:7860/

ScreenShots

![image](https://user-images.githubusercontent.com/106823333/211617384-aff735d1-561f-4672-b6dc-e9cae4c56a10.png)

