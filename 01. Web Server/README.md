# 1. Web Server

Last updated Feb 10, 2021

Prompt: Build a lightweight HTTP Web Server that processes incoming network requests over HTTP protocol. Web server processes and delivers web pages to clients (browsers). The pages are HTTP documents. The primary function may be to serve content, a full implementation of HTTP also includes ways of accepting content from clients (used for submitting form information or in accepting files for upload). Try to imitate [NGINX](https://www.nginx.com/) if in need of inspiration.

Ideas: Build server with Golang as it is quite good for servers from my research. This isn't something I've ever done before, so I'll need to do some research into the process of creating a Web Server.

Basically, here's what needs to happen.

Gain some HTTP knowledge, figure out what language you want to write the server in (likely Go), implement a VERY simple version (serves just an index.html, 404, and 501 errors), implement tests, run tests until it works, then add features slowly but surely, testing along the way. The whole time I want to do this is by using TDD (test dependent development).
