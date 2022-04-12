# Simple Web App

Simple web app for labs.

## Installation

First switch user to root:

~~~
sudo su
~~~

Clone repository to directory `/root`:

~~~
git clone https://github.com/nuwm-cloud-and-big-data/web-app.git /root/web-app
~~~

Copy daemon file for setup:

~~~
cp /root/web-app/etc/systemd/system/web-app.service /etc/systemd/system/web-app.service
~~~

Add service to auto start and start service:

~~~
systemctl enable web-app.service
systemctl start web-app.service
~~~

Exit from root user profile:

~~~
exit
~~~