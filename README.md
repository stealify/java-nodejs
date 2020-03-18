# node-graalvm
Node.JS on GraalVM

This project enables Node.js use GraalVM and its Higperformance JavaScript engine. This project is still work in progress and not an officially supported Node.js branch. For more context into this project, please refer to the original PR.

# How it works?
A rebuild of node and native addon modules with truffle-js via GraalVM by Oracle Labs.

# Installing prebuilt.

# Installing vertx Distribution ES4x
```sh
# install
yarn global add es4x-pm # OR npm install -g es4x-pm

# create a project file
es4x init

# create a hello world
cat << EOF
vertx.createHttpServer()
  .requestHandler(req => req.response().end('Hello ES4X world!'))
  .listen(8080);
EOF > index.js

# install dependencies (npm and maven)
yarn # OR npm install

# run it
yarn start # OR npm start
```

# Build

## linux

## macos

## Windows
