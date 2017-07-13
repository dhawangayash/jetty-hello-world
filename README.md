## Description

This is a simple jetty project which shows hello world 
message.

This was based of the tutorial by [mkyong](https://www.mkyong.com/webservices/jax-rs/jersey-hello-world-example/)

### How to run the project

#### Prereqs:
- Jdk 8
- maven


##### Command to start server
```mvn clean install; mvn jetty:run ```

Test the sample server using: ```curl http://localhost:8080/rest/hello/MSG_YOU-WANT-TYPED```

A mini jetty server will start in port `8080`

1. [home-page](http://localhost:8080/)
2. [Get Request](http://localhost:8080/rest/hello/OMG)


