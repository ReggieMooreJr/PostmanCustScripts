# PostmanCustScripts
This is a Proof of Concept to see if we can create modular Postman Code 
# GitHub Repository: Postman-Request-Scripts

## Overview
This repository contains scripts for automating Postman requests using JavaScript (Node.js). Follow the steps below to set up and execute the requests.

## Instructions

### 1. Cloning the Repository
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/your-username/Postman-Request-Scripts.git
```

### 2. Importing Postman Collection
- Open Postman and import your collection (`your-collection.json`) into Postman.
- Ensure that your collection contains requests for signing in, posting a VIN, and retrieving location and VIN data.

### 3. Generating Code Snippets
- In Postman, click on the "Code" button to generate the code snippet for each request.
- Select JavaScript (Node.js) as the language.

### 4. Creating JavaScript Files
- Copy the generated code for each request.
- Create separate JavaScript files in the local repository for each request (e.g., `signInRequest.js`, `postVINRequest.js`, `getLocationRequest.js`).

### 5. Modifying Request Files
- In each JavaScript file, modify the code to include the base URL (`https://5zk1z.wiremockapi.cloud/`) and any necessary request parameters.

### 6. Creating Main JavaScript File
- Create a main JavaScript file (e.g., `main.js`) in your local repository.

### 7. Importing Request Files
- In the main JavaScript file, use the `require` function to import the necessary request files.

### 8. Writing Custom Scripts
- Write custom scripts in the main JavaScript file to execute the requests and handle the response data.
- Utilize the `pm.sendRequest` function to send requests and access the response data.

### 9. Executing Requests
- Execute the main JavaScript file using Node.js to run the Postman requests and view the results.

## Execution
Run the following command in your terminal to execute the main JavaScript file:
```bash
node main.js
```

Feel free to customize and extend the scripts based on your specific requirements. Happy coding!
