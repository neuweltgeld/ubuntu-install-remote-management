You can install linux xfce distro to your remote server.
Execute commands line by line

```console
sudo apt-get update && sudo apt-get upgrade -y

sudo apt-get install xfce4 xfce4-goodies xorg dbus-x11 x11-xserver-utils -y
 
sudo apt-get install xrdp -y

sudo apt install lightdm

sudo apt-get install tightvncserver -y

vncserver

# os install is done, also you can install chrome via ssh

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo dpkg -i google-chrome-stable_current_amd64.deb

# if you encounter error
sudo apt -f install

# reboot system
reboot

# if you run os as root, add this command to your chrome path
--no-sandbox 

# use user instead root as recommended.

# use your ip and vncserver password to access your server.
```
