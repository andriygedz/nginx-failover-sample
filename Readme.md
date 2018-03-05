Nginx automatic failover load balancing

See nginx-conf/nginx.conf for nginx cofig

# docker-compose up

docker compose starts two httpd services 

# docker stop nginxfailoversample_service1_1  

Stop service1 and nginx will redirect all requests to servise2

# docker start nginxfailoversample_service1_1 

Than start service1 and nginx will redirect requests to both service1 and service2
