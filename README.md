# WatchTrailer

## Overview

**WatchTrailer** is a dynamic web application that allows users to watch trailers and book tickets for their favorite movies. The application is built using **HTML**, **CSS**, and **JavaScript**, with additional technologies such as **PHP** and **DBMS** for backend and database management.

## Features

- **Movie Listings:** Browse a curated list of movies with their trailers and descriptions.
- **Trailer Playback:** Watch trailers directly on the platform.
- **Booking System:** Book tickets for your favorite movies with an easy-to-use interface.
- **Responsive Design:** Optimized for devices of all sizes.
- **User-Friendly Interface:** Simple and intuitive UI for seamless navigation.

## Tech Stack

### Frontend
- **HTML:** Structure of the web application.
- **CSS:** Styling for an aesthetically pleasing and responsive design.
- **JavaScript:** Interactivity and dynamic features.

### Backend
- **PHP:** Handles server-side logic for the booking system.
- **DBMS:** Manages user and booking data securely.

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/WatchTrailer.git
   cd WatchTrailer
   ```

2. **Set Up the Database:**
   - Create a database named `watchtrailer`.
   - Import the provided `database.sql` file into your database.

3. **Configure Backend:**
   - Open `config.php` in the project directory.
   - Update database credentials (host, username, password, database name).

4. **Start a Local Server:**
   - Use tools like **XAMPP**, **MAMP**, or **WAMP** to start a local server.
   - Place the project files in the server's root directory (e.g., `htdocs` for XAMPP).

5. **Run the Application:**
   - Open your browser and navigate to `http://localhost/WatchTrailer`.

## Usage

1. Browse through the list of movies.
2. Watch the trailers for any movie by clicking the "Watch Trailer" button.
3. Book tickets for movies using the booking system.

## Screenshots

### Homepage
![Homepage](screenshots/homepage.png)

### Trailer Page
![Trailer Page](screenshots/trailer-page.png)

### Booking Page
![Booking Page](screenshots/booking-page.png)

## Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Movie data and trailers from [TMDb](https://www.themoviedb.org/) API.
- Design inspiration from modern streaming platforms.

---
