# VoClo_version3
VoClo_version3

# Table of Contents

Introduction

Features

Technologies Used

Project Structure

Installation

Usage

Contributing

License

Contact

Introduction

VoClo_version3 is a web-based voice cloning application that allows users to generate synthetic speech resembling a target voice. The project integrates advanced AI models and a user-friendly interface to enable seamless voice cloning. The system includes authentication, a dashboard, and voice processing functionalities.

Features

User Authentication: Secure login, registration, and OTP-based verification.

Dashboard: Provides access to voice cloning functionalities.

Voice Cloning: Uses AI to generate high-quality synthetic speech.

Web-Based Interface: HTML/CSS templates for user interaction.

Modular Structure: Separation of authentication, dashboard, and voice processing.

Technologies Used

Backend: Python (Flask)

Frontend: HTML, CSS

AI/ML: Deep learning models for voice cloning

Database: SQLite or another lightweight database

Project Structure

VoClo_version3/
│── main/
│   │── app.py            # Main application entry point
│   │── dashboard.py      # User dashboard logic
│   │── login.py          # Authentication handling
│   │── templates/        # HTML templates for UI
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── dashboard.html
│   │   ├── register.html
│   │   ├── verify_otp.html
│   │   ├── voice_auth.html
│── voice_clone_management/
│   │── AI_main.py        # Core voice cloning logic
│   │── app.py            # Voice cloning application logic
│   │── requirements.txt  # Dependencies for voice cloning module
│── requirements@main.txt # Dependencies for main application
│── README.md             # Project documentation

Installation

Prerequisites

Ensure you have Python 3 installed on your system.

Steps

Clone the Repository:

git clone https://github.com/Snehalatha124/VoClo_version3.git

Navigate to the Project Directory:

cd VoClo_version3

Create and Activate a Virtual Environment:

python3 -m venv env
source env/bin/activate  # On Windows, use 'env\Scripts\activate'

Install Dependencies:

pip install -r requirements@main.txt
pip install -r voice_clone_management/requirements.txt

Run the Application:

python main/app.py

Access the application at http://127.0.0.1:5000/.

Usage

Register/Login: Create an account or log in.

Dashboard: Access voice cloning features.

Upload Voice Sample: Provide a target voice.

Generate Synthetic Voice: Enter text and generate speech.

Download Output: Save generated audio.

Contributing

We welcome contributions! To contribute:

Fork the Repository

Create a New Branch

Make Changes & Commit

Submit a Pull Request

License

This project is licensed under the MIT License.

Contact

Developer: Snehalatha124

GitHub: Snehalatha124

