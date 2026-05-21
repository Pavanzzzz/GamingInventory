F1 Driver Current Season Standings Website

A modern Formula 1 driver statistics website built using HTML, CSS, and JavaScript.
The application fetches real-time Formula 1 driver standings using the Jolpica F1 API and displays driver statistics in a clean and responsive interface.

Features
Search Formula 1 drivers by surname
Fetch live F1 driver standings from API
Display driver position, points, wins, nationality, and constructor
Responsive modern UI
Dynamic search functionality
Error handling for invalid searches
Keyboard Enter key support
Professional dark-themed design
Technologies Used
HTML5
CSS3
JavaScript
Fetch API
Jolpica F1 API
Google Fonts
API Used

Jolpica F1 API:

https://api.jolpi.ca/ergast/f1/current/driverStandings.json

The API provides:

Current F1 driver standings
Driver information
Team data
Championship points
Race wins
Project Structure
F1-Driver-Stats/
── index.html
── README.md
How To Run
Download or clone the repository
git clone <repository-link>
Open the project folder
Run index.html in any browser
Functionalities
Driver Search

Users can search drivers using their surname.

Examples:

verstappen
hamilton
leclerc
norris
Real-Time Data Fetching

The website fetches live driver standings data from the API using JavaScript Fetch API.

Dynamic UI Update

Driver statistics are dynamically inserted into the webpage after a successful API response.

Future Improvements
Driver profile images
Team logos
Race schedule section
Constructor standings
Driver comparison feature
Search suggestions
Season selector
Loading animations
Author

Developed by Pavan.

License

This project is open-source and intended for educational purposes.
