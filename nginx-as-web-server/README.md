Nginx as Web Server

    We will need target port it can listen traffic to.
    Where should it pick the static content from ? js/html/css
    The server needs to know that it is running at http layer
    http {} -> inside this block u can create as many servers as ossible on different ports
    block directive
    listen 8080 -> target
    localhost:8080 -> serve a default page -> because of nginx.conf.default
    To start the nginx server : type the command -> nginx
    
    nginx -s stop ---> stops the nginx server