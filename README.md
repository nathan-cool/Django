# Django Polls Application

## Overview
This Django Polls Application, developed by Nathan, is a simple yet interactive web application designed to create and vote on polls. It's a great demonstration of Django's capabilities for handling web forms, user interaction, and database management.

## Features
- **Create Polls:** Users can create polls with multiple choices.
- **Vote:** Allows users to vote on different polls.
- **Results:** Displays poll results with a count of votes for each choice.
- **Admin Panel:** An admin interface to add, change, or delete polls.

## Installation

### Prerequisites
- Python 3.8 or higher
- Django 3.2 or higher

### Steps
- 1. Clone the repository:
git clone https://github.com/nathan-cool/Django.git
cd Django

- 2. Install dependencies:
pip install -r requirements.txt

- 3. Migrate the database:
python manage.py migrate

- 4. Create an admin user:
python manage.py createsuperuser

- 5. Run the server:
python manage.py runserver

- 6. Open a web browser and go to `http://127.0.0.1:8000` to view the app.

## Usage
To create and manage polls, log into the admin panel at `http://127.0.0.1:8000/admin` using the superuser credentials created earlier.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
