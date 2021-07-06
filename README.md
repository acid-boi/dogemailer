Hemlo Fremds!!

This is dogemailer, a python script for sending spoof mails from anyone's mail id. Thiscan be run as a server, as well as locally on your machine. Let me guide you with its usage.

For limnux users

```
$ git clone <The git url of this repo>
$ cd dogemailer
$ chmod +x dogemailer
$ ./dogemailer

```
To run this as a server:

```
Follow the first 3 steps, and after that do
while true; do nc -lnvp 8080 -e "./dogemailer"; sleep 1; done
**Note that in some cases the nc doesn't supports the execution of command, in such cases, ncat needs to be installed.
```


For mac and windows umsers:
```
Go and get a linux machine
```

The libraries used in this project:
1. sys
2. smtplib

These can be installed using

```
pip install <name of the library>

```


==Prerequisites==
1. A computer having python3 installed
2. An account on smtp2go.com.(The username and password needs to be entered in the code. It is always advisable to expport them as environment variables.)

3. A brain

4. Atleast one hand

Citation required.
