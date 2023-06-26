 **ENG**:
# Application of Display Trends Google #
=======================================

<p> This is a simple application that displays the principal search terms 
for a specific region. It is developed using Ionic React for the frontend and FastAPI 
for the backend, with MySQL as the database. The application is containerized using Docker 
for service deployment. </p>

### Content ###
1. Overview
2. Prerequisites
3. Configuration
4. Usage
5. Customization
6. Contribution
7. License

## 2. Prerequisites ##
<p>Before running the application, make sure you have the following prerequisites installed on your machine:</p>

* Node.js (version 14 or higher)
* NPM (usually installed automatically with Node.js)
* Python (version 3.7 or higher)

## 3. Configuration ## 
<p>Follow the steps below to set up and run the project:</p>

### 3.1. Backend(FastAPI) ###
1. Navigate to the **backend** directory.
2. Create and activate a Python virtual environment (optional, but recommended).
3. Run the command **pip install -r requirements.txt** to install the project dependencies.
4. In the **backend/main.py** file, add your Google Trends API credentials in the relevant section.
5. Run the command **uvicorn main:app --reload** to start the backend server.
<br>
### 3.2. Frontend(Ionic React) ###

1. Navigate to the **frontend** directory.
2. Run the command **npm install** to install the project dependencies.
3. In the **frontend/src/api.ts** file, adjust the API URL to match the backend endpoint (e.g., http://localhost:8000).
4. Run the command npm start to start the Ionic React development server.
<br>
## 4. Usage ##
<p>After configuring and running the above steps, the application will be available in the browser.</p>

1. Access the URL provided by the Ionic React development server (usually http://localhost:3000).
2. On the home page, you will see the top Google Trends search terms for the configured region.
3. You can adjust the region and other parameters in the backend logic according to your needs.

## 5. Customization ##
<p>This project serves as a foundation for building a more complete application using Ionic React, FastAPI, and Google Trends. You can customize it by adding additional features such as charts or filters or expanding its functionality to include more Google Trends data or features.</p>

## 6. License ##
<p>This project is licensed under the -X- License.</p>
