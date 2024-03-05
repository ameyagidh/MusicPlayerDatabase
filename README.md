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

<img width="1496" alt="Screenshot 2024-03-05 at 12 10 42 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/d39a8871-7090-4829-923e-cb4231c0f0b3">
<img width="1496" alt="Screenshot 2024-03-05 at 12 10 30 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/7e335c84-6d73-40a3-8cc9-6d5849d368fa">
<img width="1496" alt="Screenshot 2024-03-05 at 12 10 04 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/7abd742a-c019-4501-a842-0fc8c2bdb0b3">

<img width="1496" alt="Screenshot 2024-03-05 at 12 10 54 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/773c0419-2506-4273-befd-49306e4ae8c4">
<img width="1496" alt="Screenshot 2024-03-05 at 12 11 02 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/35c46c2f-5308-4931-8b8c-b5dfc4f15747">

<img width="1496" alt="Screenshot 2024-03-05 at 12 11 13 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/7807165b-b366-4a26-a429-2722c62e1374">

<img width="1496" alt="Screenshot 2024-03-05 at 12 11 18 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/3eaa4edb-92ef-431e-9a12-09b10c9fa433">

<img width="1496" alt="Screenshot 2024-03-05 at 12 12 02 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/579eea1b-9160-4c43-8d61-7b67d529cc47">
<img width="1496" alt="Screenshot 2024-03-05 at 12 13 06 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/6d2de94f-cca4-47f6-944e-9a1753730ae6">
<img width="1496" alt="Screenshot 2024-03-05 at 12 16 26 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/45bf4cac-f351-44ca-bb60-cf06f2f0c92e">
<img width="1496" alt="Screenshot 2024-03-05 at 12 16 35 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/15af5d8a-97e5-4d36-b88c-90c41e2b76cb">

<img width="1496" alt="Screenshot 2024-03-05 at 12 16 39 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/535a48d2-5096-4b4e-b5bd-695affef7c43">

<img width="1496" alt="Screenshot 2024-03-05 at 12 16 39 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/184c8939-7208-414d-a543-b462d7b2dc57">

<img width="1496" alt="Screenshot 2024-03-05 at 12 16 46 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/e876572c-0505-472f-9791-8ad3ba8693c9">

<img width="1496" alt="Screenshot 2024-03-05 at 12 19 47 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/1d70c616-edb6-46d2-8a3f-4583f25b5d54">

<img width="1496" alt="Screenshot 2024-03-05 at 12 20 06 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/37df086c-cdd4-450c-adca-550b5356655a">

<img width="1496" alt="Screenshot 2024-03-05 at 12 20 10 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/e9cd3ffe-9f23-421d-8678-18dac1f9afa7">
<img width="1496" alt="Screenshot 2024-03-05 at 12 20 23 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/9bb9c5b0-38e1-4a87-900a-f1a5b9f0542a">

<img width="1496" alt="Screenshot 2024-03-05 at 12 20 25 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/5a85b2eb-cb9f-42d6-989e-fb468fe21f7b">


<img width="1496" alt="Screenshot 2024-03-05 at 12 20 39 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/12f1b1e5-f693-4f71-89dc-7ed1b769d8f3">

<img width="1496" alt="Screenshot 2024-03-05 at 12 20 47 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/6c178b0c-945c-476b-8003-1d9796334d89">

<img width="1496" alt="Screenshot 2024-03-05 at 12 11 02 AM" src="https://github.com/ameyagidh/MusicStreamingDatabase/assets/65457905/64c4c5ca-00f1-4a99-bbc4-6b0f08a0a08d">





