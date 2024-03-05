# Music Streaming Database Management System

This project offers a MySQL database system for managing streaming content, such as music, movies, or videos. Below are the steps to set up and run the system on your machine.

### Prerequisites:

1. **Python 3.x:** Install Python from the [official website](https://www.python.org/downloads/).
2. **MySQL Community Server 8.0 or above:** Download MySQL Community Server from the [official website](https://dev.mysql.com/downloads/mysql/).
3. **Operating System:** Compatible with Windows 10/8/7, Linux, and MacOS.
4. **Minimum System Requirements:** 
   - RAM: 128 MB
   - Free Storage: 10 MB
5. **Python Libraries:** Ensure the following libraries are installed:
   - `pymysql`: `pip install pymysql`
   - `cryptography`: `pip install cryptography`
   - `flask`: `pip install flask`
   - `flask-pymysql`: `pip install flask-pymysql`

### Import Database Dump into MySQL Workbench:

1. Open StreamingDatabaseDump.sql file in the root directory and run the commands.

### Setting Up Virtual Environment:

1. **Create Virtual Environment:**
   - Navigate to the project directory in the terminal.
   - Run the following command:
     ```
     python -m venv <name_of_virtualenv>
     ```
2. **Activate Virtual Environment:**
   - **Windows:**
     ```
     <name_of_virtualenv>\Scripts\activate
     ```
   - **Unix:**
     ```
     source <name_of_virtualenv>/bin/activate
     ```

### Importing Database Dump:

- Run the following command in the terminal:
  ```
  mysql -u root -p streamingdatabase < StreamingDatabaseDump.sql
  ```

### Running the Application:

1. **Configuration:**
   - Open `db_config.py` in the `FlaskApp` folder.
   - Modify `DB_SERVER`, `DB_USER`, and `DB_PASS` according to your MySQL credentials.
2. **Start Application:**
   - Navigate to the `FlaskApp` folder in the terminal.
   - Run the following command:
     ```
     python app.py
     ```
3. **Access Application:**
   - Copy the provided link from the terminal and paste it into a web browser.
4. **Interact with the Application:**
   - Use the interface to manage streaming content, such as adding, deleting, or updating records.

This Music Streaming Database Management System provides a robust platform for managing various types of Music Streaming content efficiently.
