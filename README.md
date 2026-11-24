# React Login & Registration Form

A React + Vite project demonstrating **React state (`useState`)** and **controlled forms**.

## Features
- Registration form with name, email, 10-digit phone number, and password.
- All input values are controlled by React state.
- On registration submit, entered details are displayed on the page.
- Login form checks the email and password against the registered details.
- Displays `Login Successful!` for matching details, otherwise an error message.
- Responsive layout.

## Run the project

1. Install [Node.js](https://nodejs.org/) if it is not already installed.
2. Extract the ZIP file.
3. Open the extracted project folder in VS Code.
4. Open the terminal in that folder and run:

```bash
npm install
npm run dev
```

5. Open the local URL shown by Vite (usually `http://localhost:5173`).

## How to test
1. Fill in the registration form and click **Register**.
2. The registration details will appear below the form.
3. Enter the same email and password in the login form.
4. Click **Login** to see `Login Successful!`.
5. Try a different password to see the error message.

## Main concept: Controlled Components
Each input uses a `value` property connected to React state and an `onChange` handler to update that state. The form submission uses `event.preventDefault()` to prevent a page reload.

**Note:** This is a frontend learning demo. Registration data is held only in React state and is lost when the page is refreshed. It does not use a backend or database, and it is not suitable for real authentication.
