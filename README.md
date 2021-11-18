# golang-mini-server

> Tutorial: [Developing a RESTful API with Go and Gin](https://golang.org/doc/tutorial/web-service-gin)

![image](https://user-images.githubusercontent.com/54107524/142355596-fd29ba4b-c6e0-418f-bee9-b92b04cbb7db.png)


API that provides access to a store selling vintage recordings on vinyl. So you’ll need to provide endpoints through which a client can get and add albums for users.

## Routes

```go
/albums
    GET – Get a list of all albums, returned as JSON.
    POST – Add a new album from request data sent as JSON.

/albums/:id
    GET – Get an album by its ID, returning the album data as JSON.
```

