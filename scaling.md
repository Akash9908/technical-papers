# Scaling

## Introduction

Scaling is the process of increasing a system's ability to handle more number of users, requests, and workloads without affecting its performance. When an application becomes popular, the number of incoming requests increases. A single server may not have enough processing capacity to handle all these requests. This can lead to slow response times, server overload, and sometimes application failures.
To overcome these challenges, organizations use different scaling techniques. The two major approaches are vertical scaling and horizontal scaling. Load balancing is another important technique that helps distribute incoming traffic across multiple servers and improves the performance.

## Vertical Scaling

Vertical scaling is also known as scaling up, means increasing the hardware resources of an existing server. Instead of adding new servers, we upgrade the current server by providing more CPU power, RAM, or storage capacity.

## Horizontal Scaling

Horizontal scaling, also known as scaling out, means increasing the capacity of an application by adding more servers or instances instead of upgrading an existing server.

## Load Balancing

Load balancing is the process of moving incoming network traffic across multiple servers. A load balancer acts as an entry point between clients and application servers. Instead of sending every request to a single server, it moves requests among available servers to prevent any one server from becoming overloaded.
For example, consider an application running on three servers. When users send requests, the load balancer decides which server should process each request. This improves resource utilization, reduces the possibility of server overload, and helps maintain application availability.

### Common Load Balancing Algorithms

* **Round Robin:** Distributes incoming requests across servers in a rotating order. For example, the first request goes to Server 1, the second to Server 2, and the third to Server 3.
* **Least Connections:** Sends new requests to the server with the fewest active connections. This is useful when requests require different amounts of processing time.

### Benefits of Load Balancing

* Moves traffic efficiently across multiple servers.
* Prevents individual servers from becoming overloaded.
* Helps applications handle a large number of users.

## Conclusion

Scaling is important for building reliable and high-performance applications. Vertical scaling increases the resources of an existing server, whereas horizontal scaling increases capacity by adding more servers. Load balancing uses horizontal scaling by moving incoming traffic efficiently.

## References

* Gate Smashers- Horizontal vs Vertical Scaling | System Design- https://www.youtube.com/watch?v=rwTTymOAHTU 
* telusko- Load Balancing | Microservice- https://www.youtube.com/watch?v=y0RLt73vyX8
* GeeksforGeeks- Load Balancing- https://www.geeksforgeeks.org/system-design/what-is-load-balancer-system-design/
