# Worksphere 🌐

Worksphere est une application complète de **gestion des ressources humaines** développée avec Symfony et MySQL. Conçue pour simplifier les tâches administratives RH, elle offre une suite d'outils pour gérer efficacement les employés, organiser des événements, coordonner des formations et superviser des projets. Ce projet a été réalisé dans le cadre du cours PIDEV 3A à **l'École supérieure privée d'ingénierie et de technologie**, mettant l'accent sur le développement web avancé et l'intelligence artificielle.

---

## ✨ Fonctionnalités  

### Fonctionnalités principales  
- **🔐 Authentification sécurisée** : Connexion, inscription et gestion de profil  
- **👥 Gestion des employés** : Opérations CRUD complètes  
- **📅 Gestion des événements** : Organisation et suivi des événements d'entreprise  
- **🎓 Gestion des formations** : Création et gestion des sessions de formation  
- **📊 Gestion des projets** : Création de projets, affectation d'équipes et suivi de progression des taches 
- **🤝 Gestion des équipes** : Formation et administration des équipes  
- **📝 Système de réservation** : Réservation de places pour les formations  
- **📢 Système de réclamation** : Soumission et résolution des plaintes  
- **💼 Gestion des offres d'emploi** : Publication et gestion des opportunités  
- **🗣️ Gestion des entretiens** : Planification et conduite des entretiens  
- **💬 Système de feedback** : Collecte et analyse des retours d'entretiens  

### Fonctionnalités avancées  
- **👁️ Reconnaissance faciale** : Authentification sécurisée par IA  
- **🔑 Connexion via Google (OAuth)** : Simplification de la connexion  
- **🚫 Bannissement des utilisateurs** : Outils de modération avancés  
- **🤖 Suggestions de sponsors par IA** : Recommandations intelligentes pour événements  
- **☁️ Stockage cloud** : Sauvegarde sécurisée des données  
- **💻 Réunions virtuelles** : Sessions de formation en ligne intégrées  
- **📄 Filtrage intelligent des CV** : Analyse automatisée des candidatures 

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

## 📜 Licence
Ce projet est sous licence MIT – voir le fichier LICENSE pour plus de détails.

## 📬 Contact
Équipe de développement :

Yassine Bouras - yassine.bouras@esprit.tn

Eya Kassous - eya.kassous@esprit.tn

Houssem Hbeib - houssem.hbeib@esprit.tn

Molka Gharbi - molka.gharbi@esprit.tn

Jacem Jouili - jacem.jouili@esprit.tn

Asma Sellami - asma.sellami@esprit.tn

## 💻 Technologies utilisées
Backend: Symfony 6.4

Database: MySQL 8

Frontend: JavaScript, HTML5, CSS3

Intégration IA: Python, TensorFlow, OpenCV

## 🙏 Remerciements
Ce projet a été développé dans le cadre du cours PIDEV 3A **l'École supérieure privée d'ingénierie et de technologie**. Nous tenons à remercier nos professeurs et mentors pour leur précieux encadrement et leur soutien tout au long du développement.

