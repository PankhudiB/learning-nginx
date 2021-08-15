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

    To serve something other than root path
    use location block

    serve content under location block
    location block is used to decide how to process the request URI 

    Return error for a regex -> location ~ (tilda)

    proxy_pass
    Handing off a request from server runnning on port 8888 to antoher server that can communicate using http.
    