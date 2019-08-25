# NodeArchitecture
- A progressive Node.js framework for building efficient, reliable and scalable server-side applications. 

Quickstart
-----
- `git clone https://github.com/jitendrakumar-sdn/MEAN_Architecture.git`
- `cd MEAN_Architecture && npm install && npm start`
- Local url: http://localhost:3000
- Swagger Url for testing api: http://localhost:3000/api


Setup
-----
- Install [Node](https://docs.npmjs.com/getting-started/installing-node) latest node version.
- Install [NPM](https://www.npmjs.com/get-npm)
- Run `npm install` in the directory with the `package.json` (the root directory).


How to Contribute
-----
- Create a new branch on this repo
- Make your changes
- Commit & push your changes, then open a [pull request] for approval

Hot Tips
-----
- Src folder contain all logic. 
- Conroller: Controllers are responsible for handling incoming requests and returning responses to the client.
- Dto: Dto responsible for data modeling, how data is being send over network.         
- Guard: The authorization logic because specific routes should be available only when the caller has sufficient permissions.(JWT token)
- Interface: To check the typeof veriable.  
- Lib: Common functions, Constants etc.  
- Model: For the Schema definition. 
- Services: To interact with database. 
- app.modules.ts: For injecting global level dependency(model, services, controller)     
- main.ts: Bootstrap the application.  


Deploy
-----
Run the server through pm2 tool 
- pm2 start npm -- start

