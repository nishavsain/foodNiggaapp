# FeedersConnect

FeedersConnect is a web application designed to connect donors, recipients, and volunteers in an eco-friendly manner. This project includes a responsive login and signup system, allowing users to register and log in while capturing their location.

## Features

- **User Authentication**: Signup and login functionality with email and password.
- **Google OAuth2 Integration**: Users can sign up or log in using their Google accounts.
- **Responsive Design**: Mobile-first approach ensuring usability across devices.
- **User Data Storage**: User information is securely stored in CSV files.
- **Location Tracking**: Captures user location during login using the Geolocation API.
- **Real-time Validation**: Immediate feedback on form inputs for a better user experience.
- **Eco-friendly Theme**: Modern green and white color scheme with appealing SVG art.

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

### Frontend

1. Navigate to the `frontend` directory.
2. Open `index.html` in a web browser to access the application.

### Backend

1. Navigate to the `backend` directory.
2. Install the required dependencies:
   - For Python: Run `pip install -r requirements.txt`
   - For Node.js: Run `npm install`
3. Start the server:
   - For Python: Run `python app.py`
   - For Node.js: Run `node app.js`

## Usage

- **Signup**: Fill in the required fields on the signup page and submit the form. Ensure all validations are met.
- **Login**: Enter your credentials on the login page. If you have signed up using Google, you can log in with your Google account.
- **Location Tracking**: Upon logging in, your location will be captured and stored.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.