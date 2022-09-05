# Reading Assignment 9

>## Review: High-level HTTP
>
>### Step 1: Local Processing
>This where you make a request to the server and the server then searches through the cache of recent requests, OS, router, and DNS. Once it find s what you requested it routes you to that request location.
>
>### Step 2: Resolve an IP
>
>The routing mentioned in step one, has to go through the process of resolving the IP address. It is looking for the network that has a device connected that could return your request via the shortest path to the destination possible.
>
>### Step 3: Establish a TCP Connection
>
>Establishing the TCP connection ensures the delivery of the ordered data. By doingthis it allows the requester to re-request the info and the sender to retransmit any information the receiver didn't acknowledge. 
>
>The sender sends a syn control packet, the server receives it and responds with a syn-ack message, this has a number, and finally the sender responses to the server with an ack message with a sequence number. This sequence number should match the one sent with the syn-ack message. This will verify the reliability of the information sent.
>
>### Step 4: Send an HTTP Request
>
>So now that the TCP and IP address is connected, an HTTP request can be made. To do that we'll need a request line(HTTP method), a host name(port), and the query. Once sent, it follows the same procedure previously described, returning with  the requested info.
>
>### Step 5: Tearing Down and Cleaning Up
>
>At the end of the request process, the requester sends the server a fin message, or packet, and the server responses with an ack message, follwoed by a fin.

>## Things I want to know more about...
>When would it be appropriate to make requests without using additional libraries?