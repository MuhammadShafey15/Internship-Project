Cricket Match Scheduling System

This project is developed as part of my Internship Task.
It is a Python-based Cricket Tournament Scheduler that automatically generates fixtures for a cricket tournament, assigns venues and dates, and organizes League Matches, Semi-Finals, and a Final.

🎯 Internship Task Details

Task Name: Cricket Match Scheduling System

Technology: Python

Objective: Build a scheduling system that generates fixtures and assigns venues/dates for a cricket tournament.

🚀 Features

Add any number of teams (handles odd number by assigning a "BYE").

Add multiple venues for matches.

Generates round-robin league fixtures.

Automatically assigns dates and venues starting from the tournament start date.

Randomly selects Top 4 teams for Semi-Finals.

Creates Semi-Finals and Final Match with placeholders for winners.

🛠️ Setup & Installation
1. Clone the Repository
git clone https://github.com/your-username/cricket-scheduler.git
cd cricket-scheduler

2. Install Python

Make sure Python 3.7 or above is installed.
Check version:

python --version

3. (Optional) Create Virtual Environment
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

4. Install Requirements

This project only uses Python’s standard library (datetime, random).
No external installation is required.
But for best practice, use:

pip install -r requirements.txt

▶️ Running the Project

Run the script in terminal:

python cricket_scheduler.py


You will be asked to provide:

Number of teams and their names

Number of venues and their names

Tournament start date (YYYY-MM-DD)

The system will then generate and display the Complete Tournament Schedule.

📋 Example Output
=== Cricket Match Scheduling System ===
Enter number of teams: 4
Enter name of Team 1: Tigers
Enter name of Team 2: Warriors
Enter name of Team 3: Kings
Enter name of Team 4: Strikers
Enter number of venues: 2
Enter name of Venue 1: National Stadium
Enter name of Venue 2: City Ground
Enter tournament start date (YYYY-MM-DD): 2025-09-01

=== Complete Tournament Schedule ===
Date         Team 1          Team 2          Venue                Match Type
--------------------------------------------------------------------------------
01-Sep-2025  Tigers          Strikers        National Stadium     League
02-Sep-2025  Warriors        Kings           City Ground          League
03-Sep-2025  Tigers          Kings           National Stadium     League
04-Sep-2025  Strikers        Warriors        City Ground          League
...

Top 4 Teams (for Semi-Finals): ['Kings', 'Strikers', 'Tigers', 'Warriors']

📌 Future Enhancements

Add a Points Table System to decide Top 4 teams instead of random selection.

Export schedules into CSV/Excel/JSON formats.

Build a Flask/Django Web App for a UI-based experience.

Add time slots for matches.

👨‍💻 Author

Name: Muhammad Shafey

Role: Internship Trainee

Task: Cricket Match Scheduling System
