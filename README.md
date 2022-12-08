# fruits-api

Mockup API used on the "Fruit at your door" project

To create the json server:

1. npm install -g json --registry https://registry.npmjs.org
2. json-server --watch db.json

To deploy:

1. npm install gh-pages --save-dev
2. add to "scripts":
   "predeploy" : "npm run build",
   "deploy" : "gh-pages -d build"
