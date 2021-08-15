Nginx as Layer 4 Proxy

    location directive and all will not work hear..
    there is no http no slash
    you do not know which protocol u are using
    at layer 4, any protocol of layer 7 will work.. whether its http,smtp,webrtc
    u r just dealing woth tcp packet
    just tel niginx which backend u want to stream to

    when u hit localhost
    That is why even if u have written a round robin config. u ll still be hitting same backend    
    browser forms tcp connection with nginx
    nginx is going to communicate the connection all the way to backend    
    nginx engine does a NAT
    [this ip on this internal port is trying to come to me ..but the real me is 1 of the backend]
    it ll pick the backend.
    
    Any future request from this client now will always go to the same backend 2222
    bcoz its 1 tcp connection. u r not going to establish connection again. 
    u r using the same connection that was established earlier. and sending content over it.


    

    
    