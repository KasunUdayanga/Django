# Little Lemon Restaurant

Welcome to the Little Lemon Restaurant project! This is a fully functional web application built using Django, a high-level Python web framework. The application allows users to browse the menu, learn about the restaurant, and make bookings.

## Features

1. **Menu List**: View a comprehensive list of items available on the menu.
2. **About**: Learn more about the restaurant, its history, and its mission.
3. **Booking**: Make a reservation at the restaurant with an easy-to-use booking system.

## Requirements

To run this project, you need to have the following installed on your system:

- Python 3.x
- Django 3.x
- SQLite (or another database system if you prefer)

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/little-lemon-restaurant.git
    cd little-lemon-restaurant
    ```

2. **Create a Virtual Environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:

    ```bash
    pip install django
    ```

4. **Run Migrations**:

    ```bash
    python manage.py migrate
    ```

5. **Create a Superuser**:

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the Development Server**:

    ```bash
    python manage.py runserver
    ```

    Visit `http://127.0.0.1:8000/` in your browser to see the application.

## Project Structure

- `little_lemon_restaurant/`: Project directory.
- `menu/`: Django app for managing the restaurant's menu.
- `about/`: Django app for the about page.
- `booking/`: Django app for managing table bookings.
- `templates/`: HTML templates for rendering pages.
- `static/`: Static files (CSS, JavaScript, images).
- `requirements.txt`: List of dependencies.
- `manage.py`: Django's command-line utility.

## Configuration

- **Database**: By default, this project uses SQLite. If you want to use another database (e.g., PostgreSQL), update the `DATABASES` setting in `settings.py`.

- **Static Files**: Ensure that the `STATIC_URL` and `STATIC_ROOT` settings in `settings.py` are configured correctly for production.

## Usage

1. **Menu**: Navigate to `/menu/` to see the list of menu items. 
2. **About**: Visit `/about/` to learn more about the Little Lemon Restaurant.
3. **Booking**: Go to `/booking/` to make a reservation.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries or feedback, please contact us at udayangakasun696@gmail.com

