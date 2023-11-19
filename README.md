# News-Searching Application

## Description
This Android-based application provides users with the ability to search for the most recent news by inputting a keyword and a date of interest. It communicates with a back-end web service, which interfaces with the News API to fetch and serve the relevant news articles.

## Features
- **Android Client Application**: Interact with the web service to receive news information using different Views (TextView, EditText, ImageView).
- **User Input Handling**: Accepts keyword and date input from users, with input validation.
- **HTTP Requests**: Makes HTTP requests to the web service and parses JSON formatted responses.
- **Web Service**: Implements a servlet that handles requests, interacts with the News API, and logs interactions to MongoDB.
- **Data Parsing**: Parses API responses and extracts news article information to display on the Android client.
- **Error Handling**: Includes robust error handling for various potential faults.
- **Logging**: Logs interaction data for analytics and troubleshooting.
- **Dashboard**: Provides a web-based dashboard displaying operational analytics and logs.
- **Deployment**: Deployed on GitHub Codespaces with detailed instructions for local and remote testing.

## Installation
To set up the project for development:
1. Clone the repository.
2. Import the project into Android Studio.
3. Configure the MongoDB connection strings in `MongoDBService.java`.
4. For local testing, ensure the local server is running and accessible.

## Usage
For searching news:
<local or remote server address>/api/news/<searchKeyword>/<searchDate>

To access the dashboard:
<local or remote server address>/dashboard


## Local Testing URLs
- Android Application: `http://10.0.2.2:8080/api/news/Tesla/2023-11-14`
- Dashboard: `http://localhost:8080/Project4ServletServer-1.0-SNAPSHOT/dashboard`

## Remote Testing URLs
- Android Application: `https://<codespaces-url>/api/news/labradoodle/2023-11-14`
- Dashboard: `https://<codespaces-url>/dashboard`

## Authors
- Sennan Cen - *Initial work* - [sennanc2@gmail.com]

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- News API for providing news data.
- MongoDB for database services.
- All contributors who helped with the project.

