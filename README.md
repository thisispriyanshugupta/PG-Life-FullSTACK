# PG-Life-FullSTACK

PG-Life-FullSTACK is a comprehensive full-stack web application designed to assist students and working professionals in finding comfortable accommodations. The app provides a seamless experience across various devices and offers personalized features.

## Web App Overview

- **Technology Stack**: Developed using HTML, CSS, Bootstrap, DBMS, JavaScript, PHP, React, and MySQL.

## Features

### Home Page

- **Search Bar**: Users can enter a city name (case-insensitive), and the app will display a list of available PGs in that city.
- **City Sections**: Circular sections represent main cities. Clicking on a city section reveals the list of PGs available in that city.

### PG List Page

- Displays a list of PGs with their main features in the selected city using visually appealing cards.
- **Filter Bar**: Users can sort PGs by rent and rating (ascending or descending order).
- Indicates the popularity of a PG by showing how many users have marked it as interested.
- Logged-in users can mark PGs as interested directly from the list by clicking the heart icon (which dynamically updates).

### PG Details Page

- Clicking on "View" in the property list page reveals detailed information about a selected PG.
- Features a carousel displaying images of the PG.
- Displays comprehensive details, including amenities, testimonials, and address.
- Indicates the popularity of the PG based on the number of users marking it as interested.
- Users can mark PGs as interested on this page, updating the heart icon dynamically.

### Dashboard (For Logged-in Users)

- Shows account details of the logged-in users.
- Includes a section for Interested Properties, displaying cards of PGs marked as interested across any city.
- Users can remove PGs from the interested list directly from the dashboard.

### Navbar

- Displays brand name.
- When not logged in, shows options for Signup and Login.
- When logged in, offers options to go to the Dashboard and Logout.
- Dynamically displays the logged-in user's first name using SESSION.
- Responsive toggler navbar.

### Breadcrumb

- Provides a visually appealing representation of the user's location in the web app.
- Contains hyperlinks for easy navigation.
