1. cmd/app - entry point of application/service
2. config - consists whole config and handling specific config options (common options handles in internal/config-internal)
3. handlers -  define handlers (in example there are handlers for http, socket and websocket)
4. internal - main framework folder
    app - main application functionality (registering config,storage,handlers and etc)
    config-internal - common config options (server settings and etx)
    http - boilerplate code for http server
    socket - the same as above for socket
    websocket - the same for websocket
5. pkg - common code (start servers) 
6. storage - get instance of storage client we will work with
7. tasks - main busyness logic
8. types - models we will use in our microservice
