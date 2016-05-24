This API implement the Rock, Paper, Scissors game.

## Running the server
0) Open the console and start the mongodb using the command './mongod'

1) Open `server.js` and start the app.

2) Alternatively you can launch the app from the Terminal (mongod need to be running):

    $ node server.js

Once the server is running, open the project in the shape of 'https://projectname-username.c9.io/'. and use the different methods available.

 
1) POST -> api/championship/result".
2) GET -> api/championship/top.
3) POST api/championship/new.

In case of problems with mongodb follow this steps for run cloud9
First delete the data folder then run this commands...
1) $ echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
2) ./mongod
https://community.c9.io/t/setting-up-mongodb/1717

I modified the database connection for avoid issues with the free service of cloud9...