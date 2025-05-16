# Remote-Patient-Monitoring-System

**System Overview**
The Remote Patient Monitoring System is a comprehensive healthcare management platform that enables patients to connect with healthcare providers remotely.
The system includes features for appointment scheduling, vital signs monitoring, prescription management, and real-time communication.

**Prerequisites**
1. Java Development Kit (JDK) 17 or higher
2. MySQL Database Server 8.0 or higher
3. Maven (for dependency management)
4. JavaFX (included in the project dependencies)
   
**Database Setup**
1. Install MySQL Server if not already installed
2. Create a new database named 'remote_patient_monitoring'
3. Import the database schema from the 'database_rpms' file
4. Run all queries from the file
5. Update database connection settings in 'src/main/resources/config.properties':
- database.url=jdbc:mysql://localhost:3306/remote_patient_monitoring
- database.username=your_username
- database.password=your_password
  
**Project Setup**
1. Clone the repository to your local machine
2. Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse)
3. Install Maven dependencies:
- Right-click on pom.xml
- Select "Maven" -> "Reload Project"
4. Build the project:
- Run 'mvn clean install' in the project directory
  
**Running the Application**
1. Navigate to the project directory
2. Run the main class: 'src/main/java/UI/LoginPage.java'
3. The login screen will appear
   
**Login Instructions**
1. For First-Time Users:
- Click on "Sign Up" button
- Fill in the required information:
* User ID (unique identifier)
* Name
* Email
* Password
* Role (Patient/Doctor/Admin)
* Other required personal information
- Click "Register" to create your account
  
**2. For Existing Users:**
- Enter your email address
- Enter your password
- Select your role (Patient/Doctor/Admin)
- Click "Login"
  
**User Roles and Features**
1. Patient:
- View and book appointments
- Monitor vital signs
- View prescriptions
- Upload medical records
- Chat with doctors
- Video consultations
- Emergency alerts
2. Doctor:
- Manage patient appointments
- View patient vitals
- Write prescriptions
- Review medical records
- Chat with patients
- Video consultations
- Respond to emergency alerts
3. Admin:
- Manage user accounts
- Monitor system activity
- Handle emergency alerts
- Generate reports
  
Predefined Users
The system comes with a few predefined users for demonstration purposes:

1. Doctors:
i. Dr Faisal Siddiqui
Email: faisal@gmail.com password: docpass201
ii. Dr. Nadia Hassan
Email: nadia@gmail.com password: docpass202

3. Administrator:
i. Zain Ul Abideen
Email: zain@gmail.com password: adminpass

**Troubleshooting**
1. Database Connection Issues:
- Verify MySQL server is running
- Check database credentials in config.properties
- Ensure database schema is properly imported
2. Application Launch Issues:
- Verify Java version (java -version)
- Check Maven dependencies are properly installed
- Ensure JavaFX is properly configured
3. Login Issues:
- Verify email and password
- Check if account exists in database
- Ensure correct role is selected
  
**Support**
For technical support or questions, please contact:
- Email: shahzadjatoi1800@gmail.com
Note: This is a demonstration system. In a production environment, additional security measures and proper error handling should be implemented.
