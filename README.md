# Linux-server-setup
In this project I set up a server to host my catalog website.

## >Access data:
#### Public IP: 50.112.59.196
#### SSH port: 2200
#### SSH key:
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC5/QWjpy3P59l9RGqH3hgo4sjDZFyhYGyNCwfE8lcSCJfw0WzQzg
QAWrFFY5Jl/zW6MzN4Novn4zJ2Zk//W9HjM620vNHh2hZjBrEP4+2FkQOqTjpyQoZxO1ZVx3Q26tLENrFsgTW7D6oN
rKVo3IEXJnEZjgSeL1sK7yZcMNt2PX16VpANjRqc5Fn20Z/yuBGsH0zjK6jBYmsj2yWF666uoTL0xKdgMntb2ouB0b
6KfQZ7LnyOgQy2svS8vU4dDt2ioQgFdLbKYzDt51IgSpit8GLz2vNDFnA9iASrFQWo6tJWFJY614ZuUO7q2CRZ3O+Q
F+oHfwbQrM0v8AJwp57b ubuntu@ip-172-26-3-151


## Softwares and steps:
1.Update all currently installed packages.

2.Download package lists with sudo apt-get update.

3.Fetch new versions of packages with sudo apt-get upgrade.

4.Change SSH port from 22 to 2200.

5.Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).

6.Configure the local timezone to UTC.

7.Configure key-based authentication for grader user.

8.Install Apache.

9.Clone the Catalog app from Github,

10.Install virtual environment.

11.Install Flask and other dependencies.

12.Configure and enable a new virtual host.

13.Install and configure PostgreSQL
