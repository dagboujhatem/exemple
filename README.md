## Quick Start with swagger-faker

```shell
npm init
npm i swagger-faker
```
Then, add the script `{"start": "swagger-faker run"}` to start the server. 

### Create a first fake API: 

1. Step 1 : Create a folder named `data` in the home path. In this folder, we'll create a response file for each API we wish to create. For exemple, create a file named `getUsers.json` like the file in the data folder.  

2. Step 2 : Create a folder named `getUsers.js` in the `middlewares` folder. In this step we'll return the fake JSON response created in the step 1.

## Start the server 

Then you'll see:
1. A `mock-server` folder is generated in your current path, and all mock data is setting in `mock-server/data` folder, you can customize them if needed.
2. A mock server is started in `http://localhost:8082`, you can open your browser and visit one of the mock API by `http://localhost:8082/api/v1/users` (The mock data is setting in: ``)
