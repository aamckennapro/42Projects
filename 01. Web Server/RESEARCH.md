# RESEARCH.MD

Boy howdy this is my research document for Project 1, the Web Server. I've never built a web server, but I sure have been interested in them.

NGINX was recommended for inspiration, which is written in C, and here's that [source code](https://github.com/nginx/nginx). nginx is written in a way such that it works through the command prompt, or terminal. This is incredibly helpful as I have no need to create a GUI.

[What is HTTP/2?](https://kinsta.com/learn/what-is-http2/)

[Python HTTP/1.1 Server](https://bhch.github.io/posts/2017/11/writing-an-http-server-from-scratch/)

[Building a Multi-Threaded Server in Rust](https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html)

[A Multi-Threaded Web Server](https://www.cs.carleton.edu/faculty/dmusican/cs348/webserver.html)

[An example repo of a Multi-Threaded Server in C](https://github.com/ozgurhepsag/Multi-threaded-HTTP-Server)

[RFC 2616 - An in-depth overview of HTTP 1.1](https://tools.ietf.org/html/rfc2616)

[RFC 7540 - An in-depth overview of HTTP 2.0](https://tools.ietf.org/html/rfc7540)

[Simple HTTP server sample](http://www.jbox.dk/sanos/webserver.htm)

This is all that I've found so far, and it seems that I need to go the route of a multi-threaded web server. 

Likely situation: single file or just two files, one that deals with requests and one that deals with everything else. Multi-threaded server that works through the command prompt. Can host HTML files at the very least. Lightweight and efficient. Can accept up to an undisclosed amount of requests, but I will likely have a cap on it.
