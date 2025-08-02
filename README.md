Network Traffic Analysis & SIEM Deployment
This project is a hands-on simulation that demonstrates a Security Information and Event Management (SIEM) solution. It showcases the core principles of network traffic analysis, log collection, and real-time threat detection and visualization.

The project consists of a Python Flask backend that simulates network traffic, applies custom threat detection rules, and an HTML/JavaScript frontend that acts as a real-time monitoring dashboard.

Features
Simulated Network Traffic: The backend generates a continuous stream of mock network events, including source/destination IPs, protocols, and ports.

Custom Threat Detection: A simple SIEM rule is implemented by flagging traffic to or from a predefined list of "malicious" IP addresses.

Real-time Analysis: The Python application processes the simulated logs in real-time to calculate key metrics.

Interactive Web Dashboard: A responsive web interface visualizes key metrics and threat data using dynamic charts, mimicking a professional SIEM dashboard.

API-Driven: The frontend fetches data from a RESTful API endpoint, demonstrating a decoupled and scalable architecture.

Technologies Used
Backend: Python 3, Flask

Frontend: HTML5, CSS3 (Tailwind CSS), JavaScript

Data Visualization: Chart.js

Dependencies: flask_cors

Setup and Installation
Clone the repository (if applicable) or save the files:

Save the Python code as app.py.

Create a folder named templates in the same directory.

Save the HTML code as index.html inside the templates folder.

Install Python dependencies:
Open your terminal or command prompt and run the following command to install Flask and its dependencies:

pip install Flask flask_cors

How to Run
Start the server:
From your terminal, navigate to the project directory and run the Python application:

python app.py

Access the dashboard:
Open a web browser and go to the following URL to see the real-time dashboard:
http://127.0.0.1:5000

Future Enhancements
Advanced Threat Detection: Implement more sophisticated rules to detect patterns like port scanning, DDoS attacks, or unusual user behavior.

Log Persistence: Instead of an in-memory deque, use a database (e.g., SQLite, PostgreSQL) or a log file to store historical data.

User Interface Improvements: Add more visualizations, filters, and a list of live malicious events to the dashboard.

Integration with Real Tools: Connect the simulated data to an open-source SIEM like Elasticsearch + Kibana for a more complete deployment.
