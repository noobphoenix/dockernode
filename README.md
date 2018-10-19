Dockerizing a Node.js web app

Build: 

$ docker build -t <your username>/node-web-app .

Run:
$ docker run -p 49160:8080 -d <your username>/node-web-app
