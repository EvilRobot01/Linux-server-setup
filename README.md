# Linux-server-setup
In this project I set up a server to host my catalog website.

## >Access data:
#### Public IP: 34.210.80.206
#### SSH port: 2200
#### Any Password requested: robot
#### SSH key:
-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAuAq4V+l2SX6aHRcNpYCPq8mVkt5F8zDqhoKol+EYpa/zg2he
NjZmZS9Qpnt8Q/rCtA/kn90rpxgX2oaQg0oLFVuB9rfVBEJsMY8h69BVExT0FtbM
D2h1l1EbIUWLlq1C713I3jc1u7sQ6hnvdttqRj3o5MDiUOjQHio3OvP95lw8jGZx
goefBDE4kpYklJP+2HESdgg/dtAOHcxL0SwyXNsWJo7XXDp1ZGhhWdL906ViBkR5
0Vp87JnPTcn0dad4pl54spzPDdpD80D5gTQBElu4HGHUMgq0pSAyL//vpYZ2/oGV
7uIxhq2Jb3VHGnZ4L8NiBgMFJ4zM32nIVypoIwIDAQABAoIBAHf71S7LL6i+du7c
JrNtWz0d0PvNGUFw9JT4/bz2rUDnsxRKqJEjaiIxdJz1CJCxHNqTOfPXFyx6kqKO
9AwD67Hi1JnqQ1/hhfPRYsYALlagZHm3U5X//hnGcK+CTXzQPEEdnWTyDX/0dxSI
EAwnA+QDXKA199XT0kq4LwWqKC9TebgDKWF8RE42RQiei9lG9QJKRaofcMmN3p0I
d1jnSPxoNDVyxcq/NB1BNH27QAbuRAdY36fIYsWNIxd3fWVuz96Y3VNb5pQwEq2P
iYudby8hnw6ZiDPa9rVqgtQNJWbzUjJUELaWIEyiGcfD38DesUbuu8sOO2XWvCok
q5lDbBECgYEA9OaICpedwoIoZQqvjvunUM0Vsyc+rOr/RQubqvYI9N78ly97sBU3
JhaZlFn1J+b75p0r3FXduWuk58uUFTXCEzHd7NPjzrPehCbs39SSQX9stAbwoeHn
m3n4fDnJ1n8xx6Dv/Iz2sZu3uumKLvzxppnWCTAiAeax0UlZ3oTv0ucCgYEAwGIS
4XSRdifI1v0cu/gUUatZym+5E/K/nMBTSCi86kf/NO8l4D45Ij5s394cbRG2d1zL
vG5v8C2QrxBB5e5GvbpWLHs3ubuxDUjbqUBzz7lfEizCGmwD7SCmgUeXHlylnRS+
lA7YrjeE8fh7KSayBNpEngdMTwwp8/KRieUe1WUCgYEA2LW6wmzB/GIC7s6S5ZrI
xxaD0kGzE37rnqST/qey60T7DanF8N4FLB4pjv4/kyyx0bNZIaOWDcM0bK1X/6DP
eP7SnAQwfTPrftOXHsZTGcRxY6kUfJuTwKAhA4R7l+R8H2PJmZj/n9Dkt3B7h/Lq
v3s3zG+cWERVK5aWAPNv6RcCgYAE9sLb9GEIdnBVM8S5COalUNGJSqaw4BOXnNLJ
StvNA7yPBhipF5Hr00aF5DpBijJ2E/vhycuzm8le6wF4SFSk8pjknu1KKpCf8iBQ
1qvmUTclxefgPKdBSBVjwpAgpW1Uh0N/mH54yE/y2mF7J1dyjps0pKWQaJTwiXK9
5x6LjQKBgFseDJtIAP4HxsYJJeG4hkqePtkb3Qkjz6Jp9wziylhwvGOQBENvR77m
OAUFMsPdhSvtH1KeuJH7iPJ03M//GRrVOCPduSUjHF7rt1QKNiuyPl03OHwhiVix
9HmiKrkGas4aSPQ2sb97hnsTtHDAzgwWwDWfIGaYPIRGTSp0pUzH
-----END RSA PRIVATE KEY-----

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


## Resources:
1.[Ask Ubuntu](https://askubuntu.com/)

2.[UFW, Ubuntu Documentation](https://help.ubuntu.com/community/UFW)

3.[LAMP, Udacity](https://blog.udacity.com/2015/03/step-by-step-guide-install-lamp-linux-apache-mysql-python-ubuntu.html)

4.[Setup Flask App, DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)

