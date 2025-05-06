# Worksphere 🌐

Worksphere is a comprehensive **Human Resources Management Application** developed using Symfony and MySQL. Designed to streamline HR administrative tasks, it offers a suite of features for efficient employee management, event organization, training coordination, and project oversight. Developed as part of the PIDEV 3A course at Esprit School of Engineering, this project emphasizes advanced web development and AI integration.

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
   Edit the .env file to configure your database settings
     ```bash
   For example:DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"
3. **Set up database**
     ```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load

4. **Launch development server**
     ```bash
symfony serve
