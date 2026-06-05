# PSUSphere

A Django-based project for managing student organizations at PSU.  
This project demonstrates the use of Django models, admin customization, and Faker for generating sample data.

## Features
- College, Program, Organization, Student, and OrgMember models  
- Django Admin interface with search, filters, and custom list displays  
- Superuser account for managing records  
- Faker integration for generating sample data  
- Requirements.txt for dependency tracking  
- GitHub version control integration

## Installation
1. Clone the repository:  
    git clone <your-github-url>

2. Create and activate a virtual environment:  
    python -m venv psusenv  
    # Windows  
    psusenv\Scripts\activate  
    # Linux/Mac  
    source psusenv/bin/activate

3. Install dependencies:  
    pip install -r requirements.txt

4. Run migrations:  
    python manage.py migrate

5. Create a superuser:  
    python manage.py createsuperuser

6. Start the server:  
    python manage.py runserver

## Running with Docker
This project can also be run inside a Docker container.

### Prerequisites
- Docker  
- Docker Compose

### Build and Run
    docker-compose build
    docker-compose up

The app will be available at:  
http://localhost:8000

## Notes
- Uses **Python 3.12** and **Django 6.0.2**  
- Dependencies are installed from `requirements.txt`  
- Development server only — **not** for production use

## Authors
- Marife Joy Aguilar  
- Princess Joy Ago

## License
This project is for educational purposes only.
