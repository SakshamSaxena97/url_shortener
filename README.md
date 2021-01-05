# url_shortener
This is a Flask-SQLAlchemy url-shortener dockerized app. It takes URL and shortens it, this shortened version of the url redirects to the long url that was initially entered by the client/user.

## How to run it locally?
1) Clone the repo.
2) Run `docker-compose up --build`
3) You can access the app on http://localhost

## App Characteristics
1) Shortening Service - Takes long url as input and generates a random short url, also stores the mapping of short and long url in the datastore.
![alt text]()

2) Redirection Service - When a random short url is generated, the user can click on the link to redirect to the actual long url.
![alt text]()

3) Datastore - SQLAlchemy is used as the database which has the mapping of the short and long url. This mapping can be visited on http://localhost/data/
![alt text]()
