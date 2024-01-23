# webserv
### Web server, simplified clone of NGINX

The goal of the project is to build a C++98 compatible HTTP web server from scratch.
The web server can handle HTTP GET, HEAD, POST, PUT, and DELETE Requests, and can serve static files from a specified root directory or dynamic content using CGI.
It is also able to handle multiple client connections concurrently with the help of select().

###Availability is 99.9% with 100 concurrent client on simple GET request.

