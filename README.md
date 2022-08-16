# Holy-Grail-Redis

## Initialize node application
npm init
npm install

## Set up the Redis Docker container locally. 
docker run -p 6379:6379 --name some-redis -d redis:4.0.1

## Install the Redis npm package.
npm install redis@3.0.2

## Run on localhost:3000
node index.js
After running, you should be able to navigate to localhost:3000


