Nginx as Layer 7 Proxy

    Run round robin load balancing.
    Browser communicated to nginx ->
    1 tcp connect between client and nginx -> which gets terminated at nginx.
    Nginx creates 4 tcp connection with 4 other servers
    
    ip_hash :
    hash the client ip to a particular web server
    this is useful for stateful application [sticky-state]
