spring-websocket-chat [![build](https://travis-ci.org/daggerok/spring-websocket-chat.svg?branch=master)](https://travis-ci.org/daggerok/spring-websocket-chat)
=====================

this is just a fork with minor sproject build structure improvements...

#### get and running rabbitmq

```shell
$ wget -qO-  http://www.rabbitmq.com/releases/rabbitmq-server/v3.6.0/rabbitmq-server-generic-unix-3.6.0.tar.xz | tar -xvf-
$ rabbitmq_server-3.6.0/sbin/rabbitmq-server
$ gradle npm
$ gradle bootRun
$ open http://localhost:8080
```
#### build app

```shell
gradle build
```

#### running the app

```shell
gradle bootRun
```

#### Chat application using AngularJS and Spring WebSockets (STOMP over WebSockets)

![Spring WebSocket Chat](http://www.sergialmar.com/wp-content/uploads/2014/09/spring-websocket-chat-room.png "Spring WebSocket Chat")

### Features
- Built with Spring Boot
- User login
- Chat message broadcasting and private messages (filtering profanities)
- Presence tracking sending notifications when users join / leave
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- WebSocket security with Spring Security
- Spring Session integration
