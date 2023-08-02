# PG-Life | [live](http://pglife-pureshwar.42web.io/)
</hr>

## Overview

PG-Life is a fully responsive website that allows users to book PG accommodations from different regions. The website is implemented using HTML, CSS, Bootstrap, and PHP. It utilizes a MySQL database connected through PHP to manage property listings, bookings, and user data. The website consists of several key pages: Home Page, Property List Page, Property Detail Page, and Dashboard Page.

## Key Features

- **Home Page:** The landing page of the website welcomes users and provides an overview of the services offered by PG-Life.

- **Property List Page:** This page displays a list of available PG accommodations in different regions. Users can browse through the listings and filter properties based on preferences such as location, price range, and amenities.

- **Property Detail Page:** When users click on a specific property from the list page, they are directed to the property detail page. This page provides comprehensive information about the selected PG, including images, description, amenities, and contact details.

- **Dashboard Page:** Registered users have access to their personalized dashboard. From here, they can manage their bookings, view payment history, and update their profile information.

## Database Design

The database for the PG-Life web application is designed to store essential data related to users, properties, bookings, and payments. The key tables in the database include:

- **Users:** Stores user information such as user ID, name, email, password (hashed), and contact details.

- **Properties:** Contains details about each PG property, including property ID, name, address, description, amenities, price, and region.

- **Bookings:** Tracks information about user bookings, including booking ID, user ID, property ID, check-in date, check-out date, total cost, and status.

- **Payments:** Records payment information, including payment ID, booking ID, payment date, amount, and transaction details.

## ScreenShots

![Home Page](https://github.com/PureshwarGonekar/PG-Life/assets/88015818/5c8b6fbf-668f-4182-a3bf-5e0450f7bc9a)

![Dashboard](https://github.com/PureshwarGonekar/PG-Life/assets/88015818/d5d247ae-5ab1-4d0f-a9a6-619edbda9924)

![Amenties)](https://github.com/PureshwarGonekar/PG-Life/assets/88015818/3305f720-d602-439e-8bbe-0d1fa671cd9d)

## Setup Instructions

1. Clone the repository from GitHub: `git clone https://github.com/your_username/PG-Life.git`.

2. Set up a web server (e.g., Apache) and PHP on your system.

3. Create a MySQL database and import the database schema provided in the `database_schema.sql` file.

4. Update the `config.php` file with your database credentials and configuration settings.

5. Upload the website files to your web server.

6. Launch the website by accessing the appropriate URL in your web browser.

## Requirements

- Web server with PHP support
- MySQL database
- Modern web browser (Chrome, Firefox, Safari, Edge, etc.)

## Contributors

- [Pureshwar Gonekar](https://github.com/PureshwarGonekar)

## Known Issues

- [List of known issues, if any]

## Support

If you encounter any issues or have any questions, please feel free to contact us at pureshwargonekar7@gmail.com.


