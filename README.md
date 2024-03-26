# Flask Login

## Description
This application utilizes Flask to implement sign-up and login functionalities. It allows users to create accounts, log in, and access protected areas within the site.

## Installation

To set up the project on your local machine, follow these steps:

1. **Set up the virtual environment:**
   
   Make sure you have Python and `virtualenv` installed on your system. Then, create a virtual environment and activate it with the following commands:
   
   ```bash
   # Create a virtual environment
   python3 -m venv auth
   
   # Activate the virtual environment (for macOS and Linux)
   source auth/bin/activate
   
   # Activate the virtual environment (for Windows)
   auth\Scripts\activate.bat

2. **Set up you environment variables:**

   Next, set your Flask_APP environment variable which tells Flask how to load the application:

   ```bash
   # For macOS and Linux
   expoer FLASK_APP=project

   # For Windows CMD
   set FLASK_APP=project

   #For Windows PowerShell
   $env:FLASK_APP="project"

3. **Install dependencies:**

   After, we will need to install all the required packages using `pip`:

   ```bash
   pip install -r requirements.txt

4. **Run the Flask Application**:

   Last but not least, you will start the server by executing `flask run`. You can now access the application through a web browser at `http://127.0.0.1:5000/`.
