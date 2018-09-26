# Linux-server-setup
In this project I set up a server to host my catalog website.

## >Access data:
#### Public IP: 34.222.251.54
#### SSH port: 2200
#### Any Password requested: robot
#### SSH key:
-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEAzfWTlZemaQlIc7geMUnW4mvNQ03B9NoNsdj4JMxT/InNPI+8
hwzaixvo2e3UKnR02McUwVMUh9sQfW2gPzmv+D3NImGxWIAB88FpESkhy+oSxuio
/u8InZtrhDEswH53e+qTd/mYFKwnH9+OHBT0mF2K65YWkOZRy8Gucpc8ge+MNh62
7g46wsNu6Z52TgjShtg7hphqtgkLKXmRekE9/FfqevNhcPGDtL39vbHZQ03L+3XB
pzlwWRsW1DmQycPbbzLIWTasJjigZmPQy89e1plLEIwIRSwm5XzgU5mi1DJ5Dpwf
Qzp5elIBQvlyadg0en2UmUlVbg7Jmiv2IC6srQIDAQABAoIBAB15jqRy7oLLrE27
RL7jBVij+t0t7JsA9cLE/UYu47oZcoC/RUjCgygzV1CQ47MrtWksnIDKRf7nT+XT
YYKK2+8X0RqhhoLW1vCudj3ZeBe5qPREaaMKTF5Z1ro1W2U09B6MxIv/8U7MEFFU
af8E1LhVcsMiWJpmC8CwOCn4ENW7U2gMOpgeaagPNiWPl/1N5A8tSIY1d4CKZbw8
meypgsSUNDyQ/rHfAV+JJLTRxKhMv08ITrdezNnV18mHEHrL8SC78KOHEJ52alnj
sq5JNzYBPjU+Ub1QoFEVx5nfq4EfRVlkSIUpk6ilEyahx2PwwwCVfWjIZ9BrFNkP
gO9f6RUCgYEA/7Jn6N4nuyWXNWHoxMVyZoeyK79DQDYrjCZb0m6+fej2cvYy9fAS
AYeqOHdSSXeI7a4fjCQKM+dEPA2JlTdIjWWHNBvNu8ydpSTKFcByu97V31u86g8k
cVGN7vCFdfTuyirWV3DQfcrRv4NE/JoHDTAsJ3kPQABwkbAxOa6qad8CgYEAzjQT
wRZleyboMy00345EqdFrkBs84Z8e6i6yePG0f1RX+SYdDVbY0IZ7S0RlJOglEROs
P/KrqwbZ5QdocTev2Y0tAHqrBB/gH/WxFGGk7XMt1pSPKo7ygtgkGEq5aLVfZuwG
lNKaN+Ru7hj9JW+EGegD6JnixyagZQ5apqNVkvMCgYEAjKHGDsjo10CUirLAAEGM
ayHk97SpO07P4rRSOknYkY2oxo/sdWHFtXu1Pns6Edghwn/LMBu+VM+0ssbLTftq
9wHJO/qyy8B9UBAM6avALt4fiUp+e8k6RO0TAEDfVoIRN7YZz1vn/9emRwvezIO2
ryU4k7k8jvnu7+IVIOGVLscCgYEAjzqZJhu6bap+y11xRn95rkNq5XQl+8odHSlG
ir/JUlBxsvwIXgWfIGjpJ0TgxJwDczMpCFo1Z9ygaXeV0l6N5R0szxJly72gXlK4
p6GTf+PrSQtzzmnwhXZAzCbLVrH1DHaRs7n9qSkg7H2rCN/G8H+6h0ysuwxXiRpJ
WUpG3IUCgYEAmUYSK3Zf3baKkrMJUDS+z96APm3YPC9bmysjs2Dhzk4z123lgrNI
rGnOS7x3yD82QNWZw/epI4T3dWk1oCF8gitOVt0zIHxyCF2wir5PA/h1ynorHG3K
oSw3kNhOS62PK4xZ7FYMrIIQtu+4zsOYcS7q/6ee7+/nija2ioaRMHk=
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
