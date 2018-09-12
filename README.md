# Linux-server-setup
In this project I set up a server to host my catalog website.

## >Access data:
#### Public IP: 34.222.131.32
#### SSH port: 2200


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
