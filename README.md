# Veterinary-Appoinment-System
Veterinary Appointment System is a role-based web application that streamlines clinic operations by managing pet records, appointments, treatments, and payments in one platform. It enables pet owners to book visits, vets to record diagnoses, and admins to oversee scheduling, ensuring efficient, secure, and organized veterinary care.

# Features
•	Role-based authentication (Admin, Veterinarian, Customer)
•	Appointment scheduling and vet assignment
•	Pet medical history tracking
•	Treatment and prescription management
•	Secure payment tracking and receipt generation
•	Administrative dashboard for clinic management


# Technology Stack
•	Python
•	Flask
•	MongoDB
•	HTML/CSS
•	Bootstrap

# How to Run This Project Locally (Windows)
Step 1: Clone or download the repository and navigate to the project folder.
Step 2: Create a virtual environment using: python -m venv venv
Step 3: Activate the virtual environment:
   - Command Prompt: venv\Scripts\activate
   - PowerShell (if blocked, first run Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser)
   - Then activate using: .\venv\Scripts\Activate.ps1
Step 4: Install dependencies using: pip install -r requirements.txt (or pip install flask)
Step 5: Run the Flask application using: flask --app app.py --debug run
Step 6: Open browser and go to http://127.0.0.1:5000
 
# Common Errors and Fixes
•	If scripts are disabled in PowerShell, run: Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
•	If Flask is not recognized, run: pip install flask
•	If you get 'Could not import app', ensure app.py exists and contains: app = Flask(__name__)


# Application Workflow
1. Customer registers and adds pet details
2. Customer requests appointment
3. Admin assigns veterinarian
4. Vet records diagnosis and treatment
5. Customer completes payment
6. Receipt is generated and stored
