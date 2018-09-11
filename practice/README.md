Draw a sequence diagram for the following:

A browser makes an HTTP request to `mysite.com`, which returns its index page. It links to a stylesheet, `style.css`, a jQuery script at `maxcdn.com/jquery.js`, and a JavaScript file, `app.js`. On load, the `app.js` script makes an AJAX request to `mysite.com/users/1`. The `mysite.com` server makes a `postgres` request to the database at `mydatabase.com` to get User 1, which it returns to the browser as JSON.

Identify:

* The 5 major actors
* All of the requests and responses, including DNS requests and cache lookups
* The protocols used
* The IP addresses of the requests (feel free to make them up, but they have to be valid IP addresses!)
* The port numbers of the requests
* Any DOM processing
* The data sent and returned

For your practice, there are some included diagrams that are only partially complete, as well as a complete example.
