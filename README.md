# WheelDeal Web Application

Welcome to WheelDeal, a web application built using HTML, CSS, Bootstrap, JavaScript, jQuery, Python 3, and Django. WheelDeal is designed to provide a platform for buying and selling cars and bikes.

## Features

- User Registration and Authentication: Users can create accounts, log in, and log out. Authentication ensures secure access to the application's features.
- Product Listing: Sellers can list their cars and bikes for sale, including details such as brand, size, condition, price, and image.
- Search and Filtering: Users can search for specific products based on various criteria such as brand, transmission, and model. Filtering options allow for a refined search experience.
- Product Detail: Users can view detailed information about a specific product, including images, descriptions, seller information, and contact details.
- User Profiles: Registered users have personalized profiles where they can manage their listings and update account information.
- Admin Panel: The application includes an admin panel with appropriate access controls for managing user accounts, product listings, and site configuration.

## Installation and Setup

To run the WheelDeal web application locally, follow these steps:

1. Install Python 3: Ensure you have Python 3 installed on your machine. You can download it from the official Python website.
2. Clone the Repository: Clone the WheelDeal repository from GitHub using the following command:
```
git clone https://github.com/NiviShukla/WheelDeal.git
```
3. Create a Virtual Environment: Set up a virtual environment for the project to isolate its dependencies. Use the following command:
```
python3 -m venv wheeldeal-env
```

4. Activate the Virtual Environment: Activate the virtual environment using the appropriate command based on your operating system:
- For Windows:
  ```
  wheeldeal-env\Scripts\activate
  ```
- For macOS/Linux:
  ```
  source wheeldeal-env/bin/activate
  ```

5. Install Dependencies: Navigate to the project directory and install the required dependencies using pip:
```
pip install -r requirements.txt
```

6. Set Up the Database: Configure the database settings in the `settings.py` file. You can use SQLite for development purposes or set up a different database system like PostgreSQL or MySQL.

7. Apply Database Migrations: Apply the necessary database migrations using the following command:
```
python manage.py migrate
```

8. Create a Superuser: Create a superuser account to access the admin panel and manage the application:
```
python manage.py createsuperuser
```

9. Run the Application: Start the development server using the following command:
```
python manage.py runserver
```
10. Access the Application: Open your web browser and visit `http://localhost:8000` to access the WheelDeal web application.

## Screenshots
![Profile](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(42).png)
Profile

![Listings](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(43).png)
Listings and Liked Listing

![Wheeldeal Homepage 1](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(44).png)
Wheeldeal Homepage 1

![Wheeldeal Homepage 2](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(45).png)
Wheeldeal Homepage 2

![Wheeldeal Main Page](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(47).png)
Wheeldeal Main Page

![Login](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(49).png)
Login

![Register](https://github.com/NiviShukla/WheelDeal/blob/963eb8935369b58345f8b9496dbd1648e3343d62/Screenshots/Screenshot%20(48).png)
Register


## Contributing

We welcome contributions to the WheelDeal project. If you find any issues or have ideas for enhancements, please submit them through the GitHub issue tracker. Additionally, feel free to fork the repository and submit pull requests with your proposed changes.
