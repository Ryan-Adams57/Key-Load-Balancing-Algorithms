# Key-Load-Balancing-Algorithms.

An overview of 8 load balancing algorithms and their uses.

8 Load Balancing Algorithms You Should Know.

1. Round Robin.
Distributes requests evenly across all servers in a rotating sequence.
Best for: Servers with similar capabilities.

2. Least Connections.
Sends requests to the server with the fewest active connections.
Best for: Servers with varying processing speeds.

3. Weighted Round Robin.
Assigns more requests to stronger servers, but still in a round-robin fashion.
Best for: Systems with mixed server capacities.

4. Weighted Least Connections.
Considers both server load and strength when assigning requests.
Best for: Efficiently balancing workloads on varied servers.

5. IP Hash.
Routes requests from the same user to the same server.
Best for: Sessions requiring user persistence (e.g., online shopping).

6. Least Response Time.
Sends requests to the server with the quickest response time.
Best for: Speed-critical applications.

7. Random.
Selects a server randomly for each request.
Best for: Simple load balancing when servers are similar.

8. Least Bandwidth.
Routes requests to the server using the least bandwidth.
Best for: Avoiding network congestion.

Image Credit: DesignGurus.

(https://media.licdn.com/dms/image/v2/D4E10AQE9d6xdCw64CA/image-shrink_1280/image-shrink_1280/0/1730964609457?e=1732125600&v=beta&t=YAcZcqMG6ZN2jEiN3S36Fin46-nB-zwsE3fIjCrywpA)
