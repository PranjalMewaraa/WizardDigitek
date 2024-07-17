# WizardDigitek
Welcome to the E-commerce Gadget Store project repository! This project is built using the P.E.R.N stack (PostgreSQL, Express.js, React, Node.js) and includes a Node.js backend and a React frontend. The project features amazing animated interfaces, a fully functional e-commerce platform, and an in-house management tool for inventory management.
Table of Contents
Features
Project Structure
Installation
Usage
Technologies Used
Contributing
License
Features
Animated Interfaces: Enjoy a visually appealing and engaging user experience with smooth animations.
E-commerce Facilities: Full suite of e-commerce functionalities including product listings, search, filtering, cart management, and checkout process.
Inventory Management Tool: In-house tool for managing inventory, tracking stock levels, and handling orders.
Project Structure
The project is divided into two main folders:

node-backend: Contains the Node.js backend with Express.js and PostgreSQL.
react-frontend: Contains the React frontend application.
arduino
Copy code
ecommerce-gadget-store/
│
├── node-backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── utils/
│   ├── config/
│   ├── .env
│   └── server.js
│
├── react-frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   ├── utils/
│   │   └── App.js
│   ├── .env
│   └── package.json
│
└── README.md
Installation
Prerequisites
Node.js
PostgreSQL
npm or yarn
Backend Setup
Navigate to the node-backend folder:

bash
Copy code
cd node-backend
Install dependencies:

bash
Copy code
npm install
Set up the PostgreSQL database and update the .env file with your database credentials.

Run the backend server:

bash
Copy code
npm start
Frontend Setup
Navigate to the react-frontend folder:

bash
Copy code
cd react-frontend
Install dependencies:

bash
Copy code
npm install
Update the .env file with your API endpoint.

Run the frontend application:

bash
Copy code
npm start
Usage
Navigate to the frontend application in your browser at http://localhost:3000.
Use the e-commerce platform to browse and purchase gadgets.
Use the in-house management tool to manage inventory and orders.
Technologies Used
Frontend: React, React Router, Redux, Styled Components
Backend: Node.js, Express.js, PostgreSQL
Animations: CSS Animations, Framer Motion
Contributing
We welcome contributions! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.
License
This project is licensed under the APACHE License. See the LICENSE file for details.

