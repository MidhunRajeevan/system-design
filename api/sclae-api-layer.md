# Scaling Of API Layer

## Role of an API Layer
1. Request Routing :The API Gateway routes incoming client requests to the appropriate backend services or microservices based on the API path
2. Security and Authentication:The API Gateway enforces security protocols like authentication, authorization, and encryption 
3. Rate limit and Throuttling
4. Cashing
5. Request Transerfomation 
6. Protocol transition
7. Centralized Management or Orchastrating the API

## Key concepts on API Scaling

1. Latency 
    
    The latency is the time delay between a client sends a request to API and when it receives a response.It is the the time taken for a request to travel from client to server and be processed and travel back from server to client.
    
    - Network Latency :Time take for a request to travel from client to server.The Round trip time(RTT) the time take for a request to travel to the server and return back to the client.
    - Processing Latency : The time server takes to process the request
    - Response latency : The time it takes for the response to travel from the server t cleint.


    High latency means user experience delay in receiving the response .

2. ThroughPut 
    
    Throughput referes to the number of request an API can handle per second.It represent the howmany data or howmany request a system can handle.Throughput measured in request per second.

3. Scalability 

    Scalability referes to the ability of the api layer to efficiently handle increased load by adding resources.

    - Horizontal scaling 
    - Vertical scaling 


## API Scaling Stratergies 

1. Horizontal and Vertical Scaling 
2. Load Balancing 

    - reverse proxy sitting infront of the backend applications
    - DNS load balancing : 
    
        DNS load balancing is a technique that distributes traffic accross multiple servers by leveraging the Domain name system.It maps the single domain name to multiple IP address , allowing the DNS server to direct the cleint to different servers.

3. Rate Limit 

    The number of request a client can make to an API with in predefined period of time 

4. Asynchronous Processing 

    Off loading the time consuming or resource intensive task to a seperate process at the backend.The message queues play a crucial role in fecilitating the asychrounous communication.They act as an intermediaries , allowing the component to send and receive the message asynchronously.

5. Microservice Application


        



