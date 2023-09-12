# Login Portal

This project represents a secure and user-friendly login page for a web application. It ensures a clean and intuitive user interface while incorporating modern design practices. The page allows users to enter their email, password, and choose their role (either as a customer or an admin) to log in. It uses JavaScript to handle user interactions and make API requests for user authentication. The code prioritizes security by sending data as JSON and includes error handling for potential issues during the login process. Additionally, it utilizes local storage to store authentication tokens for future user sessions.

## Table of Contents

- [Demo](#demo)
- [Screenshots](#screenshots)
- [Features](#features)
- [How it Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Demo

You can check out the live demo of the Login Portal [here](https://22pankajsahu.github.io/JS_PRO_USER-AUTHENTICATION/).

## Screenshots

Included relevant screenshots of the application here.

![Screenshot 1](https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION/assets/135128502/68638665-b41d-431f-a23f-c75504776bc8)

![Screenshot 2](https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION/assets/135128502/9cf45847-daea-409c-8cc3-01fcb4901b99)

![Screenshot 3](https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION/assets/135128502/b7d5d469-d54d-4bca-a7f3-e2177307be95)

![Screenshot 4](https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION/assets/135128502/3ea94f95-c041-4b4b-84eb-7b8a83840e81)

![Screenshot 5](https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION/assets/135128502/c34e4665-3a72-4b1f-9ca4-d033dfe9b397)

## Features

- User-friendly and responsive design.
- User authentication with role selection (customer or admin).
- Secure login process with error handling.
- Local storage for storing authentication tokens.
- Modern and clean user interface.

## How it Works

The login portal is a user-friendly web application designed to provide secure access to authorized users with role-based access control (customer or admin). Here's an overview of how it works:

1. **User Interface (UI):**
   - The login portal offers an intuitive and responsive user interface. Users can easily access it from any device with an internet connection.

2. **User Input:**
   - Users are required to provide their credentials to log in. These credentials include:
     - Email address
     - Password
     - Role selection (customer or admin)

3. **Authentication:**
   - Upon entering their credentials and clicking the "Login" button, the JavaScript code in the background collects this information.

4. **API Request:**
   - The collected data is then used to create a JSON object.

5. **Sending Data:**
   - An API request is made to the server using the Fetch API. The API request is sent to the server endpoint responsible for user authentication.

6. **Server Authentication:**
   - The server processes the API request, validating the user's email, password, and role. It checks if the provided credentials match any registered user's data.

7. **Error Handling:**
   - The server provides a response, which is handled by the JavaScript code in the frontend.
   - If the authentication is successful, a token is typically returned from the server, indicating a successful login.
   - If there are errors (e.g., incorrect credentials, server issues), appropriate error messages are displayed to the user.

8. **Local Storage:**
   - If the user's login is successful and a token is received, the token is stored in the browser's local storage. This allows the user to remain authenticated between page visits or after refreshing the page.

9. **Redirection:**
   - After successful authentication, the user is typically redirected to another page, often the main dashboard or homepage of the web application.

10. **Logging Out:**
    - If the user decides to log out, they can click the "Log-out" link (if logged in), which removes the token from local storage, effectively logging the user out.

11. **Error Handling (Again):**
    - The code also includes error handling for cases where API requests fail or other unexpected issues arise during the login or logout process.

12. **Security Measures:**
    - The application ensures data security by sending user credentials as JSON data, which is a more secure method compared to sending data in plain text.
    - Additionally, it utilizes local storage for storing authentication tokens, enhancing the security of user sessions.

## Installation

To run the Mini Calendar web application locally, follow these steps:

1. Clone this repository to your local machine: `git clone https://github.com/22pankajsahu/JS_PRO_USER-AUTHENTICATION.git`
2. Open the project folder in your code editor.

## Usage

1. Open the Mini Calendar application in a web browser.
2. You will see the current month, day, date, and year displayed in a visually pleasing format.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository to your own GitHub account.

2. Create a new branch for your feature:

   ```bash
   git checkout -b feature/new-feature
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push your changes to your forked repository:

   ```bash
   git push origin feature/new-feature
   ```

5. Open a pull request to the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Name: [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu)
- Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)
- GitHub: [22pankajsahu](https://github.com/22pankajsahu)
