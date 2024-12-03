
# Progressive Web Applications (PWA) Challenge: Text Editor
### Description
This project involves creating a browser-based text editor that meets the Progressive Web Application (PWA) standards. The application must support data persistence using multiple techniques to ensure redundancy and functionality even when offline. This includes the use of IndexedDB through the idb package. The application will be deployed on Render following best practices.

### Features
Single-Page Application (SPA): Seamlessly runs in the browser.
Offline Functionality: Data persistence and retrieval without an active internet connection.
IndexedDB Database: Stores and retrieves data using the idb package.
PWA Compliance: Includes service workers, a manifest file, and support for installation as a desktop app.
Next-Gen JavaScript: Supports ES6+ features, bundled with Webpack.
Render Deployment: Full-stack application deployed and accessible online.

### User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use.

Acceptance Criteria
Project Structure:

Application should have a client-server folder structure when opened in an editor.
Start the Application:

Running npm run start from the root directory should start the backend and serve the client.
Webpack Bundling:

JavaScript files should be bundled using Webpack.
Webpack Plugins:

Should generate an HTML file, service worker, and manifest file.
JavaScript Compatibility:

Application should run next-gen JavaScript without errors.
IndexedDB Usage:

A database should be created immediately upon loading.
Content entered in the text editor should be saved and retrieved from IndexedDB.

Install Button:

Allows the application to be installed as a desktop icon.
Service Worker:

Must register a service worker to pre-cache static assets.
Render Deployment:

Application should include proper build scripts for Webpack to deploy on Render.
Getting Started
Prerequisites
Node.js installed on your local machine.
Clone the starter code here (replace with actual link).
Installation
Clone the starter repository.

bash
Copy code
git clone <starter-code-url>
Create your own repository and initialize it with the starter code.

### Install dependencies:

bash
Copy code
npm install
Start the application:

bash
Copy code
npm run start

### Technologies Used
Frontend: HTML, CSS, JavaScript (ES6+)
Backend: Node.js
Database: IndexedDB with idb package
Build Tools: Webpack
Service Worker: Workbox
Hosting: Render

### Deployment
Follow the Render Deployment Guide (replace with actual link) for step-by-step instructions to deploy your application.

### How to Contribute
Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-name).
Open a pull request.

### License
This project is licensed under the MIT License.