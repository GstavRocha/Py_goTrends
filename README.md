 **ENG**:
# Application of Display Trends Google #
_________________________________

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

### 3.2. DOCKER ###
<p>This application can be containerized using Docker to simplify the deployment process. With Docker, you can package the application and its dependencies into a container, ensuring consistency across different environments. To use Docker with this application: </p>

1. Install Docker on your machine following the Docker documentation for your specific operating system.
2. Build the Docker image by running the command docker build -t trends-app . in the project's root directory.
3. Once the image is built, you can run the container with the command docker run -p 3000:3000 trends-app.
4. Access the application in your browser at http://localhost:3000.
5. By using Docker, you can easily deploy the application in various environments and ensure a consistent runtime environment for the application.

Contribution
Contributions are welcome! If you encounter issues, have suggestions, or want to add features, feel free to open an issue or submit a pull

### 3.3. Frontend(Ionic React) ###

1. Navigate to the **frontend** directory.
2. Run the command **npm install** to install the project dependencies.
3. In the **frontend/src/api.ts** file, adjust the API URL to match the backend endpoint (e.g., http://localhost:8000).
4. Run the command npm start to start the Ionic React development server.

## 4. Usage ##
<p>After configuring and running the above steps, the application will be available in the browser.</p>

1. Access the URL provided by the Ionic React development server (usually http://localhost:3000).
2. On the home page, you will see the top Google Trends search terms for the configured region.
3. You can adjust the region and other parameters in the backend logic according to your needs.

## 5. Customization (incomplete description)
<p>This project provides a solid foundation for building a more comprehensive application using Ionic React, FastAPI, and Google Trends. You can customize and enhance the application in several ways:.</p>

* UI/UX: Customize the frontend interface by modifying the components, styles, or layout to align with your design preferences.
* Additional Features: Extend the application's functionality by adding new features, such as visualizing trend data using charts or implementing search filters.
* Data Analysis: Utilize the fetched Google Trends data to perform more in-depth analysis, such as identifying patterns, trends, or correlations.
* Backend Enhancements: Expand the backend by integrating additional APIs or databases to enrich the application's data sources.

## 6. License ##
<p>This project is licensed under the -X- License.</p>
