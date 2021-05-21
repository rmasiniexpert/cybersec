# cybersec

## How HTTP works:
All HTTP transactions follow the same general format. Each client request and server response has three parts: the request or response line, a header section and the entity body.

The client initiates a transaction as follows:

The client contacts the server and sends a document request. A GET request can have url parameters and those parameters will be available in the web access logs.

GET /index.html?param=value HTTP/1.0

Next, the client sends optional header information to inform the server of its configuration and the document formats it will accept.

User-Agent: Mozilla/4.06 Accept: image/gif,image/jpeg, /

In a POST request, the user supplied data will follow the optional headers and is not part of the contained within the POST URL.
