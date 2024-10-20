# NIT3213 Android Project
Login Credentials:
username= pravesh
password= s4677960

This project is an Android application for NIT3213 Assignment that integrates with an API for authentication and displays a list of entities with details.

## Features

- **Login Functionality**: Users can log in using a username and password, which fetches a `keypass` from the API.
- **Dashboard**: After a successful login, the app displays a list of entities retrieved from the API.
- **Details Page**: Clicking on an entity in the dashboard shows its details.
- **Profile Icon**: The dashboard includes a profile image next to each entity.
- **Unit Testing**: Simple tests are included for login validation and API interactions.

## API Endpoints

The app interacts with the following API endpoints:

1. **Login Endpoint** (`/footscray/auth`): Accepts a username and password, returning a `keypass`.
2. **Dashboard Endpoint** (`/dashboard/{keypass}`): Fetches a list of entities using the `keypass`.

## Getting Started

### Prerequisites

- **Android Studio**: Make sure you have Android Studio installed.
- **API Access**: Ensure that the API endpoint `https://nit3213-api-h2b3-latest.onrender.com` is accessible.

### Installation

1. Clone the repository: https://github.com/pravesh307/praveshproject.git
2. Open the project in Android Studio.
3. Sync Gradle by clicking "Sync Now" when prompted.
4. Run the app on an emulator or a physical device.

   Running the App
#Login:
Enter your username and password in the login screen.
Upon successful login, you will be redirected to the Dashboard.
#Dashboard:
The dashboard displays a list of entities retrieved from the API. Each item includes a profile image and information about the entity.
#Entity Details:
Clicking on an entity takes you to the details page, showing more information about the entity (name, culture, domain, etc.).

#Unit Testing
This project includes basic unit tests for login and API functionality. To run the tests:

- Go to app/src/test/java/com/example/nit3213project/.
- Right-click on the test files (e.g., LoginActivityTest.kt or DashboardActivityTest.kt).
- Select Run 'LoginActivityTest' or Run 'All Tests' to execute the tests.
   
