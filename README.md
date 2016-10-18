# Project: rest_proxy
Node.js based REST proxy used for JS UI developments to avoid CORS problems

#Installation
git clone https://github.com/dunamis1974/rest_proxy.git
cd rest_proxy
npm install

#Configuration
Use conf.js to configure data you need. Note that the static content is not required t be in the ./public folder. You can put it anywhere on the filesystem as long as your user can access it.

#Start using it
node .

Server starts by default on port 3000 so if you point your browser to the http://localhost:3000/your-app and you are good to go.
