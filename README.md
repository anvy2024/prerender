# Getting Started with [Fastify-CLI](https://www.npmjs.com/package/fastify-cli)
This project was bootstrapped with Fastify-CLI.

## Available Scripts

In the project directory, you can run:

### `npm run dev`

To start the app in dev mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm start`

For production mode

### `npm run test`

Run the test cases.

## Learn More

To learn Fastify, check out the [Fastify documentation](https://fastify.dev/docs/latest/).

## Build and publish the docker image
docker buildx build --platform linux/amd64,linux/arm64 -t 339713009221.dkr.ecr.ca-central-1.amazonaws.com/prerender:latest --push .

docker build -t 339713009221.dkr.ecr.ca-central-1.amazonaws.com/prerender:latest --push .