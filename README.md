**Creating a Flask Web App Using Copilot in VS Code**

Follow these steps to create and run a simple Flask web application using GitHub Copilot in Visual Studio Code:

1. **Generate the Flask App**
   Prompted GitHub Copilot to create a simple Flask web application. It generated the project workspace and added the necessary files to VS Code.

2. **Create a Virtual Environment**
   python -m venv .venv

3. **Activate the Virtual Environment**

   **On Windows:**
  .venv\Scripts\activate.bat
  
   **On macOS/Linux:**
  source .venv/bin/activate

4. **Install Required Packages**  
   pip install -r dev-requirements.txt

5. **Set the Flask App Environment Variable**
   
   **On Windows:**
   set FLASK_APP=app.py
  
   **On macOS/Linux:**
  export FLASK_APP=app.py

6. (Optional) Set the Flask Environment to Development
   
   **On Windows:**
   set FLASK_ENV=development
  
   **On macOS/Linux:**
   export FLASK_ENV=development

7. **Run the Flask App**
   If using app.py, run:
   flask --app app run

   **Or simply:**
   flask run
