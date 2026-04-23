npm init -y //Initialize JSON file
npm install mongoose cors dotenv express
npm install nodemon --save-dev
Change scripts -> 
"scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  }
  or
 "scripts": {
    "dev": "nodemon server.js"
  }
  create .env file add MONGO_URI = and PORT =
  next frontend :
  npm create vite@latest .
  ctrl + , -> quick suggestions -> suggest:Selection Mode -> always
