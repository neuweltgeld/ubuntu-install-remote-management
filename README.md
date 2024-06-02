

```
sudo apt-get update && sudo apt-get upgrade -y 
sudo apt-get install xfce4 xfce4-goodies xorg dbus-x11 x11-xserver-utils -y 
sudo apt-get install xrdp -y 
sudo apt install lightdm 
sudo apt-get install tightvncserver -y 
vncserver

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb

in case error
sudo apt -f install

reboot

add --no-sandbox flag to chrome path to run as root (use user instead. working with root access is not recommended)
```
Done!
