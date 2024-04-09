# EmailGenie

## Description
This project aims to implement a web application called OneBox that provides a user-friendly interface for accessing and managing threads. It includes features such as login functionality, integration with Google login, fetching data from the server using API calls, keyboard shortcuts for efficient navigation, and a custom text editor with additional functionalities like saving and inserting variables.

## Features
1. **Login Page:** The application provides a login page for users to authenticate themselves.
2. **Google Login Integration:** Users can log in using their Google accounts for convenience and security.
3. **OneBox Screen:** After successful login, users are redirected to the OneBox screen, where they can view and manage threads.
4. **Fetching Data:** The application fetches thread data from the server using API integration.
   - `GET /onebox/list`: Fetches a list of threads.
   - `GET /onebox/:thread_id`: Retrieves details of a specific thread.
   - `DELETE /onebox/:thread_id`: Deletes a thread.
5. **Keyboard Shortcuts:** Keyboard shortcuts enhance user experience by enabling quick actions.
   - Pressing "D" deletes a thread.
   - Pressing "R" opens the reply box for the selected thread.
6. **Custom Text Editor:** The application includes a custom text editor with additional functionalities.
   - Users can save their work using the "SAVE" button.
   - The editor allows users to insert variables for easier content creation.

## Implementation Details
- **Frontend Technologies:** HTML, CSS, JavaScript, React.js
- **Backend Technologies:** Node.js, Express.js
- **API Endpoints:**
  - Authentication:
    - `/login`: Handles user login.
  - OneBox:
    - `GET /google-login`: Initiates Google login process.
    - `GET /onebox/list`: Retrieves list of threads.
    - `GET /onebox/:thread_id`: Retrieves details of a specific thread.
    - `DELETE /onebox/:thread_id`: Deletes a thread.
- **Third-party Services:**
  - Google OAuth for authentication.
- **Additional Libraries/Tools:**
  - React Router for client-side routing.
  - Axios for handling API requests.
  - Custom text editor component for text editing functionality.

## Setup Instructions
1. Clone the repository from [GitHub Repo URL].
2. Install dependencies using `npm install`.
3. Configure environment variables for API keys, database connection strings, etc.
4. Start the frontend and backend servers using `npm start`.
5. Access the application through the provided URL.

## Future Enhancements
- Implement user authentication and authorization for enhanced security.
- Improve UI/UX design for a more visually appealing interface.
- Add functionality for creating new threads.
- Implement real-time updates using WebSockets for instant notifications.
- Enhance text editor with additional formatting options such as bold, italic, etc.

## Contributors
- [Your Name/Email] - Project Lead & Developer
- [Contributor Name/Email] - Frontend Developer
- [Contributor Name/Email] - Backend Developer
- [Contributor Name/Email] - UI/UX Designer

## License
This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.
