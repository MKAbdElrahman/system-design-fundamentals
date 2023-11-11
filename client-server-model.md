# Client Server Model


The client-server model is a fundamental architecture for networked communication, and understanding the roles of clients, servers, DNS, IP addresses, ports, and protocols is crucial for comprehending how data is transmitted over the internet.

1. **Client-Server Model:**
   - **Client:** A machine (or software) that initiates requests to the server.
   - **Server:** A machine (or software) that listens for client requests and provides responses.

2. **Domain Name System (DNS) Query:**
   - When a user types a human-readable domain name like "www.google.com" into a browser, the browser needs to find the corresponding IP address of the server hosting that website.
   - The browser initiates a DNS query to a DNS server to obtain the IP address associated with the given domain.

3. **IP Address:**
   - An IP address is a unique numerical label assigned to each device connected to a computer network. In the context of web communication, it identifies the server hosting the website.

4. **Ports:**
   - Ports are used to differentiate between different services running on the same machine. They help direct incoming data to the appropriate application or process.
   - Servers listen for requests on specific ports.

5. **HTTP and HTTPS Protocols:**
   - **HTTP (Hypertext Transfer Protocol):** A protocol used for transmitting hypermedia (like web pages) over the internet. The standard port for HTTP is 80.
   - **HTTPS (Hypertext Transfer Protocol Secure):** An extension of HTTP with added security using encryption. The standard port for HTTPS is 443.

6. **Communication Process:**
   - After obtaining the IP address, the browser sends an HTTP or HTTPS request to the server's IP address.
   - The server processes the request and sends back an appropriate response to the client.

