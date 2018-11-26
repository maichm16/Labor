
Rechte Übersicht:
ls -la /home

rmdir /home/test
verzeichnis anlegen

chown sx /home/test

Test gehört Root. Den SX geben


chmod (oTHER/gROUP/uSER)-rx /home/test
chmod 700 /home/sx      Lese rechte Wegnehmen

alias...bei Ubuntu ll
Raspbian nano ~/.bashrc

abkürzungen verwalten

ll einkommentieren
# entfernen


~ abkürzung für /home

Tree nicht auf Lite installiert

Advanced pakage technology

verwendete dpkg tool
apt
/etc/apt/

cd /etc/apt

apt update
Sucht Upgrade Packete

Upgraden: apt dist-upgrade

mit Dist upgradet er Kernel auch

apt install tree
installiert tree package

dpkg -- list | WC

ssh -X pi@10.200.114.217

Desktop Programm steuern

xeyes

mit Steuerung z Stoppen
fg weierlaufen
bg in den Hintergrund

ps Welche Prozesse laufen
ps -ef | xeyes

Zeigt alle und Filtert xEyes

kill ()
Rauswerfen


raspi-config
Raspi Config Commando


ssh keygen

öffentlichen Key kopieren
ssh -cop-id pi@ip

am anderen cat .ssh/authorized_keys 

Kann sofort einlogen der auf dem Rechner sitzt

-> Den Schlüssel ein passwort geben

Einstieg sicherer

WICHITG: vom PC aus
schlüssel auch

ssh-keygen
ssh-copy-id pi@10.200.114.227


nano .ssh/config

Host Chef
  Hostname IP adresse
  User PI

ssh NAME

    1  ip a
    2  sudo nano /etc/hostname
    3  hexdump /etc/hostname
    4  hexdump -C /etc/hostname
    5  cat /etc/hostname
    6  less /etc/hostname
    7  sudo nano/etc/hosts
    8  sudo nano /etc/hosts
    9  sudo reboot
   10  passwd
   11  sudo -i
   12  sudo -i
   13  ll
   14  nano .bashrc
   15  exit
   16  ll
   17  tree
   18  cd
   19  exit
   20  ll .ssh
   21  ls -la -
   22  ls -la ~
   23  ls -la -
   24  ll .ssh
   25  cat .ssh/authorized_keys 
   26  history

    1  passwd
    2  less /etc/passwd
    3  man passwd
    4  man 5 passwd
    5  less /etc/group
    6  less /etc/shadow
    7  less /etc/passwd
    8  man adduser
    9  man adduser
   10  adduser maichm16
   11  less /etc/passwd
   12  less /etc/passwd
   13  less /etc/group
   14  less /etc/shadow
   15  ls /home
   16  ssh maichm16@10.200.114.227
   17  less /etc/sudoers
   18  less /etc/group
   19  less /etc/passwd
   20  nano /etc/group
   21  ls -la
   22  cat .bash_history
   23  history
   24  history
   25  less history
   26  history
   27  history
   28  poweroff
   29  history
   30  less /etc/passwd
   31  cd /etc/apt
   32  cd /etc/apt ll
   33  cd /etc/apt ls -la
   34  cd /etc/apt ls -la
   35  apt:update
   36  apt:update
   37  apt:update
   38  apt update
   39  apt install tree
   40  tree
   41  cpkg -list |Wc
   42  cpkg -list |WC
   43  cpkg -list|WC
   44  cpkg --list|WC
   45  cpkg--list|WC
   46  dpkg--list|WC
   47  dpkg --list|WC
   48  dpkg --list|WC
   49  ssh -X pi@10.200.114.217
   50  raspie -config
   51  raspie-config
   52  raspi-config
   53  cd ~
   54  ~/.ssh
   55  .ssh
   56  /home/.ssh
   57  ls -la ~/.ssh
   58  ssh-keygen
   59  ls -la ~/.ssh
   60  ssh-copy-id pi@10.200.114.227
   61  nano .ssh config
   62  cp /home/pi/.ssh/authorized_keys .ssh/
   63  chmod 600 .ssh
   64  history

