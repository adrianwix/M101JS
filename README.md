# M101JS FINAL PROJECT

This is the final project of MongoDB University course for NodeJS Developers.

## Setup

- Clone from github
- Install the dependencies `yarn install` or `node install`
- Install bower if you don't have it `npm install -g bower`
- Run `cd static && bower install` to install static folder dependencies
- Make sure you have a mongod running version 3.2.x of MongoDB.
- Import the "item" collection: `mongoimport --drop -d mongomart -c item data/items.json`
- Import the "cart" collection: `mongoimport --drop -d mongomart -c cart data/cart.json`
- Run `yarn start or npm start` to initiate the nodemon server
