# Microproject 2 – Node.js + Express + MongoDB (CREATE API)

# Team Members
- Neel Manishkumar Patel
- Mahi Dharmeshkumar Patel
- Pratham Ghanshyambhai Patel

# This is a simple backend project built using Node.js, Express, and MongoDB. The goal of this microproject was to implement the **CREATE** operation from the CRUD functionality using the MEN (MongoDB, Express, Node.js) stack.

## What We Did

- Set up a Node.js project using Express framework.
- Connected the project to a MongoDB Atlas cloud database using Mongoose.
- Created a schema with 5 fields using Mongoose (with validation and default values).
- Built two API endpoints:
  - `POST /api/create` → to create a new document.
  - `GET /api/` → to view all documents.
- Used Postman to test the `POST` route and successfully add data to MongoDB.
- Followed the proper MEN folder structure (models, controllers, routes, config).
- Used ES module syntax (`import`/`export`) and stored sensitive data in a `.env` file.

## How to Run

1. Clone the repo and run:
2. From root directory
   ```bash
   npx nodemon src/app.js

# Test api
1. Go to browser --> Connect to or search localhost:3000/api
2. open postman --> Connect to or search localhost:3000/api/create
   use post method --> select body --> raw --> JSON Type --> and write json file for field 1,2,4,5 using key-value pairs --> then press send.
3. use get method to check that api is working properly and connected to MongoDB --> Use link localhost:3000/api/ and the status should be "OK" and the JSON file is shown below.
4. also can check on mongodb compass in connection-->models after connecting to DB.
   
