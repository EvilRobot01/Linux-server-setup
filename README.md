# Linux-server-setup
In this project I set up a server to host my catalog website.

## >Access data:
#### Public IP: 34.221.212.186
#### SSH port: 2200
#### Any Password requested: robot
#### SSH key:
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEAojNzeWrf7bPBSjZInjWkVYgqYTUdgIOd7jArfT5UhAG4Wo8n
1M8f4YCeVNIJfV1HV3hzFFoYacTk1adJzQCBPXMprwpQPyDYYGSN9YjcFFVuDvDz
3BqVh9ZkqBfCjHi8gLOqWslCajtcmkjYbuX76MvAajSZ9D9k/4fiJpTb4ZHKZPN8
bcrRC36JCdSYlSbP/Nw+FmVdcFaTR0mmcePr0IfOMIZruh79+bRdzJuQ9jf70e86
5ri9Tk0MwO/c2x7twMy7ImiGJAk9qx2a77EIsnf9+UaO0YjA+9s9OgsuDtDmrOeP
JREGpKIUecWcrjBgrAhNKwbgBpHJjECVT2PAawIDAQABAoIBAQCXFgH8GVdY3VWw
wPvHkwPuQBXp0kYWzYKwueHomcSz6b5FbI+XpQ93SA0zySnZwqePjLz1Oi7/Zs4Z
TehqsouwJ7OuPpcdFoU21LN/AOqvbhxEgqFEZubeTxAXm3o2ysgbwj9urYXV2lGZ
zTz9n/CUmiYzR6gYYWy8sWAwu/xNEbqZ32L0J5sZ+U15omeE7uw0VyNhp2YI4mhN
eNZm3wOXNKlmbtVlOtYeQ/1WC89G/n7sfjcj8dbG0K3Uir41srZ+WYme2eanBirq
rJChOa9zSjvhKEdf0MR5i4ixwJU11dgqkGEsdRJJhTChsmTKOnZLUBa1OQgo7aAN
qP7OOB3BAoGBAM+zuTjp22+hPM7v7gH5/D9h2aMoGWmhY5llCYhak1sSgFRK4k5q
WaBRnrcGsDC2vR1lOdOj0Nk5fEC2xayrBar039BPb70PD+33mEP+dEtHhrXP2Nxt
7THPpQyZ2GA8EWhwytJJ/ed8E1/UMqYAkCQhPPhbLMZd1ynF4l7G1kuRAoGBAMfr
GUg486+tUYWvpzooXrPrGf1ZsMIp8o9mxUFTmpAhDgptelSh/SjhVae8zD7uU8Bt
nBFCWSF7DGjy/SEl3vPvutzzP1kvfZFrT1ilUvrOrvXE8z4gYDxoRZRNIIhmu/qY
57C3UcMQvX8qstDZhvjozcnj/ZJqv8UKtdKps/Y7AoGBAIroUbnEfSNdHEPxpqXf
wFnLYTiC+uvwKaJPNl7g5KgF6Zl2M3/qFGLp81HIwVDzBeuA5Xmrl2OP1I+bLPzb
rAC3oG+6kKpKRocKDeV7ad9myKsThJ93TSkBDAsvYMyLn8DPnnWhUpPcIUD3s5/d
xIjFSfd3Uqyf2eRwGYL1TCBhAoGAa0Q9wH6uYeiBAVYKSC45Ahh3TXS+Xq/bMg5W
cILHP+Y8fmPXa2mvSCv/pYyrmmiOD4XAY5JR+KDpO7aFEzAavJA4lyz9JIFSwp/t
Zwbtyxzyy3Ptf7wnZsIb80Ke3hEhc4hvaGY0PJHS21SxtVXCEfP31we5msIkOzlP
7cSYhtkCgYBlZnimkVRfjSS5DQbGc2ncBKzJntQH1jCAUJ7w8GnOhFvKlIqv5NU/
E985ZICqh1+zJanlNiIYTX+jYM0eE82Pjw1q2wJQekwnrpImCuy8ZCJRSmt2RcNn
an1gK1yFbgsj3cm2T0gf/SHqs75yVWdDA/6JnnMu/qGTBd7Sjb8KBA==
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

