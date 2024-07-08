# Webserv: nginx-like web server.

## About
The goal of the project is to build a C++98 compatible HTTP nginx-like web server from scratch.
The web server can handle HTTP GET, HEAD, POST, PUT, and DELETE Requests, and can serve static files from a specified root directory or dynamic content using CGI. It is also able to handle multiple client connections concurrently with the help of select().
<br>

# Usage
```bash
make
./webserv [Config File] ## leave empty to use the default configuration.
```
