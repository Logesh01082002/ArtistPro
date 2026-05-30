ArtistPro
Artist pro is a project is used to collabrate with users and artist.

🎶 ArtistPro

ArtistPro is a platform where musicians and people can book, collaborate for events, rent and lend instruments seamlessly.

✨ Features

Community page for updates Chatbot for project insider smart features Instruments renting and lending Event bookings and collaborations More upcoming modules...

📁 Project Structure

ArtistPro/ ├── client/ # Frontend React application └── server/ # Backend Node.js Express application

🔽 Clone the Repository

git clone : https://github.com/Logesh01082002/ArtistPro.git

📦 Extract and Setup

If this project is shared as a zip:

Extract it to your desired directory. Open the folder in VS Code or your preferred IDE.

⚠️ Notes

Ensure Node.js version >= 18 is installed. i am using node js v24

Check your version using: node -v

🚀 Frontend - Client

📂 Location

client folder – built with React.

📦 Packages Used

ajv-keywords@5.1.0 ajv@8.17.1 axios@1.9.0 bootstrap-icons@1.13.1 bootstrap@5.3.3 country-state-city@3.2.1 libphonenumber-js@1.12.7 react-bootstrap@2.10.9 react-dom@19.1.0 react-icons@5.5.0 react-router-dom@7.6.0 react-scripts@5.0.1 react-toastify@11.0.5 react@19.1.0 socket.io-client@4.8.1

🛠️ Install Dependencies

cd client xargs npm install < requirements.txt

(Ensure requirements.txt contains the listed client dependencies.)

🚀 Start Frontend

npm i npm start

The client will run at http://localhost:5000 by default.

🏗️ Build for Production

npm run build

This will generate a build/ folder with production-ready files.

🧪 Running Tests

npm test

Runs tests using React Testing Library.

⚙️ Backend - Server

📂 Location

server folder – built with Node.js and Express.

📦 Packages Used

axios@1.7.9 bcrypt@5.1.1 bcryptjs@3.0.2 cors@2.8.5 dotenv@16.5.0 express@4.21.2 jsonwebtoken@9.0.2 mongoose@8.12.1 multer@1.4.5-lts.2 nodemon@3.1.9 socket.io@4.8.1

🛠️ Install Dependencies

cd server xargs npm install < requirements.txt

(Ensure requirements.txt contains the listed server dependencies.)

🚀 Start Backend

configure index.js before start

npm i npm start

create a cluster mongo db🛠️ MongoDB Setup Guide (Atlas) 📌 1. Create MongoDB Account Go to MongoDB Atlas: 👉 https://cloud.mongodb.com Sign up or log in.

📌 2. Open Your Cluster Dashboard Use your project dashboard: 👉 https://cloud.mongodb.com/v2/6a04c586207c3b588e03f457#/overview

📌 3. Create a Cluster Click Build a Database Choose FREE (Shared Cluster) Select: Provider: AWS / GCP (any) Region: closest to you (e.g., Mumbai / Singapore) Click Create Cluster

📌 4. Create Database User Go to Database Access Click Add New Database User Set: Username: your_username Password: your_password Save user

📌 5. Allow Network Access Go to Network Access Click Add IP Address Choose: Allow Access from Anywhere (0.0.0.0/0) (for development)

📌 6. Get Connection String Go to Clusters Click Connect Select Drivers Copy the connection string:

Example: mongodb+srv://:@cluster0.xxxxx.mongodb.net/?retryWrites=true&w=majority

📌 7. Add to Backend (Node.js)

Install mongoose: npm install mongoose

📌 8. Run Project npm install npm start

📧 Gmail App Password Setup (For Sending Emails) ⚠️ Important

Google does not allow normal Gmail password for Node.js apps anymore. You must use an App Password.

📌 1. Enable 2-Step Verification Go to your Google Account: 👉 https://myaccount.google.com/security Under "Signing in to Google" Enable 2-Step Verification

📌 2. Generate App Password Go to: 👉 https://myaccount.google.com/apppasswords Login if required Select: App: Mail Device: Other (Custom name) → type: Node.js App Click Generate

📌 3. Copy App Password

You will get a 16-character password like: abcd efgh ijkl mnop

👉 Copy it (this is your EMAIL PASSWORD for Node.js)

📌 4. Use in Backend (Node.js)

Install nodemailer: npm install nodemailer

🤖 Agentbase Integration

This project uses Agentbase, a serverless AI agent platform that allows developers to build, deploy, and run production-ready AI agents using a simple API.

👉 Official Website: https://www.agentbase.sh 👉 Documentation: https://docs.agentbase.sh

⚙️ How this project uses Agentbase

In this project, Agentbase is used to:

Create and manage AI-powered agents Automate backend tasks using API calls Handle intelligent workflows and agent execution Enable scalable AI-driven operations without custom infrastructure
