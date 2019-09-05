# NodeArchitecture
- A progressive Node.js framework for building efficient, reliable and scalable server-side applications. 

Quickstart
-----
- `git clone https://github.com/pranabeshchand/Node_Architecture.git`
- `cd Node_Architecture && npm install && npm start`
- Local url: http://localhost:3000
- Swagger Url for testing api: http://localhost:3000/api


Setup
----- 
- Run `npm install` in the directory with the `package.json` (the root directory).

 
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
