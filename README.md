# Quiz App Project - containerised

This repo provides a fully containerised version of the Quiz App, using Docker Compose.

## Setup

1. Fork and clone the repository

2. Install required `npm` dependencies for the front-end
   ```sh
   cd client
   npm install #install dependencies from package.json
   ```
3. Install required `npm` dependencies for the back-end
   ```sh
   cd ../server
   npm install #install dependencies from package.json
   ```
4. Run the containerised application

   ```sh
   cd ..
   docker compose up
   ```

   > **Warning**: The Docker daemon must be running for the above command to be able to execute properly.

---

Upon the successful completion of the above steps, the urls for the client and api will be available at:

- Client-side: http://localhost:8080
- API: http://localhost:3000
