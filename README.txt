==============================
Cyber Cafe Management System
==============================

This is a Django-based web application designed to manage a cyber cafe. It uses MySQL as the backend database.

How to Run:
-----------

1. Create a virtual environment:
   python -m venv venv
   venv\Scripts\activate      (on Windows)
   source venv/bin/activate     (on Mac/Linux)

2. Install dependencies:
   pip install -r requirements.txt

3. Create a MySQL database:
   - Database Name: ccmspythondb
   - Import the SQL file provided in the 'MySQL File' folder using MySQL Workbench:
     - Open MySQL Workbench
     - Create a schema named `ccmspythondb`
     - Open 'MySQL File/ccmspythondb.sql' and run it to populate the database

4. Apply migrations (if needed):
   python manage.py makemigrations
   python manage.py migrate

5. Run the server:
   python manage.py runserver

6. Open your browser and go to:
   http://127.0.0.1:8000/

Admin Credentials:
------------------
Login at: http://127.0.0.1:8000/admin/

Username: admin@gmail.com
Password: Test@123

Other Notes:
------------
- Developed using Django and MySQL.
- Ensure MySQL server is running before starting Django.

