# Load Balancing

Load balancing is used to efficiently distribute incoming network traffic across multiple servers or resources. It ensures that no single resource becomes overwhelmed, thus improving the reliability, availability, and scalability of the system.

## Scaling strategies

- Vertical scaling (a.k.a scaling up): involves adding more resources, such as CPU, memory, or storage, to a single server to handle increased load.
- Horizontal scaling (a.k.a scaling out): involves adding more machines or instances to distribute the load across multiple servers.

## Load balancing algorithms

- Round robin: requests are distributed evenly across a group of servers in a circular order.
- Least connections: requests are routed to the server with the fewest active connections, aiming to balance the load more evenly.
- IP hash: the client's IP address is used to determine which server receives the request. This ensures that a particular client consistently communicates with the same server, useful for maintaining session state.
- Weighted round robin: assigns a weight to each server based on its capacity, allowing more powerful servers to handle proportionally more requests.
- Least response time: routes traffic to the server with the shortest response time, aiming to optimize performance.
- Adaptive load balancing: utilizes real-time monitoring and analysis of server performance to dynamically adjust routing decisions based on factors like server health, response time, and capacity.

## Load balancer types

- Hardware load balancer: dedicated physical devices optimized for high-performance load balancing.
- Software load balancer: load balancing implemented in software, often as part of application delivery controllers or reverse proxies.
- Cloud load balancer: Load balancing services provided by cloud providers, offering scalability, reliability, and integration with other cloud services.

## External references

- [Horizontal scaling vs vertical scaling: Choosing your strategy](https://www.digitalocean.com/resources/article/horizontal-scaling-vs-vertical-scaling)
- [What Is Load Balancing?](https://www.nginx.com/resources/glossary/load-balancing/)
