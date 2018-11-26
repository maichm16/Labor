
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


nano .ssh/config

Host Chef
  Hostname IP adresse
  User PI
  
  



ssh NAME
