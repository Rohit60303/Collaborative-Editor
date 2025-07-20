# Collaborative-Editor

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BHUPATHIRAJU SURYA SRI ROHIT VARMA

*INTERN ID*: CT08DF1032

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

# Project Description 

So here comes my 3rd task, A real-time collaborative document editor developed with **React**, **Tailwind CSS**, **Node.js**, **Express**, **Socket.IO**, and **MongoDB**. This project was worked on as an internship project submission, showcasing full-stack web development and real-time communication ability.

The **Collaborative Editor** enables multiple users to edit a single document in real-time. It features a smooth editing experience with real-time updates, collaborative presence indicatiors, and MongoDB-based persistent document storage.

*The app has two parts* :

 `Frontend`: Developed with React.js and Tailwind CSS

 `Backend`: Developed with Express.js and Socket.IO, interfaced with MongoDB

*Folder Structure* :

-  The root folder (collab editor) has two folders namely **Frontend** & **Backend**

-  The Frontend folder consists of src folder and other files like tailwind.config, postcss.config, etc.. and the src folder consists of files like app.css, app.js, index.css, index.js, collaborative editor.js, etc,.

-  The Backend folder consists of model folder, node modules, .env, package.json, package-lock.json, server.js and the models folder consists of Document.js file.

*Features* :

-  Multi-user real-time text collaboration, multiple users can edit the same document a time.

-  Persistent document storage using MongoDB.

- Automatic document ID generation.
  
- Active user tracking and cursor synchronization.

-  Responsive new-age UI with Tailwind CSS.

# Technologies Used 

 *Backend* :
 
`Node.js`

`Express.js`

`Socket.IO`

`MongoDB` with Mongoose

`dotenv` for environment setup

`CORS` for cross-origin requests

*Frontend* :

`React.js`
  
`Tailwind CSS`

`socket.io-client`

`Functional components with hooks`

# Installation Instructions 

 Clone the repository

    bash
    
    git clone https://github.com/your-username/collaborative-editor.git
    cd collaborative-editor
    
Backend Setup :

    bash
    
    cd backend
    npm install

Create a .env file:

    env
    
    MONGODB_URI=your_mongodb_connection_string
    PORT=5000
    
Start the backend:

    bash

    npm run dev
    
The backend will be running on `http://localhost:5000`

Frontend Setup :

    bash

    cd ./frontend
    npm install
    npm start
    
The frontend will be running on `http://localhost:3000`

NOTE : Ensure both frontend and backend are running for complete functionality.

# How It Works 

This is a collaborative editor that utilizes a combination of React, Socket.IO, and MongoDB to facilitate real-time collaboration among users.

1. User opens the app : 

      The user makes a request to the React frontend at http://localhost:3000, which establishes a connection to the backend server via WebSocket.

2. User joins or creates a document :

      When a user provides a document ID, the backend queries if the document exists in MongoDB. If it does not exist, it gets created.

3. Real-time connection using Socket.IO :

      The backend connects all users to a "room" through the document ID using Socket.IO. When a user types, an update is broadcast to others in real-time.

4. Live collaboration :

      Changes to text are emitted through text-operation events. The server maintains the document content and broadcasts the changes to all users within the same room.

5. Auto-save to MongoDB :

      The server stores document changes and version numbers in MongoDB. The collaborators are also tracked and stored.

6. Everyone remains in sync :

      Other users get up-to-date content and keep working without issues, providing smooth, synchronized editing.

*This project helped me learn* :

- Setting up full-stack applications with frontend and backend separation.

- Handling real-time communication using WebSockets

- Designing REST + WebSocket APIs using MongoDB

- Using Tailwind CSS for responsive UI

- Making modular and reusable components in React

*conclusion* :

This project showcases my capability to develop a complete full-stack real-time application from the ground up. By combining technologies such as React, Tailwind CSS, Express, Socket.IO, and MongoDB, I was able to design a smooth collaborative document editor with live multi-user editing support, persistence, and effective communication between frontend and backend.

# OUTPUT

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/58afa93f-b3c7-4590-b4d4-ff92f3930fcf" />

----------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/8f13189c-ece5-4db9-829c-3c822cc3844d" />

-----------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/505c21bd-9a6c-4d8b-b5b2-13e000811127" />

-----------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/d5ac43b4-4a84-4b61-963c-196b84a125df" />

-----------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/d5ac43b4-4a84-4b61-963c-196b84a125df" />

------------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/956fa575-7c29-4f4c-8537-c7239ee4aabb" />

-------------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/aa6b3be6-654e-4371-8e8a-6ad4d61f192a" />

-------------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/8871ab15-b432-4ef9-9a3b-3fe891d81870" />

-------------------------------------------------------------------------------------------------------------------------------------------

<img width="1920" height="1140" alt="Image" src="https://github.com/user-attachments/assets/99281499-3926-469b-9d22-16401d6d72a4" />
