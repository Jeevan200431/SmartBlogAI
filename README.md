# SmartBlogAI

<h5>SmartBlogAI is a blogging platform where users can **read blogs and post comments**, while admins can **add, remove, and manage blogs and comments**.  
The project is built using a **MERN-like architecture** (React + Node.js/Express + MongoDB) and optimized for deployment on **Vercel** and **GitHub**.</h5>
---  
## 🔗 Live Demo  
Try it out here 👉 [SmartBlogAI Live] (https://smart-blog-ai.vercel.app/)  

## Features    
### Users  
- Read blogs  
- Comment on blogs  

### Admin
-  Add new blogs  
-  Remove blogs  
-  Manage blog content  
-  Manage and moderate comments  

---  

##  Project Structure  
AIBlog/  
│── client/ # Frontend (React + vite)  
│ ├── src/   
│ ├── public/  
│ ├── .env  
│ └── package.json  
│  
│── server/ # Backend (Node.js + Express + MongoDB)  
│ ├── configs/  
│ ├── controllers/  
│ ├── middleware/  
│ ├── models/  
│ ├── routes/  
│ ├── server.js  
│ └── .env  
│  
├── .gitignore  
├── README.md  
├── vercel.json  
└── package.json  

---

## 🛠 Tech Stack
- **Frontend**: React + Vite + TailwindCSS  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Tokens)  
- **Deployment**: Vercel / GitHub   

---  

## ⚙ Installation & Setup  

### 1. Clone the repo  
```bash
git clone https://github.com/Jeevan200431/SmartBlogAI.git
cd SmartBlogAI
```
### 2. Setup backend (server)  
```
cd server
npm install
```
### Create a .env file inside server/:  
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
Start the server  
```  
npm start
```
### 3. Setup frontend (client)  
```
cd ../client
npm install
```

### Create a .env file inside client/:  
```
VITE_API_URL=http://localhost:5000  
```

Run the client:  
```
npm run dev  
```
## Deployment  
- Frontend is deployed via Vercel  
- Backend can be deployed on Vercel  

## Environment Variables   
- Make sure to create .env files in both client and server.  
- For security, these are ignored in .gitignore.  


## Author  
Jeevan MR  
GitHub: Jeevan200431  
 
