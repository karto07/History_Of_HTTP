# History and Evolution of HTTP
### What is HTTP?
          HTTP known as HyperText Transfer Protocol is an underlying protocol of the world wide web. It is a Simple protocol to transfer the HTML documents.
### What is HyperText?
          It is a text that contains links to other texts or files.
### Who developed HTTP? 
          Developed by Tim Berners-Lee and his team in 1989.
### Version of HTTP?
          1. **HTTP/0.9 – The one-line protocol**
          2. **HTTP/1.0 – Building extensibility**
          3. **HTTP/1.1 – The standardized protocol**
          4. **HTTP/2 – A protocol for greater performance**
### Features in HTTP/0.9 – The one-line protocol?
          - HTTP/0.9 is extremely simple: Requests consist of a single line and start with the only possible method GET followed by the path to the resource.
          
          - Sample Request
              - GET /mypage.html.
              
          - Response consisted the HTML file itself
              - <HTML>
                    A very simple HTML page
                </HTML>
### Features in HTTP/1.0 – Building extensibility?
          - Versioning information is now sent within each request (HTTP/1.0 is appended to the GET line).
          - A status code line is also sent at the beginning of the response, allowing the browser itself to understand the success or failure of the request and to adapt its               behavior in consequence.
          - The notion of HTTP headers has been introduced, both for the requests and the responses, allowing metadata to be transmitted and making the protocol extremely                   flexible and extensible.
          - With the help of the new HTTP headers, the ability to transmit other documents than plain HTML files has been added.
### Features in HTTP/1.1 – The standardized protocol?
          - A connection can be reused, saving the time to reopen it numerous times to display the resources embedded into the single original document retrieved.
          - Pipelining has been added, allowing to send a second request before the answer for the first one is fully transmitted, lowering the latency of the communication.
          - Chunked responses are now also supported.
          - Additional cache control mechanisms have been introduced.
          - Content negotiation, including language, encoding, or type, has been introduced, and allows a client and a server to agree on the most adequate content to exchange.
          - With the help of Host header, the ability to host different domains at the same IP address now allows server colocation.
          - It had more than 15 years of experience, giving various support and new revisions.
### Features in HTTP/2 – A protocol for greater performance?
          - It is a binary protocol rather than text. It can no longer be read and created manually. Despite this hurdle, improved optimization techniques can now be                         implemented.
          - It is a multiplexed protocol. Parallel requests can be handled over the same connection, removing the order and blocking constraints of the HTTP/1.x protocol.
          - It compresses headers. As these are often similar among a set of requests, this removes duplication and overhead of data transmitted.
          - It allows a server to populate data in a client cache, in advance of it being required, through a mechanism called the server push.
