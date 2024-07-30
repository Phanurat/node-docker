# Node-Docker

### Initialize Nodejs

```sh
npm init -y
```

### install express

```sh
npm install express
```

### Build the docker image

```sh
docker build -t my-node-app .
```

### Run Docker Container

```sh
docker run -p 3000:3000 my-node-app
```

```sh
my-node-app/
│   app.js
│   package.json
│   package-lock.json
│   Dockerfile
│   .dockerignore
└───node_modules/
```
