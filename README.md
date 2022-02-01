# HTTP Methods

#### GET

It is the request method used to get - list data.
```
http://api.example.com/users
http://api.example.com/users/1
```
#### POST

It is used to send data to a specific resource.
```
http://api.example.com/users
```

#### PUT

It is the method used to replace all the data in a particular source.
```
http://api.example.com/users/1
```
```
{ “name": "Gurcan", "age": 40}

```

#### PATCH

It is a method used to modify some of the data in a particular source.
```
http://api.example.com/users/1
```
```
{ "name": "Gurcan"}
```

#### DELETE 

It is the method used to delete data from a particular source.
```
http://api.example.com/users/1
```

#### Endpoint 

It is the meeting point determined for the request sent and the response given using the REST API.

It consists of Root(Base) /Path structure, names are used, the verb is specified with the corresponding HTTP method. It is specified by the documentation.
```
https://jsonplaceholder.typicode.com /posts
```

Usually (:) is used for the changed value.
```
https://jsonplaceholder.typicode.com/posts/1 => /posts/:id veya /posts/{{id}}
https://jsonplaceholder.typicode.com/posts/1/comments
```

(?) is used for query parameters.

Actually, query parameters are not part of the REST structure, but we often come across it in query addresses.

```
http://example.com/articles?sort=author&date=published
```

[docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
