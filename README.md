# deploy-node-app-docker
Deploy a Node.JS app with Docker

## Creating an app with Node.JS image

Execute:
`docker run --rm -it -v "$(pwd)/:/usr/src/app" -p 3000:3000 node:15 bash`

In the working directory install the Node.JS dependencies like Express

Add `index.js` file

Build image
`docker run -p 3000:3000 diltheyaislan/hello-node`
