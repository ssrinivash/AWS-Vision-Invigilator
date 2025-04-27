# AWS-Vision-Invigilator
Project Overview
This Cheating Surveillance System is designed to monitor user activities on a computer to detect potential cheating or unethical behavior. It logs keystrokes, mouse movements, clipboard contents, and captures frames from a webcam to analyze the user's focus and actions. The system includes a Flask backend that processes and serves the logged data, and a frontend that displays the data and allows interaction, such as viewing captured images and analyzing risk levels associated with the logs.​
GitHub

Key Features
Keystroke Logging: Captures all keystrokes along with timestamps and the active window titles.

Mouse Movement Logging: Tracks mouse movements and logs window switches and other significant events.

Clipboard Monitoring: Records any text that is copied to the clipboard.

Webcam Surveillance: Captures frames based on specific triggers such as significant eye movement or leaving the workstation.

Risk Analysis: Analyzes the collected data to assess the risk level of cheating or unethical behavior.

Dynamic Reporting: Provides an interface to view detailed logs and the risk analysis results.

Feedback System: Allows users to provide feedback on the system's risk assessment, which is used to train a reinforcement learning model to improve accuracy.​
IJNRD
+2
GitHub
+2
ResearchGate
+2

Technologies Used
Python: Core backend development.

Flask: Server-side web framework used for handling web requests and serving the web application.

HTML/CSS/JavaScript: Frontend development for displaying data and interacting with the backend.

Bootstrap: For responsive design and styled components.

Reinforcement Learning: Used to enhance risk analysis based on user feedback.​
GitHub

Project Structure
app.py: Main Flask application file with route definitions.

ScoringModel.py: Contains the logic for parsing logs, calculating cheating scores, and managing the reinforcement learning agent.

templates/: Contains HTML files for the web interface.

static/: Contains CSS, JavaScript, and other static files.

Eye-Tracker/: Directory storing captured frames and webcam logs.

Keylogger/: Directory containing keystroke logs.​
