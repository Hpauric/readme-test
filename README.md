# readme-test

It’s worth getting to know about the mongo shell.

https://docs.mongodb.com/manual/mongo/

Running shell commands with MongoDB is a really useful way to see what’s in your database. You can review and update your database contents directly from the command line.

Make sure the mongoDB database is running on another terminal before attempting to start the mongo shell.
To start up the database, run `./mongod`

You should see something like this

![](https://github.com/Hpauric/readme-test/blob/master/mongod-cli-screenshot.png)


To access a shell prompt for the above MongoDB open a new terminal and type `mongo` to initialize the shell:

Now the shell is running. I can list the available databases with the command `show databases`
I see the database I’ve been using.

<img src="https://github.com/Hpauric/readme-test/blob/master/show-collections-screenshot.png" alt="test gif" style="mwidth: 50px;"/>




<img src="https://github.com/Hpauric/readme-test/blob/master/show-databases-screenshot.png" alt="test gif" style="mwidth: 50px;"/>

 I can switch to the database with the command:
`use url-shortener-microservice`
I can see the collections in the database with:
`show collections`
<img src="https://github.com/Hpauric/readme-test/blob/master/storedlinks-find-screenshot.png" alt="test gif" style="mwidth: 50px;"/>
I haven’t been too busy - there are just two collections so far.
I can see exactly what’s in the storedLinks collection by running a find() method on it without any arguments. This returns everything:
`db.storedLinks.find()`


https://github.com/Hpauric/readme-test/blob/master/mongod-cli-screenshot.png
