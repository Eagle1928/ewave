this project presents top ten movies.
I used react and .net frameworks building this app.
the style mainly consists bootstrap as you asked for.

Client

the main react component is home.js[Containers/Home.js] , this component includes all the low order components(MovieItem/Modal/Popmessage).

* you can find all the javascript methods / ajax requests in home.js

Server

In the server beside the methods there are three const variables:
1) the json file path(the json file is the 'db' of the weba-pp)  "../exam/data/movies.json"
2) Movies categories.
3) the controllers api (MovieController)

two methods are responsible to Get/Post movies, you can the find the method logic in 'MovieController' which is the system api.

* Sessionstoreage is used in GetCategories method.

the system architecture:

CLIENT -- > HomeController --> MovieController(api) --> movies.json

beside this file, the code is full of documentation as well.
