# 0x0A-Configuration Management
A Configuration management project given by ALX.

Configuration Management is the process of maintaining systems, such as computer hardware and software, in a desired state. Configuration Management (CM) is also a method of ensuring that systems perform in a manner consistent with expectations over time.

Configuration management (CM) also refers to the process of systematically handling changes to a system in a way that it maintains integrity over time.

The purpose of this project is to expose to us the various configuration management tools and how to use them and for this project we used Puppet.

In computing, Puppet is a software configuration management tool which includes its own declarative language to describe system configuration. It is a model-driven solution that requires limited programming knowledge to use.

## Architecture
Puppet usually follows client-server architecture. The client is known as an agent and the server is known as the master. For testing and simple configuration, it can also be used as a stand-alone application run from the command line.

Puppet Server is installed on one or more servers, and Puppet Agent is installed on all the machines to be managed. Puppet Agents communicate with the server and fetch configuration instructions. The Agent then applies the configuration on the system and sends a status report to the server.
