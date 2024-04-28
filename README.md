# Guess the Capital Game

This is a fun guessing game built with Express.js and PostgreSQL. Test your knowledge of world capitals by guessing the correct capital for a given country!

## Features

- Random selection of countries for guessing.
- Earn one point for each correct answer.
- Game ends when an incorrect answer is entered.

## Setup Instructions

Follow these steps to run the game on your local machine:

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/OmarSharieff/Countries-Capitals.git
   ```

2. Navigate to the project directory:
   ```
   cd Countries-Capitals
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Set up PostgreSQL:
   - Ensure PostgreSQL is installed on your local machine.
   - Create a new database for the project.

5. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     PGHOST=localhost
     PGUSER=your_postgres_username
     PGDATABASE=your_database_name
     PGPASSWORD=your_database_password
     PGPORT=5432
     ```

6. Run the application:
   ```
   nodemon index.js
   ```

7. Access the game:
   - Open your web browser and go to `http://localhost:3000`.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

---

Feel free to adjust any details or add more information to the README as needed!