# Hospital-Management-System
# eDoc-eChanneling

![Screenshot](https://github.com/hshnudr/edoc-echanneling/blob/main/Screenshots/Screenshot%20(1).png)

This is a simple web project designed to facilitate e-channeling for medical institutions such as clinics or hospitals. The platform allows patients to book appointments with doctors online, while doctors can manage their schedules efficiently. The system features three user roles: Administrator, Doctor, and Patient. 

The administrator manages the doctor listings, including their specialties and availability. Patients can use the platform to find doctors based on their needs, review their weekly schedules, and request appointments. Doctors can view patient requests and manage their own appointments.

### Features by Role:

#### 1. Admin:
- Add, edit, and remove doctors
- Schedule and cancel doctor sessions
- View patient details
- Access patient booking information

![Admin Screenshot](https://github.com/hshnudr/edoc-echanneling/blob/main/Screenshots/Screenshot%20(3).png)

#### 2. Doctors:
- View their appointment schedule
- Check their upcoming sessions
- Review patient details
- Delete or edit their account

![Doctor Screenshot](https://github.com/hshnudr/edoc-echanneling/blob/main/Screenshots/Screenshot%20(9).png)

#### 3. Patients:
- Book appointments online
- Create and manage their accounts
- View previous bookings
- Delete or update account details

![Patient Screenshot](https://github.com/hshnudr/edoc-echanneling/blob/main/Screenshots/Screenshot%20(6).png)

Each role (Admin, Doctor, and Patient) uses a unified login page for access.

---

## How to Get Started:

1. Open the XAMPP Control Panel and start both Apache and MySQL.
2. Extract the downloaded source code.
3. Copy the extracted folder into the XAMPP "htdocs" directory.
4. Open a browser and navigate to PHPMyAdmin (e.g., [http://localhost/phpmyadmin](http://localhost/phpmyadmin)).
5. Create a new database named `edoc`.
6. Import the SQL file located in the root directory (`edoc.sql`).
7. Browse the Doctor's Appointment System by navigating to [http://localhost/edoc-echanneling-main/](http://localhost/edoc-echanneling-main/).

---

### Database Name: `edoc`

### Built-in User Accounts:

**Admin**  
Email: `admin@edoc.com`  
Password: `123`

**Doctor**  
Email: `doctor@edoc.com`  
Password: `123`

**Patient**  
Email: `patient@edoc.com`  
Password: `123`
