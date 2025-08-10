# Form-Creation-Validation

A simple web project demonstrating **HTML form creation with validation** and **API data fetching** using JavaScript.

## Features

### 1. User Registration Form with Validation
- Collects user details such as **name**, **email**, **password**, and **age**.
- Implements **client-side validation** to ensure:
  - Required fields are filled.
  - Email format is valid.
  - Password meets minimum length and complexity.
  - Age is a valid number within the allowed range.
- Displays **error messages** next to invalid fields.
- Uses **CSS styling** for better UI/UX.

### 2. Fetching and Displaying API Data
- Fetches user data from:  
  `https://jsonplaceholder.typicode.com/users`
- Displays fetched user names in a **styled unordered list**.
- Handles **loading state** (`"Loading user data..."` message).
- Shows **error message** if API request fails.
- Uses `fetch-data.js` with `async/await` for cleaner code.

## File Structure

```plaintext
form-creation-validation/
│
├── index.html          # Main HTML file containing the form and API data container
├── style.css           # Styles for the form and fetched data
├── script.js           # Form validation logic
├── fetch-data.js       # Fetch API logic for displaying user names
└── README.md           # Project documentation

---

## 🛠 Technologies Used

- **HTML5** – Markup structure
- **CSS3** – Styling and layout
- **JavaScript (ES6)** – Validation logic

---

## 📋 Validation Rules

| Field    | Rule                                     | Error Message                                         |
|----------|------------------------------------------|-------------------------------------------------------|
| Username | Minimum 3 characters                     | "Username must be at least 3 characters long."       |
| Email    | Must contain `@` and `.`                 | "Email must contain '@' and '.' characters."         |
| Password | Minimum 8 characters                     | "Password must be at least 8 characters long."       |

---

## ▶️ How to Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/Form-Creation-Validation.git
