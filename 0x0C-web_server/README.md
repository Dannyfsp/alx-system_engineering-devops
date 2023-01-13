# A readme on 0x0C. Web server
This project is given by ALX. It's purpose is to make us to be familiar with how the web works, how to configure Nginx, how to use scp, how to use curl, HTTP requests, HTTP redirection and Log files on Linux.

## Background Context
In this project, some of the tasks will be graded on 2 aspects:
* 1. Is your web-01 server configured according to requirements
* 2. Does your answer file contain a Bash script that automatically performs commands to configure an Ubuntu machine to fit requirements (meaning without any human intervention)

For example, if I need to create a file /tmp/test containing the string hello world and modify the configuration of Nginx to listen on port 8080 instead of 80, I can use emacs on my server to create the file and to modify the Nginx configuration file /etc/nginx/sites-enabled/default.

But my answer file would contain:

sylvain@ubuntu cat 88-script_example
#!/usr/bin/env bash
# Configuring a server with specification XYZ
echo hello world > /tmp/test
sed -i 's/80/8080/g' /etc/nginx/sites-enabled/default
sylvain@ubuntu

As you can tell, I am not using emacs to perform the task in my answer file. This exercise is aiming at training you on automating your work. If you can automate tasks that you do manually, you can then automate yourself out of repetitive tasks and focus your energy on something more interesting. For an SRE, that comes very handy when there are hundreds or thousands of servers to manage, the work cannot be only done manually. Note that the checker will execute your script as the root user, you do not need to use the sudo command.

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* What is the main role of a web server
* What is a child process
* Why web servers usually have a parent process and child process
* What are the main HTTP requests

## DNS
* What DNS stands for
* What is DNS main role

## DNS Record Types
* A
* CNAME
* TXT
* MX
