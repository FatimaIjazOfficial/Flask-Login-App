### Flask Login Application Overview

**Purpose:**  
This Flask application demonstrates a simple login system using Flask-WTF for form handling and Bootstrap for styling.

**Components:**
1. **Flask-WTF**: Used for creating and validating forms.
2. **Bootstrap**: Used for styling the application.

**Functionality:**
1. **Home Page:** A simple landing page.
2. **Login Page:** A form where users can enter their email and password.
3. **Success Page:** Shown if login credentials are correct.
4. **Denied Page:** Shown if login credentials are incorrect.

**Routes:**
- `/`: Home page.
- `/login`: Login page. Handles both GET (display form) and POST (validate form and process login) requests.

**Forms:**
- `LoginForm`: A form with fields for email, password, and a submit button.

**Templates:**
- `index.html`: Template for the home page.
- `login.html`: Template for the login page with the form.
- `success.html`: Template shown when login is successful.
- `denied.html`: Template shown when login is denied.

### Key Dependencies
- `Flask`: The web framework used to build the application.
- `Flask-WTF`: Flask extension integrating WTForms for form handling.
- `Bootstrap-Flask`: Flask extension for integrating Bootstrap styles.
- `WTForms`: A flexible form validation and rendering library for Python web development.

### How to Run the Application
1. **Install Required Packages**: Ensure you have the required packages installed. You can do this using the following command:
    ```bash
    pip install -r requirements.txt
    ```
2. **Set Secret Key**: The `app.secret_key` is used for securing session data. Ensure you set it to a unique, secret value.

3. **Run the Application**: Execute the Flask app using the command:
    ```bash
    flask run
    ```

**Note:** Replace placeholders like `"your-secret-key"` and email/password in the `login` route with actual values as per your requirements.
