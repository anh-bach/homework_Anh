# Homeworks From SymAnalytics

## 1. REST API

Requirement: Explain in your own word what is REST API and how does it work. What are differences between GET and POST verb.

`Answer:`

```
1.a What is REST API and how does it work?
REST stands for Representational State Transfer.
API stands for Application Programming Interface.

As I understand, it is the contract or the guidelines in which,
how the clients can communicate with the web service to retrieve some
pieces of information or perform an action. Client -> REST APIs -> Database and vice versa.

A client can communicate with database via REST APIs by using HTTP requests.
The client can send HTTP requests by using these following typical HTTP verbs:
- GET: Read from database.
- PUT: Update/Replace row in database.
- PATCH: Update/Modify row in database.
- POST: Create new record in database.
- DELETE: Delete from database.

How does it work?
A client send a HTTP request to a specific endpoint and wait for a response.
(Ex: a get request to retrieve a specific product information.)
REST API receive the request from client and does whatever it is designed according to the request.
REST API queries the database for what it needs.
REST API has what it needs, it send back a response to the client in JSON or XML format.
The request - reponse cycle ends here. Every cycle is seperated and no data is stored
between the cycles.

```

```
1.b What are differences between GET and POST verb?

GET:
 - is used to request data.
 - supports only string data type.
 - parameters saved in browser history.
 - has length restriction (255 characters long).
 - can be bookmarked.
 - can be cached.

POST:
 - is used to send data to create or update a record.
 - supports different data types such as string, numeric, binary, etc.
 - parameters not saved in browser history.
 - Has no restriction on data length.
 - cannot be bookmarked.
 - cannot be cached.

```

## 2. User List

Requirement: Make a simple user list with usernames as sidebar and user infomation as card.

Technologies used: `React and CSS3`.

### Screenshot

[![Screenshot-2021-10-28-at-13-57-24-User-List-Exercise.png](https://i.postimg.cc/PJ17YTZb/Screenshot-2021-10-28-at-13-57-24-User-List-Exercise.png)](https://postimg.cc/5QNpMcsj)

### Deploy

The simple app is deployed on Heroku.

Please check it out at: [https://user-list-symanalytics.herokuapp.com/]

## 3. Custom Element

Requirement: A simple greeter web component with custom Element.

### Screenshot

[![Screenshot-2021-10-28-at-19-06-36-Document.png](https://i.postimg.cc/qq9PXffx/Screenshot-2021-10-28-at-19-06-36-Document.png)](https://postimg.cc/WqwYTH1d)

### Deploy

This simple app is deployed on GitHub.

Please check it out at: [https://iamanh1990.github.io/customElement-Symanalytics/]
