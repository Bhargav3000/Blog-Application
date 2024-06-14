#Blog Web Application
This is a blog web application built using EJS (Embedded JavaScript) and JavaScript for the backend with REST API calls. Follow the steps below to set up and run the application on your local machine.

#Prerequisites
Make sure you have the following installed on your system:
Node.js (v14.x or later)
npm (Node package manager)

#Installation
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:
Navigate to the project directory and install the required dependencies using npm:
npm install

Start the server:
npm start
Open the application in your browser:
Visit http://localhost:3000 in your web browser to view and interact with the blog application.

#Project Structure
Here's an overview of the project structure:
your-repo-name/
├── public/
│   ├── css/
│   ├── js/
│   └── images/
├── routes/
│   ├── index.js
│   └── api.js
├── views/
│   ├── partials/
│   ├── index.ejs
│   └── post.ejs
├── .env
├── app.js
├── package.json
└── README.md
public/: Contains static files like CSS, JavaScript, and images.
routes/: Defines the routes for the application.
views/: Contains the EJS templates for rendering HTML.
app.js: The main application file where the server is set up.
.env: Environment variables (not included in the repository for security reasons).
package.json: Lists dependencies and scripts for the application.
#Dependencies
The main dependencies used in this project are:
express
ejs
body-parser
REST API calls
