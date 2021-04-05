# person-api

My first API

steps :
npm install js
npm install -g json-server
npm install -g json --registry https://registry.npmjs.org
json-server --watch db.json
npm init (package.json will be created)
npm i (package-lock.json)
npm i json-server (node_module will be created)
npm i json --registry https://registry.npmjs.org、
create a server.js file for backend

deploy:
download heroku for windows
npm install -g heroku --registry https://registry.npmjs.org
heroku create try-person-api
heroku login
heroku create try-person-api-project
git push heroku main
open heroku

API link:
https://try-person-api.herokuapp.com/person
