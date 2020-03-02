# Read: 13 Summary 
## The Past, Present, and Future of Local Storage for Web Applications

> Persistent local storage is one of the areas where native client applications have held an advantage over web applications.

> If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

***Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data***
***userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure***
* In 2007, Google launched Gears and can store unlimited amounts of data per domain in SQL database tables.
> HTML5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser. 

***Unlike cookies, this data is never transmitted to the remote web server***
* From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.
* you can treat the localStorage object as an associative array. Instead of using the` getItem()` and `setItem()` methods, you can simply use square brackets.
* The storage event is supported everywhere the localStorage object is supported,
* If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)
* The storage event is not cancelable. From within the handle_storage callback function, there is no way to stop the change from occurring.
* with HTML5 Storage, you can save the progress locally, within the browser itself.
* Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it
***`“SQL”` is more of a marketing term than a hard-and-fast standard***
* there is no database server in the world that conforms to that and only that specification. There’s Oracle’s SQL, Microsoft’s SQL, MySQL’s SQL, PostgreSQL’s SQL, and SQLite’s SQL
* The Indexed Database API exposes what’s called an object store. An object store shares many concepts with a SQL database.
