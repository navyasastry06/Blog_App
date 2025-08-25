# Blog Application  

A full-stack blog application with a **custom REST API backend** (built using Express.js) and a **frontend server** (EJS + Axios) that consumes the API.  

## Features  

* REST API with CRUD operations:  
  - Fetch all posts  
  - Fetch a single post by ID  
  - Create new posts  
  - Update existing posts  
  - Delete posts  
* Frontend with EJS templates for:  
  - Listing all posts  
  - Creating new posts  
  - Editing existing posts  
* Clean separation of backend (API) and frontend (consumer).  

## Tech Stack  

* **Backend API (index.js):**  
  - Express.js  
  - body-parser  

* **Frontend (server.js):**  
  - Express.js  
  - EJS templates  
  - Axios (for API requests)
 
## Getting Started  

```bash
git clone https://github.com/your-username/blog-app.git
cd blog-app
npm install
node server.js # API will be available at: http://localhost:4000 
node index.js  # //Frontend will be available at: http://localhost:3000
```
