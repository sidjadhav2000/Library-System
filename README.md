(a)How to Run the Project:
1.Unzip the folder and navigate to the lib_system directory.
2.Open Command Prompt (CMD) in that folder by typing cmd in the address bar of the folder and pressing Enter.
3.Ensure you have Python installed (version 3.x recommended). Install Flask and SQLite dependencies by running:
(pip install Flask sqlite3)
4.Run the Flask application by typing: (python app.py)
5.After running the command, the server will start, and you will see the URL (e.g., http://127.0.0.1:5000).
6.Open a web browser (like Chrome) and paste the URL to access the API.

(b)The design choices made:
1.Flask Framework: Flask was chosen due to its simplicity and flexibility for building RESTful APIs. 
2.SQLite Database: SQLite was used as the database for this project because it is a file-based, lightweight database that does not require separate server installations. 
3.RESTful API Structure: The project follows a RESTful API design with separate routes for each operation (CRUD for books and members). 
4.JSON Response: JSON was chosen as the format for communication between the server and client, ensuring easy parsing on the client-side and compatibility with web and mobile applications.

(c) Any assumptions or limitations: No Limitations
