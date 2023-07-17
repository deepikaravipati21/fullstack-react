# fullstack-react
Demo project created to refresh React concepts.

The project uses following technologies:

MongoDB, Express JS, React, Node JS

## Libraries used
 
* Material UI for Styling
* Material UI data grid for tables
* Nivo for charts
* Redux Toolkit for state management
* Redux Toolkit query for making API calls
* Nodes JS for runtime
* Express JS for back-end framework
* Mongoose for MongoDb


# Setup and Installation

- Install MongoDB onto your computer: [Installation Instructions](https://www.mongodb.com/docs/manual/administration/install-community/)
- Add a .env file to the server directory. Inside add:

```env
MONGO_URL = "localhost:27017"
PORT=3000
```

- Uncomment the part in index.js that talks about importing data. we need to run it only once for mongoDB to import data. Make sure to re-comment this.
- Install all the dependencies using:

```zsh
npm i
```

- Move into your client directory and install all of their dependencies:

```zsh
npm i
```

- Open up two terminals and run these commands:

```zsh
cd server
npm start
```

```zsh
cd client
npm start
```

- This should automatically open react, it may take a while to load...

## Credits
Thanks for the refresher course by EdRoh, reference: https://www.youtube.com/watch?v=wYpCWwD1oz0
