# Web stack debugging #4

In this task, we were required to test how well our web server setup featuring Nginx is doing under pressure and it turns out it's not doing well: we were getting a huge amount of failed requests.

For the benchmarking, we are using ApacheBench which is a quite popular tool in the industry. It allows us to simulate HTTP requests to a web server. In this case, we will make 2000 requests to our server with 100 requests at a time. We noticed that 943 requests failed, we'll fix our stack so that we can get to 0, and we have to keep in mind that when something is going wrong, logs are our best friends.

We'll have to debug this issue and come to a possible solution.
