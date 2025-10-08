
🌮 Tattler API Project - Challenge 4
📖 Project Description
This project involves the transformation of the Tattler restaurant directory platform. It will use a non-relational database (MongoDB) and a RESTful API developed with Express.js to offer users a personalized and dynamic experience.

The core functionalities will include adding comments, rating establishments, and registering new restaurants.

🚀 Installation and Usage Instructions
To set up and run this project in a local environment, follow these steps:

1. Clone the Repository
   First, clone the project from GitHub to your local machine:

Bash

git clone https://github.com/Diego2gonzalez/Tattler-project.git
2. Restore the Database
   Use the backup file located in the /backup folder to restore the tattlerDB database. Open a terminal and run the following command:

Bash

mongorestore --archive="./backup/tattler.gz" --gzip
3. Install Dependencies (Sprint 2 onwards)
   Navigate to the project directory and install the required packages.

Bash

# Navigate into the project folder
cd Tattler-project

# Install dependencies
npm install
4. Start the Server (Sprint 2 onwards)
   Once the dependencies are installed, you can start the API server.

Bash

npm start
📁 Repository Structure
The project is organized into the following main folders:

Tattler-project/
├── 📂 backup/         # Contains the MongoDB database backups (`mongodump`).
├── 📂 scripts/        # Includes scripts or instructions for data import (`mongoimport`).
├── 📂 screenshots/    # Stores screenshots of the database structure and content.
└── 📄 README.md        # This file.