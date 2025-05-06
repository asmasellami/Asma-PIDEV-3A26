# Worksphere 🌐

Worksphere est une application complète de **gestion des ressources humaines** développée avec Symfony et MySQL. Conçue pour simplifier les tâches administratives RH, elle offre une suite d'outils pour gérer efficacement les employés, organiser des événements, coordonner des formations et superviser des projets. Ce projet a été réalisé dans le cadre du cours PIDEV 3A à **l'École supérieure privée d'ingénierie et de technologie**, mettant l'accent sur le développement web avancé et l'intelligence artificielle.

---

## ✨ Features

### Core Functionalities
- **🔐 User Authentication**: Secure login, registration, and profile management
- **👥 Employee Management**: Full CRUD operations for employee records
- **📅 Event Management**: Organize and track company events
- **🎓 Training Management**: Create and manage training sessions
- **📊 Project Management**: Project creation, team assignment, and progress tracking
- **🤝 Team Management**: Team formation and administration
- **📝 Reservation System**: Training session spot reservations
- **📢 Reclamation System**: Complaint submission and resolution
- **💼 Job Offer Management**: Posting and managing employment opportunities
- **🗣️ Interview Management**: Scheduling and conducting interviews
- **💬 Feedback System**: Collect and analyze interview feedback

### Advanced Features
- **👁️ Facial Recognition**: AI-powered secure authentication
- **🔑 Google OAuth**: Simplified login via Google accounts
- **🚫 User Banning**: Comprehensive user management tools
- **🤖 AI Sponsor Suggestions**: ML-based event sponsor recommendations
- **☁️ Cloud Storage**: Secure project data storage
- **💻 Virtual Meetings**: Integrated online training sessions
- **📄 AI CV Filtering**: Intelligent application screening

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/worksphere.git
   cd worksphere
2. **Configure environment**
   Edit .env file :
   ```bash
   DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"
  
3. **Set up database**
   ```bash
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate
   php bin/console doctrine:fixtures:load

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact
Development Team:

Yassine Bouras - yassine.bouras@esprit.tn

Eya Kassous - eya.kassous@esprit.tn

Houssem Hbeib - houssem.hbeib@esprit.tn

Molka Gharbi - molka.gharbi@esprit.tn

Jacem Jouili - jacem.jouili@esprit.tn

Asma Sellami - asma.sellami@esprit.tn

## 💻 Technologies Used
Backend: Symfony 6.4

Database: MySQL 8

Frontend: JavaScript, HTML5, CSS3

AI Integration: Python, TensorFlow, OpenCV

## 🙏 Acknowledgements
This project was developed as part of the PIDEV 3A course at **Esprit School of Engineering**. We would like to express our gratitude to our professors and mentors for their invaluable guidance and support throughout the development process.

