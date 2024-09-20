# Quizify - Interactive Quiz Application

## Project Overview
Quizify is an interactive quiz application where users can take multiple-choice quizzes, track their scores, and receive feedback in real time. This project is developed using Python (Flask), HTML, and CSS.

## Features
- User authentication and session management.
- Multiple-choice quizzes with scoring and feedback.
- Responsive design.
- Quiz results stored in a database.
- REST API for retrieving quiz questions.

## Tech Stack
- **Back-End**: Python (Flask)
- **Front-End**: HTML, CSS
- **Database**: SQLite/PostgreSQL
- **Bonus Features**: REST API

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quizify.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quizify
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```
5. Run the application:
   ```bash
   flask run
   ```

## Future Improvements
- Implementing user-generated quizzes.
- Adding leaderboards.

