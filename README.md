## Spring boot communication test application

Provides simple feedback for testing communication between environments.

# run
```
    mvn spring-boot:run
```

# endpoint
```
    http://[server]:[port]/commtest/ping
```

# response

```
    { "pong":1 }
```
# notes: 

- Current port is 8080. Change at application.properties if required.

