# Music Streaming Database Management System

This project offers a MySQL database system for managing streaming content, such as music, movies, or videos. Below are the steps to set up and run the system on your machine.

### UML and ER Diagram

![UMLDiagram](https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/e8803260-ec8a-477b-87d1-16ad5d35cf38)
![LogicDiagram-Photoroom png-Photoroom](https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/bb167a3a-240d-46bc-a677-120082c9d1e9)

### Working Flask App with SQL
<img width="800" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/e8b14f37-58f4-4947-ab30-45adc4386ffa">

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

### Images

#### Sign up
<img width="1496" alt="Screenshot 2024-03-05 at 12 10 04 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/26ee1caa-0c87-47c2-b209-70135b803a22">

#### Login 

<img width="1496" alt="Screenshot 2024-03-05 at 12 11 02 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/455e0112-be96-469e-9c11-0d840dac226a">

#### Playlist 
<img width="1496" alt="Screenshot 2024-03-05 at 12 11 18 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/81b602ef-a36e-4f37-9ec3-ee1305349195">

#### SQL Database

<img width="1496" alt="Screenshot 2024-03-05 at 12 12 02 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/55d802ca-cf4e-45da-9bdb-80817f84d33b">

<img width="1496" alt="Screenshot 2024-03-05 at 12 13 06 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/f3e0f174-2217-4f65-89dc-d4da0f775854">

#### Profile

<img width="1496" alt="Screenshot 2024-03-05 at 12 16 35 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/8807cf7b-bd96-4e7c-adf7-4fb43d79cf88">

#### Songs List
<img width="1496" alt="Screenshot 2024-03-05 at 12 20 23 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/8c8aa2ba-9541-4a44-8fec-1c4cd4f6014a">

#### Edit Playlist

<img width="1496" alt="Screenshot 2024-03-05 at 12 20 39 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/e1cec2aa-f1b6-459c-a76b-dc3e25c89494">


