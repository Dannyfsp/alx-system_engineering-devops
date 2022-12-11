A readme on Web Infrastructure design project given by ALX.

This project require us to design the different types of server web infrastructure that hosts the website www.foobar.com

At the end of this project we are expected of the following without the help of google or anyone:
* We must be able to draw a diagram covering the web stack we built with the sysadmin/devops track projects
* We must be able to explain what each component is doing
* We must be able to explain system redundancy
* We must know all mentioned acronyms: LAMP, SPOF and QPS

## 0-simple_web_stack
For this task, with the use of a whiteboard, we designed a one server web infrastructure that hosts the website that is reachable via www.foobar.com using the following:
* 1 Server
* 1 Web server(NGINX)
* 1 Application server
* 1 Application file(our code base)
* 1 Database(MySQL)
* 1 domain name foobar.com configured with www record that points to our server IP:8.8.8.8

## 1-distributed_web_infrastructure
For this task, with the use of a whiteboard, we designed a three server web infrastructure that hosts the website www.foobar.com using the following:
* 2 Servers
* 1 Web server
* 1 Application server
* 1 Load-balancer(HAproxy)
* 1 Set of application files(our code base)
* 1 Database(MySQL)

## 2-secured_and_monitored_web_infrastructure
For this task, with the use of a whiteboard, we designed a three server web infrastructure that hosts the website www.foobar.com which must be secured, serve encrypted traffic and monitured adding the following:
* 3 Firewalls
* 1 SSL certificate to serve www.foobar.com over HTTPS
* 3 monitoring clients (data collector for Sumologic or other monitoring services)

## 3-scale_up
For this task, we added the following:
* 1 Server
* 1 load-balancer(HAproxy) configured as a cluster with the other one
* Split components (web server, application server, database) with their own server

Whiteboarding tool used: www.miro.com

AUTHOR:
Bogare Aghogho Daniel
