
Run both the update and upgrade commands on your server
```
sudo apt-get update
```
```
sudo apt-get upgrade -y
```

Installing the Xfce GUI
You need to install some X-server packages
```
sudo apt-get install xfce4 xfce4-goodies xorg dbus-x11 x11-xserver-utils
```

Install a remote desktop onto your server.
```
sudo apt-get install xrdp
```

Add it to the “ssl-cert”
```
sudo adduser xrdp ssl-cert
```

You will need a VNC server on your server
```
sudo apt-get install tightvncserver
```
```
vncserver
```

Install Firefox for web browsing
```
sudo apt-get install firefox
```

Done!
