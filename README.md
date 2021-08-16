# learning-nginx

All folders have README.md where i have jotted down my understanding
Go through in the following order :

1st. nginx-as-web-server

2nd. nginx-as-layer-4-proxy

3rd. nginx-as-layer-7-proxy

In a nutshell :

NGINX

    Works both as Webserver and Proxy

Webserver

    Serves web content
    - static content / html / js

Proxy
    reverse proxy - public -> private
    load balancing 
    backend routing
    
Nginx can act as Layer 4 and Layer 7 proxy

    Layer 4 --> 
        The TCP/IP layer, where we are aware of the TCP handshake and src and destination ports attached. 
    
    Layer 7 -->
        The Application layer, where you have all the headers and content type etc.

    Nginx 4 proxy using stream context
    Nginx 7 proxy using http context
