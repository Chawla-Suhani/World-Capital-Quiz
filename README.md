A simple world quiz app where users answer questions related to different countries. The app fetches random questions from a PostgreSQL database and checks user answers. The score increases with every correct answer.

**Features**
==>Random questions fetched from a PostgreSQL database
==>User can submit their answer
==>The app checks the user's answer against the database
==>Score increases with each correct answer
==>Built using Node.js, Express, PostgreSQL, and EJS

**Technologies Used**
==>Node.js: Backend server
==>Express: Web framework for Node.js
==>PostgreSQL: Database for storing quiz questions and answers
==>EJS: Templating engine for rendering HTML pages

**Installation**
Clone the repository: git clone https://github.com/Chawla-Suhani/World-Capital-Quiz.git

**Install dependencies:**
cd world-quiz-app
npm install

Set up PostgreSQL:
==>Create a database in PostgreSQL (e.g., world_quiz_db).
==>import data from capital.csv file which is present in repository

Configure PostgreSQL connection:

In your project, open config/database.js (or the relevant config file).

Update the connection settings to match your PostgreSQL setup.

**Start the server:**
==>nodemon index.js

==>Open your browser and go to http://localhost:3000.
