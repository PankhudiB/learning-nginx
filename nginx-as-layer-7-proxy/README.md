Nginx as Layer 7 Proxy

    Run round robin load balancing.
    1 tcp connect between client and nginx -> which gets terminated at nginx.
    Nginx creates 4 tcp connection with 4 other servers