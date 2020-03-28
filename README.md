# springboot-Microservice

A skeleton project which has following microservice components 
- springbootServiceDiscovery: eureka server
- accountProducerService: rest producer service
- accountWebClient: rest consumer
- gateway: zuul proxy for accountsWebClient

To run the microservice setup:

Start the individual components in the order mentioned above.
To access eureka: http://localhost:1111/
To access web client via zuul gateway proxy: http://localhost:8080/accounts-web