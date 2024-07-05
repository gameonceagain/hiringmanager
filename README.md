Project Setup
Prerequisites
Before setting up the project, ensure you have the following installed on your system:

Node.js (for the frontend)
Python 3.10.9 (for the backend)
Frontend Setup
Install Node.js:

Download and install Node.js from the official website. This will include npm (Node Package Manager), which is needed for managing frontend dependencies.

Navigate to the Frontend Directory:

Open a terminal and change to the directory where the frontend code is located:

bash
Copy code
cd path/to/frontend
Install Dependencies:

Run the following command to install the required npm packages:

bash
Copy code
npm install
Start the Development Server:

Use the following command to start the frontend development server:

bash
Copy code
npm run dev
The frontend application should now be running locally and accessible through your browser.

Backend Setup
Install Python 3.10.9:

Download and install Python 3.10.9 from the official Python website.

Navigate to the Backend Directory:

Open a terminal and change to the directory where the backend code is located:

bash
Copy code
cd path/to/backend
Install Dependencies:

Use the following command to install the required Python packages from requirements.txt:

bash
Copy code
pip install -r requirements.txt
Start the Backend Server:

Run the following command to start the backend server:

bash
Copy code
python manage.py runserver
The backend server should now be running locally and accessible at the specified address (usually http://127.0.0.1:8000/).

Additional Information
Frontend Development: The frontend development server will usually run on port 3000 by default. You can access the application at http://localhost:3000/.

Backend Development: The backend server will usually run on port 8000 by default. You can access the API at http://localhost:8000/.
