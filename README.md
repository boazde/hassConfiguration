# hassConfiguration

Steps for Installing Home Assitant on Rpi with raspbian
1. Download RASPBIAN STRETCH LITE from https://www.raspberrypi.org/downloads/raspbian/
2. Download Etcher from https://etcher.io/
3. Download putty  https://www.putty.org/
4. Check the manual installation at https://www.home-assistant.io/docs/installation/raspberry-pi/
  ssh pi@ipaddress
  $ passwd
  $ sudo apt-get update
  $ sudo apt-get upgrade -y
  $ sudo apt-get install python3 python3-venv python3-pip nmap git 
  $ sudo useradd -rm homeassistant -G dialout
  $ cd /srv
  $ sudo mkdir homeassistant
  $ sudo chown homeassistant:homeassistant homeassistant
  $ sudo su -s /bin/bash homeassistant
  $ cd /srv/homeassistant
  $ python3 -m venv .
  $ source bin/activate
  (homeassistant) homeassistant@raspberrypi:/srv/homeassistant $ python3 -m pip install wheel
  (homeassistant) homeassistant@raspberrypi:/srv/homeassistant $ pip3 install homeassistant
  (homeassistant) $ hass
  You can now reach your installation on your Raspberry Pi over the web interface on http://ipaddress:8123.
  
  If Home Assistant install is not located at /srv/homeassistant, please modify the ExecStart= line appropriately.

    [Unit]
    Description=Home Assistant
    After=network-online.target

    [Service]
    Type=simple
    User=%i
    ExecStart=/srv/homeassistant/bin/hass -c "/home/homeassistant/.homeassistant"

    [Install]
    WantedBy=multi-user.target

  sudo systemctl enable home-assistant@homeassistant
