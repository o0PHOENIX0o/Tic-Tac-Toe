Here's a brief guide on how to set up and run the Tic-Tac-Toe web application locally:

 Prerequisites
Before setting up the application, make sure you have the following installed on your local machine:

- Python 3.x
- pip (Python package installer)
- SQLite (This comes pre-installed with Python)
- Git (optional, if you are cloning the repository)



If you are not using Git, simply download the project files and navigate to the project directory.

 Step 2: Set Up a Virtual Environment
It’s recommended to use a virtual environment to manage your dependencies.

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:
  ```bash
  venv\Scripts\activate
  ```

- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

 Step 3: Install Dependencies
Install the required Python packages using `pip`:

```bash
pip install -r requirements.txt
```

If there is no `requirements.txt` file, manually install the necessary packages:

```bash
pip install flask
```

 Step 4: Initialize the Database
Run the Python script to initialize the SQLite database:

```bash
python app.py
```

This will create a `tictactoe.db` file in the project directory if it doesn't already exist.

 Step 5: Run the Application
Start the Flask development server:

```bash
python app.py
```

By default, the application will run on `http://127.0.0.1:5000/`. Open this URL in your web browser to access the Tic-Tac-Toe game.

 Step 6: Access the Application
- Home Page: `http://127.0.0.1:5000/`
- Leaderboard: If you created a separate HTML file for the leaderboard, access it via: `http://127.0.0.1:5000/leaderboard.html`

 Troubleshooting
- If you encounter a `404` error when trying to load a page, ensure that all files (HTML, CSS, JavaScript) are correctly referenced and located in the `templates` or `static` directories as needed.
- Make sure the Flask server is running before trying to access the application in your browser.

 Step 7: Deactivate the Virtual Environment (Optional)
After you're done, you can deactivate the virtual environment:

```bash
deactivate
```

 Step 8: Stop the Server
To stop the Flask server, simply press `Ctrl + C` in the terminal where the server is running.

By following these steps, you should be able to set up and run the Tic-Tac-Toe web application locally on your machine.
