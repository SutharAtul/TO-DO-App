# TO-DO-App
TO_DO Web-Application using PostgreSQL to perform update, delete, create, and read operation.  
If you want to clone this project you should have follow some steps.
# 1. Clone the Repository

git clone https://github.com/your-username/your-repo.git  
cd your-repo  

# 2. Install Dependencies
Run the following command to install all necessary dependencies:

npm install  
 OR  
pip install -r requirements.txt  

# 3. Set Up the Database
Install PostgreSQL:

Download and install PostgreSQL from https://www.postgresql.org/download/.
Create a Database:

Open the PostgreSQL shell or use a GUI like pgAdmin.
Create a database using:

CREATE DATABASE your_database_name;  
Set Up Database Configuration:

Update the database.config file (or .env) with your database credentials:

DB_HOST=localhost  
DB_PORT=5432  
DB_USER=your_username  
DB_PASSWORD=your_password  
DB_NAME=your_database_name  
