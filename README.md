
# Blue Rabbit Code Challenge

Fork this repo and create a Full Stack app using languages and frameworks of your choice that
*literally* introduces you to us. Submit your response back to us here in the form of a pull
request or submit it to us privately. Please don't spend more than a couple hours on it. It's ok
if you don't finish, just tackle the requirements in order and take it as far as you can in the time frame.

Include A README with instructions on how to build/run the app. Use the README to let us know
why you chose the technologies you did. Notes on design patterns, challenges, or aspects
of your stack that you find interesting are also appreciated!

### Requirements
1. Create an API with an endpoint or operation that we can call that tells us your name. The shape of the data
and the storage mechanism are up to you. It's ok if it takes no params and returns only your name.
2. Create a minimal frontend that calls your api and displays your name when we run it.
3. Add an API endpoint or operation that takes a name and stores it.
4. Add an input to the frontend that we can use to submit a name to the endpoint or operation you just created.
5. Add an input to the frontend that lets us upload an image avatar and submit it to your API.


## Available Scripts

In the project directory, you can run:

### `npm install`

Install all the dependencies

### `npm run server`

Runs the api in the development mode.\
Able to get a name list from endpoint [http://localhost:3001/api/name](http://localhost:3001/api/name) and post a new name to the same endpoint with param body

key  | Type
------------- | -------------
firstName  | String
lastName  | String


### `npm run seed`

Runs the seed.js file to insert my name to database

## For Upload Image

Make a copy of `.env.template` file to `.env` and replace corresponding personal cloudinary name and preset name







