# Real Estate Management System

## Project Overview
The Real Estate Management System is a web application designed to streamline the management and operations of real estate properties. It provides an interface for users to manage property listings, user accounts, and more. The system includes different roles such as admin and general users to ensure proper access control and functionality.

Home Page:
![Screenshot (65)](https://github.com/user-attachments/assets/d723ad38-99b9-4f2c-b7ed-0949ccde68f3)
![Screenshot (66)](https://github.com/user-attachments/assets/324e72b9-ca05-40c7-9b2f-e1654e6ce153)
![Screenshot (67)](https://github.com/user-attachments/assets/1105d0d9-af6d-401c-8310-215eed8996b2)
![Screenshot (68)](https://github.com/user-attachments/assets/81a06d03-c66a-42d0-925d-80da2eba82a4)
![Screenshot (69)](https://github.com/user-attachments/assets/ae03a150-4e77-46e8-b4e6-cb1a50ff40ec)

## Features
- **User Management**: Admins can manage user accounts, including creating, updating, and deleting accounts.
- **Property Listings**: Users can add, update, and delete property listings with detailed information.
- **Property Search**: Users can search for properties based on various filters such as location, price, and type.
- **Property Details**: Detailed property pages with images and descriptions.
- **Authentication**: Secure login and registration system with password hashing.
- **Responsive Design**: Mobile-friendly design using Bootstrap for responsiveness.
- **Image Handling**: Use of `ImageField` for uploading and managing property images.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Django
- **Database**: PostgreSQL
- **Other**: Django ORM, Django Templates, Python

## Setup Instructions

### Prerequisites
- Python 3.x
- PostgreSQL
- Git

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/2000032059/real-estate-management-system.git
   cd real-estate-management-system
Set Up Virtual Environment

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies

bash
pip install -r requirements.txt
Set Up the Database

Create a PostgreSQL database.
Update the settings.py file with your database credentials.

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_database_name',
        'USER': 'your_database_user',
        'PASSWORD': 'your_database_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
Apply Migrations

bash
python manage.py makemigrations
python manage.py migrate
Create a Superuser

bash
python manage.py createsuperuser
Run the Development Server


python manage.py runserver
Access the Application
Open your web browser and go to http://127.0.0.1:8000/.

Usage
Admin: Log in with the admin credentials to access the admin panel for managing users, properties, and other settings.
General Users: Register and log in to add properties, browse listings, and use other features.
Project Structure
php

real-estate-management-system/
│
├── manage.py
├── README.md
├── requirements.txt
├── venv/
│
├── myapp/  # Your Django app
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── models.py
│   ├── views.py
│   └── ...
└── ...


Contact
For any questions or suggestions, please contact kamsanigowtham9999@gmail.com.

