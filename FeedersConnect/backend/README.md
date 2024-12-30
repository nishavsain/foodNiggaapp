# FeedersConnect Backend README

## Overview
FeedersConnect is a web application designed to connect donors, recipients, and volunteers through a user-friendly platform. This project includes a responsive frontend and a robust backend that handles user authentication, data storage, and geolocation tracking.

## Features
- User signup and login functionality
- Google OAuth2 integration for social media login
- Real-time form validation with clear error messages
- User location tracking during login
- Data storage in CSV files for user information and login records

## File Structure
```
FeedersConnect
├── frontend
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── scripts.js
│   ├── index.html
│   ├── login.html
│   └── signup.html
├── backend
│   ├── app.py (or app.js if using Node.js)
│   ├── users.csv
│   ├── login_records.csv
│   ├── requirements.txt (if using Python)
│   ├── package.json (if using Node.js)
│   └── README.md
└── README.md
```

## Setup Instructions

### Prerequisites
- Python 3.x or Node.js (depending on your choice of backend)
- A code editor (e.g., VS Code)
- Basic knowledge of Flask (for Python) or Express (for Node.js)

### Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   cd FeedersConnect/backend
   ```

2. If using Python, create a virtual environment and install dependencies:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

   If using Node.js, install dependencies:
   ```
   npm install
   ```

### Running the Application
- For Python:
  ```
  python app.py
  ```

- For Node.js:
  ```
  node app.js
  ```

### API Endpoints
- **POST /signup**: Handles user signup and saves data to `users.csv`.
- **POST /login**: Handles user login, validates credentials, captures location, and saves to `login_records.csv`.
- **GET /auth/google**: Handles Google OAuth2 login/signup.

## Usage
- Access the application through your web browser at `http://localhost:5000` (or the port specified in your backend).
- Follow the prompts to sign up or log in.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.