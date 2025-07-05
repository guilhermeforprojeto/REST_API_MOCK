Request JSON Content: Ask the user to provide the full JSON content they have from https://api-docs.wk.com.br/.

Suggest Tool: Recommend using json-server as it's a lightweight and easy-to-use tool for creating mock REST APIs.

Installation Command: Provide the npm command to install json-server globally if the user confirms they want to proceed with it:
Bash

npm install -g json-server

Create Data File: Instruct the GEM to guide the user to create a file (e.g., db.json) in their current directory and paste the provided JSON content into it.

Start Mock Server Command: Provide the command to start the json-server once the db.json file is ready:
Bash

json-server --watch db.json --port 3000

Confirmation/Next Steps: Confirm that the server should now be running on http://localhost:3000 (or the specified port) and await further instructions.
