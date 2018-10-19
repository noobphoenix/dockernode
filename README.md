Dockerizing a Node.js Hello World

Build: 

$ docker build -t <your username>/node-web-app .

Run:
$ docker run -p 49160:8080 -d <your username>/node-web-app
