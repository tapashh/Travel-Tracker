# Travel Tracker 🌍

A simple web application to track the countries you have visited.

## Features ✨
- Add visited countries by name.
- View a list of visited countries.
- Prevent duplicate entries.
- Uses PostgreSQL for data storage.

## Tech Stack 🛠
- **Frontend**: EJS (Embedded JavaScript)
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL

## Installation ⚙️

1. **Clone the repository**
   ```sh
   git clone https://github.com/tapashh/travel-tracker.git
   cd travel-tracker
2. **Install dependencies**
   npm install
3. **Set up PostgreSQL**
   Create a database named World.
   Ensure you have a countries table with country_code and country_name fields.
   Ensure you have a visited_countries table with country_code as a field.
5. **Configure environment variables**
   Update index.js with your PostgreSQL credentials.
6. **Run the application**
   npm start
   or
   node index.js
7. **Access the app**
   Open http://localhost:3000 in your browser.

## Future Enhancements 🚀
Add authentication for personalized tracking.
Include a map visualization of visited countries.
Implement a REST API for better extensibility.

## License 📜
This project is licensed under the ISC License.
