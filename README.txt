Project: Chatbot with FastAPI Backend
Project Overview
This project, developed by Akash Singh, involves creating a robust chatbot using Dialogflow. The chatbot is seamlessly connected to a backend server, responsible for storing information about food items, orders, and their status.

Directory Structure
backend: Contains the Python FastAPI backend code.
db: Holds the database dump. Import this into your MySQL database using MySQL Workbench.
dialogflow_assets: Includes training phrases and other assets for Dialogflow intents.
frontend: Contains the code for the project's website.
Module Installation
To set up the project, install the required modules using the following commands:

pip install mysql-connector
pip install "fastapi[all]"
Alternatively, you can run the following command in the backend directory:

pip install -r backend/requirements.txt

Starting FastAPI Backend Server
Navigate to the backend directory in your command prompt.
Run the following command to start the FastAPI backend server:

uvicorn main:app --reload
Using ngrok for HTTPS Tunneling
Install ngrok from https://ngrok.com/download based on your operating system.
Extract the downloaded zip file and place ngrok.exe in a dedicated folder.
Open the Windows command prompt, navigate to the ngrok folder, and run the following command to create an HTTPS tunnel:


ngrok http 8000
Note: Ngrok sessions may expire, so restart the session if you encounter a timeout or see a session expired message.

Important Notes
The backend folder contains the FastAPI backend code.
The db folder holds the database dump, which should be imported into your MySQL database using MySQL Workbench.
dialogflow_assets include essential training phrases and other assets required for Dialogflow intents.
The frontend directory contains the website code.
Feel free to reach out to Akash Singh for any further assistance or clarifications regarding the project.