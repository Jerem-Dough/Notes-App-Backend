## **Notes App - Backend**

A web-based notes application with user authentication, CRUD functionality, and dark mode. Built using **React**, with a **Node.js/Express** backend and **MongoDB** for data storage.

## **Features**

- Create, read, update, and delete notes
- User authentication with JWT
- Dark mode toggle
- Responsive and user-friendly UI

## **Tech Stack**
- Backend: Node.js, Express.js
- Database: MongoDB, Mongoose
- Authentication: JWT, bcrypt

## **Deployment**

**Steps to Run Locally**
1. Ensure JavaScript, NPM, and Node.js are installed, with PATH variables added accordingly.
2. Clone the repository: git clone https://github.com/Jerem-Dough/Notes-App-Backend.git
3. Navigate to the working directory:
   - Navigate to .env file. Configure 'MONGO_URI' and 'JWT_SECRET' variables. (Not required for local testing)
   - cd your-backend-directory
   - npm install
   - npm start
   - Backend is now running on http://localhost:5000.

## **API Endpoints**
Endpoint	      Method	  Description
/api/signup	    POST	    Register a new user
/api/login	    POST	    Authenticate user and return JWT
/api/notes	    GET	      Fetch all notes (requires auth)
/api/notes/:id	GET	      Fetch a single note (requires auth)
/api/notes	    POST	    Create a new note (requires auth)
/api/notes/:id	PUT	      Update an existing note (requires auth)
/api/notes/:id	DELETE	  Delete a note (requires auth)

  
