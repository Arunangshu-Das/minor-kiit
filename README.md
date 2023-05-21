# Medicine E-commerce API [Backend]

This is an API for a medicine e-commerce platform. It provides endpoints for user registration, login, medicine search, adding items to the cart, and more. The API is built using Node.js, Express.js, and MongoDB.

## Installation

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-directory>`
3. Install the dependencies: `npm install`

## Configuration

Before running the application, make sure to configure the database connection in the `config/database.js` file.

## Usage

To start the server, run the following command:

```
npm start
```

The server will start running at `http://localhost:<PORT>`, where `<PORT>` is the port number specified in the environment configuration.

## API Endpoints

The following are the available API endpoints:

- `GET /` - Retrieves a welcome message.
- `POST /register` - Registers a new user.
- `POST /login` - Authenticates a user and generates a JSON Web Token (JWT).
- `GET /all` - Retrieves all available medicines.
- `POST /search` - Searches for medicines by name.
- `PUT /addtocart` - Adds an item to the user's cart.
- `GET /showcart` - Retrieves the user's cart.
- `GET /getmedicine` - Retrieves medicines related to a specific disease.
- `POST /generatemedicine` - Generates new medicines for a disease.

Please refer to the API documentation for detailed information on each endpoint.

## Dependencies

The following are the main dependencies used in this project:

- `express` - Fast, unopinionated, minimalist web framework for Node.js.
- `jsonwebtoken` - JSON Web Token implementation for Node.js.
- `bcryptjs` - Library for hashing and salting user passwords.
- `mongoose` - MongoDB object modeling tool.
- `cors` - Middleware for enabling Cross-Origin Resource Sharing (CORS) in Express.js.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

---

# Disease Prediction API [ML]

This is an API for disease prediction based on symptoms. It uses a machine learning model trained on symptom data to predict the most likely disease given a set of symptoms. The API is built using Flask and relies on a trained model stored in a pickle file.

## Installation

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-directory>`
3. Install the dependencies: `pip install -r requirements.txt`

## Usage

To start the server, run the following command:

```
python app.py
```

The server will start running at `http://localhost:5000`.

## API Endpoints

The following are the available API endpoints:

- `GET /` - Retrieves a welcome message.
- `POST /search` - Predicts the disease based on provided symptoms.

Please refer to the API documentation for detailed information on each endpoint.

## Dependencies

The following are the main dependencies used in this project:

- `Flask` - A lightweight web framework for Python.
- `pandas` - A data manipulation and analysis library.
- `numpy` - A numerical computing library.
- `scikit-learn` - A machine learning library.
- `flask_cors` - A Flask extension for handling Cross-Origin Resource Sharing (CORS) requests.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

---
# Frontend and Integration

This is a React application that provides various features related to human and veterinary health. It includes features like user authentication, searching for products, adding items to the cart, and more. The application uses React Router for handling different routes and components.

## Usage

To run the application, follow these steps:

1. Install the required dependencies: `npm install`
2. Start the development server: `npm start`
3. The application will be running at `http://localhost:3000`

## Components

The application is composed of the following main components:

- `Navbar`: Renders the navigation bar with links to different sections of the application.
- `Login`: Displays the login form for user authentication.
- `Signup`: Displays the signup form for user registration.
- `Footer`: Renders the footer section of the application.
- `Home`: Represents the home page component.
- `Human`: Represents the component for human health-related information.
- `Veterinary`: Represents the component for veterinary health-related information.
- `Search`: Allows users to search for specific products.
- `Searchresult`: Displays the search results based on user input.
- `Proddescription`: Provides detailed information about a specific product.
- `Showcart`: Displays the items added to the cart.
- `Mlresult`: Represents the component for displaying machine learning results.

Please refer to the component files for more information on their functionalities and usage.

## Dependencies

The application relies on the following dependencies:

- `react`: JavaScript library for building user interfaces.
- `react-router-dom`: Library for handling routing in a React application.
- `react-toastify`: Library for displaying toast notifications.
- `react-hot-toast`: Library for showing animated toast messages.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using the React App!
