# crud-Data-Flow-Manager
Developed a user management web app using React, React Router, and JSON Server. Implemented CRUD operations, state management with hooks, and real-time updates. Designed a responsive UI with Bootstrap.




1. Start JSON server (mock backend)
If not installed:


npm install -g json-server
Create a file named db.json (your mock database).

Run the server:

json-server --watch db.json --port 3001
2. Start React app
If not created yet:

npx create-react-app crud-manager
cd crud-manager
If already created:


cd crud-manager
npm start

3. Make sure data fetch URL in React matches
In your React code (e.g., App.js or api.js):


fetch('http://localhost:3001/items')
items should match the key in db.json.

✅ Now both:
http://localhost:3000 → React frontend

http://localhost:5001 → JSON backend (API)

