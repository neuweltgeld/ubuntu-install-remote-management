Sunucunuza linux xfce dağıtımı kurmak ve uzaktan bağlanmak için şu adımları izleyebilirsiniz.
Komutları tek tek girmeniz iyi olur.

```console
sudo apt-get update && sudo apt-get upgrade -y

sudo apt-get install xfce4 xfce4-goodies xorg dbus-x11 x11-xserver-utils -y
 
sudo apt-get install xrdp -y

sudo apt install lightdm

sudo apt-get install tightvncserver -y

vncserver

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo dpkg -i google-chrome-stable_current_amd64.deb

# hata alırsanız
sudo apt -f install

reboot

root yetkisiyle çalıştırıyorsanız çalıştırma yoluna
--no-sandbox 
ekleyin.

(güvenlik sıkıntısı olabilir, bu sebeple root yerine user kullanın )
```
