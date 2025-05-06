🧠 Worksphere
Worksphere is a comprehensive human resources management application developed using Symfony and MySQL. It streamlines various HR-related tasks such as employee management, event planning, project oversight, training, recruitment, and more.

This project was built as part of the PIDEV 3A course at Esprit School of Engineering, focusing on advanced web development and AI integration.

📑 Table of Contents
Features

Advanced Features

Installation

Usage

Contributing

License

Contact

Technologies Used

Acknowledgements

✅ Features
User Authentication & Management
Secure login, registration, and profile management.

Employee Management
Add, update, delete, and view employee records.

Event Management
Organize, update, and manage internal events.

Formation (Training) Management
Add and manage training sessions.

Project Management
Track progress, assign teams, and manage tasks.

Team Management
Create and manage project teams.

Reservation System
Allow employees to reserve training sessions.

Reclamation Management
Submit and track employee complaints.

Job Offers
Create and manage job postings.

Interview Management
Schedule and organize interviews.

Feedback System
Collect and manage interview feedback.

🚀 Advanced Features
🔐 Facial Recognition Login
AI-powered secure authentication.

🔓 Google OAuth Integration
Log in using Google accounts.

🚫 User Banning System
Admin tools for banning and managing users.

🤖 AI-Powered Sponsor Suggestions
Smart event sponsor suggestions based on type.

☁️ Cloud Storage Integration
Store project-related data securely.

🎥 Online Meeting Integration
Conduct remote training sessions online.

📄 AI-Based CV Filtering
Automatically rank and filter job applications.

⚙️ Installation
Follow these steps to set up the project locally:

Clone the repository

bash
Copier
Modifier
git clone https://github.com/yourusername/worksphere.git
cd worksphere
Install dependencies

bash
Copier
Modifier
composer install
Install PHP
Make sure PHP is installed (Download here).

Configure the database
Edit the .env file:

env
Copier
Modifier
DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"
Set up the database

bash
Copier
Modifier
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
Start the Symfony server

bash
Copier
Modifier
symfony server:start
💻 Usage
Once running, open your browser and go to:
http://localhost:8000

Use the dashboard to access:
Employee Management

Event & Training Sessions

Team & Project Management

Interview Scheduling

Complaint & Job Offer Systems

Reservation & Feedback Panels

🤝 Contributing
We welcome all contributions!

Fork the repository

Create your branch:
git checkout -b feature-name

Commit your changes:
git commit -m "Add feature"

Push to your branch:
git push origin feature-name

Open a pull request

Please follow coding standards and include tests.

📄 License
Licensed under the MIT License. See the LICENSE file for details.

📬 Contact
For any questions, contact one of the contributors:

Yassine Bouras – GitHub

Eya Kassous – GitHub

Houssem Hbeib – GitHub

Molka Gharbi – GitHub

Jacem Jouili – GitHub

Asma Sellami – GitHub

🧰 Technologies Used
Symfony (Backend)

MySQL (Database)

JavaScript, HTML, CSS (Frontend)

Python (AI Integration)

🙏 Acknowledgements
This project was developed as part of the PIDEV 3A module at Esprit School of Engineering.
Special thanks to our professors and mentors for their support.
