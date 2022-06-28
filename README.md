# toDoList-v2  

This is the version 2 of To-Do-List. First version didn't have a database, so the data would be lost
whenever you restart the server.

With this version, now MongoDB database has been added. All the items will be stored in lists so it has
little more functionality than before.

You can create new lists by typing the name at the end of base URL (localhost:3000/Work or localhost:3000/Work etc.) 

This has been achieved by using Express routing parameters. If list already exists, you are able to retrieve the
data seperately from other lists. 

User accounts and authentication would be next for this app.

This app has been built by using Express.js, Node.js, MongoDB, Mongoose, EJS, HTML, CSS and JavaScript.
