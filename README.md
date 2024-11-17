Hello
I am Shameera
Welcome to Coding with Shameera
In this video we are going to create Vehicle Tracking website using MERN
With 
Frontend – React js
Backend – Express js, Node js
Database- MongoDB
Before that make sure you have
Visual Studio Code (VS Code)
MongoDB 
Node js
Installed on your device.
For Complete Coding used in this project, visit my GitHub profile: https://github.com/ShameeraBanuF
Let us start…

Step 1: Create a Folder in your project name and Create 2 folders for Backend and Frontend inside it, Open it in VS code and also open terminal in it.
BACKEND
Step 2: Type cd backend & npm init -y in terminal.
Step 3: Install required packages
	npm install express mongoose body-parser cors nodemon
Step 4: Create 2 files named server.js and seedData.js.
Step 5: Type the codings into it

FRONTEND
Its time to create Frontend with below steps:-
Step 1: In terminal, type
	cd .. [to exit from backend folder]
	cd frontend
	npx create-react-app . [dot refers to current directory]
Step 2: install required packages for frontend
	npm install  axios moment
Step 3: Next delete all files in src folder and public folder
Step 4: go to src folder and create 2 files  App.js & index.js. type the code as shown.
Step 5: Create a folder called components in src directory and create 3 files AddVehicle.js, VehicleList.js, VehicleCard.js inside it. Copy the code as shown.
Step 6: Create a file index.html inside public folder.

EXECUTION
Frontend: npm start
Backend: node server.js

