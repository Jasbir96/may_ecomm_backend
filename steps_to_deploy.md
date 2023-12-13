## preparing your backend for deployment
*  Add both the options : process.env.PORT || PORT,
* create .gitgnore file and add -> node_modules .env
* create  a github repo 
* Push all the code
## steps to deploy on render
* Signup to render  
* connect your github 
* go to your dashboard 
* select web service
* build and deploy using git and github
* connect the github repo
* Deployment page 
    * Enter name
    * verify if your start command is correct or not -> package.json
    * Add all the env variables except your PORT
    * deploy