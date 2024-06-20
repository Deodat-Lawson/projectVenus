# Project Venus

**Important Note:** This project is currently experiencing problems in Library uploading

## Overview

Project Venus is a project that helps users find the nearest pharmacy that suites their needs. This full stack web application features Django powering the backend and React.js for the frontend.

## Frontend

Frontend is developed using Material UI, an intuitive React library for building UI components. Throughout the project, I utilized numerous Material UI components, which I styled effortlessly.

## Backend and API

The API was constructed with Django Rest Framework (DRF). I made requests to the API using React, ensuring smooth and efficient data handling between the frontend and backend.

## Interactive Maps

To add a geographic dimension to the project, I incorporated Leaflet, a JavaScript library for building interactive maps. Property listings are displayed on the map using React-Leaflet, which binds React and Leaflet seamlessly.

## Spatial Database

The PostgreSQL database was enhanced with the PostGIS extension, making it spatially aware. This allowed me to perform spatial queries (geometric information such as distance) in addition to regular queries.

## User Authentication

User authentication was implemented using the Djoser library. This setup enables end users to add, delete, or update property listings directly from the frontend.

## Error Handling

Both client-side and server-side errors are managed effectively within the forms, ensuring a smooth user experience.

## Technologies Used

- **Backend:** Django, Django Rest Framework (DRF)
- **Frontend:** React.js, Material UI
- **Maps:** Leaflet, React-Leaflet
- **Database:** PostgreSQL with PostGIS extension
- **Authentication:** Djoser

## Features

- Fast and responsive frontend using Material UI components
- Robust API with Django Rest Framework
- Interactive maps with phamacies using Leaflet and React-Leaflet
- Spatially aware database with PostGIS, enabling advanced spatial queries
- User authentication allowing end users to manage property listings
- Comprehensive error handling on both client-side and server-side

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/real-estate-website.git
    cd real-estate-website
    ```

2. **Backend Setup:**
    - Create and activate a virtual environment
    - Install backend dependencies:
      ```bash
      pip install -r requirements.txt
      ```
    - Run database migrations:
      ```bash
      python manage.py migrate
      ```
    - Start the Django development server:
      ```bash
      python manage.py runserver
      ```

3. **Frontend Setup:**
    - Navigate to the frontend directory:
      ```bash
      cd frontend
      ```
    - Install frontend dependencies:
      ```bash
      npm install
      ```
    - Start the React development server:
      ```bash
      npm start
      ```

4. **Access the Application:**
    - Open your browser and navigate to `http://localhost:3000` to view the frontend.
    - The backend can be accessed at `http://localhost:8000`.

