# Node.js Server Setup - GitHub Submission

This repository documents the step-by-step process of creating a basic Node.js web server that outputs "Hello Javascript" in the browser, using Node's built-in `http` module.

## Steps

### 1. Check Prerequisites
<img width="643" height="251" alt="image" src="https://github.com/user-attachments/assets/c7aa1d5b-0613-4857-82a9-4dbd70fd76bc" />

**Explanation:** Before starting, I verified that Node.js and npm were installed on my machine by running these version-check commands. Both returned version numbers, confirming Node.js was ready to use.

### 2. Create Project Folder
<img width="602" height="104" alt="image" src="https://github.com/user-attachments/assets/9c565a21-90af-4679-9f70-357a3e0c532b" />

**Explanation:** I created a dedicated folder named "node-server-demo" to keep all project files organized, then navigated into it.

### 3. Initialize the Project
<img width="723" height="424" alt="image" src="https://github.com/user-attachments/assets/a122b90a-97be-4e1b-a004-bb87abeb77b2" />

**Explanation:** I ran `npm init -y` to automatically generate a package.json file, which manages the project's configuration and dependencies.

### 4. Create Server File (server.js)
<img width="921" height="221" alt="image" src="https://github.com/user-attachments/assets/ed9a379b-8b3b-433d-85b8-757e0c133762" />

**Explanation:** I created a file called server.js and wrote the server logic using Node's built-in `http` module. The server listens on port 3000 and responds with an "Hello Javascript" heading.

### 5. Start the Server
**Explanation:** I ran `node server.js` in the terminal, and the success message confirmed the server started correctly without errors.

### 6. Test in Browser
<img width="957" height="299" alt="image" src="https://github.com/user-attachments/assets/98aa06ce-2eba-4902-b207-083d32917f71" />

**Explanation:** I opened a browser and navigated to http://localhost:3000, where the page displayed "Hello Javascript," confirming the server was working as expected.

### 7. Stopping the Server
**Explanation:** Once testing was complete, I returned to the terminal and pressed Ctrl+C to stop the server and close the connection.

## Files
- `server.js` – Server logic
- `package.json` – Project configuration
