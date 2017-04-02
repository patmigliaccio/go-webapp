# Go Web Application

An application built from the ground up in the [Go](https://golang.org/) programming language using microservices, a [Redis](https://redis.io/) data store, and a [Vue.js](https://vuejs.org/) front-end. A work in progress that will eventually become a full featured web app.

## Building and Starting

Navigate to the `client` directory and run the following:

``` bash
$ npm run build
```

Then navigate to the `server` directory and run the following:

``` bash
$ go build
$ ./server
```

Finally open `localhost:8080` in a web browser. 

`Ctrl+C` to terminate the server.