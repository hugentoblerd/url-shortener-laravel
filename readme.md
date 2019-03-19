# Create your own “URL Shortener" application in PHP (similar to goo.gl)

• A user should be able to place in a long URL and submit.
	[] form -> vue.js
	[] validate -> html5 & Laravel validator

• It should store the long version of the URL, and generate a short URL for the user.
	[] create db and tables
	[] check to see if long URL exists with short URL and use if true
	[] create short url and save record to db
	[] return confirmation and short url

• All subsequent requests to the short URL should send the user to the long URL by some manner of redirect.
	[] check that short url exists
	[] if true, redirect to long url

• You can use whatever frameworks you desire (Laravel, Symfony2, Slim, Codeigniter).

• You can use whatever data storage method you prefer (SQLite, MySQL, flat-file).

• You are free to build up the complexity as you desire (CRUD, analytics, caching), but try not to spend more than 1~3 hours.

Place the result in GitHub and send me the link by Friday, March 15th at 12:00pm(est)/9:00am(mst).
