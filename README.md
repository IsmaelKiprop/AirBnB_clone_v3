# Your Project Name

## Introduction

Brief introduction about your project.

## Installation

To get started with the project, follow these steps:

### 1. Install Dependencies

```bash
pip install -r requirements.txt

### 2. Set up the database and initialize storage

```bash
python setup.py

### 3. Run the Flask application

```bash
python run.py

## API Endpoints

The API provides the following endpoints:

- `/api/v1/states`: Manage states
- `/api/v1/cities`: Manage cities
- `/api/v1/amenities`: Manage amenities
- `/api/v1/users`: Manage users
- `/api/v1/places`: Manage places
- `/api/v1/reviews`: Manage reviews
- `/api/v1/places_search`: Search for places based on specified criteria

For detailed information on each endpoint, refer to the [API Documentation](API_DOCUMENTATION.md).

## Implementation Details

### Views

- `cities.py`: Manages City objects
- `amenities.py`: Manages Amenity objects
- `users.py`: Manages User objects
- `places.py`: Manages Place objects
- `places_reviews.py`: Manages Review objects
- `places_amenities.py`: Manages the link between Place and Amenity objects

### Security Improvements

- Passwords are hashed using MD5 for security.

### CORS Setup

CORS (Cross-Origin Resource Sharing) is implemented using Flask-CORS to allow web clients to access the API. The CORS instance is set to allow `/*` for `0.0.0.0`.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request.

## License

This project is licensed under the MIT License.
