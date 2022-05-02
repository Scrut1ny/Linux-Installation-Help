Full update, upgrade, dist-upgrade, autoremove, & clean:
```
sudo apt update -y && sudo apt upgrade -y && sudo apt dist-upgrade -y && apt autoremove -y && apt clean -y
```

Fixing tzdata:
```
sudo apt install ntpdate && apt ntpdate in.pool.ntp.org && apt dpkg-reconfigure tzdata
```

Install Alfa card drivers:
```
sudo apt install dkms && sudo apt install realtek-rtl88xxau-dkms && sudo reboot now
sudo git clone https://github.com/aircrack-ng/rtl8812au && cd rtl8812au/ && make && sudo make install && sudo rm -rf rtl8812au
```

Installing Wifite:
```
sudo git clone https://github.com/kimocoder/wifite2.git && sudo pip install pytest-flake8 && sudo apt install hcxdumptool && sudo apt install hcxtools && sudo apt-get install libpcap-dev && sudo apt-get install python2.7-dev libssl-dev zlib1g-dev libpcap-dev && sudo git clone https://github.com/JPaulMora/Pyrit.git && cd Pyrit && sudo python3 setup.py clean && sudo python3 setup.py build && sudo python3 setup.py install && sudo apt clean -y && sudo apt autoremove -y
```

Installing Tor Browser:
```
https://www.howtogeek.com/423866/how-to-install-and-use-the-tor-browser-on-linux/
```

Awesome GitHub Tools:
```
git clone https://github.com/v1s1t0r1sh3r3/airgeddon
git clone https://github.com/aircrack-ng/aircrack-ng
git clone https://github.com/aircrack-ng/mdk4
git clone https://github.com/yt-dlp/yt-dlp
git clone https://github.com/ohmyzsh/ohmyzsh
git clone https://github.com/hashcat/hashcat
git clone https://github.com/lanmaster53/recon-ng
git clone https://github.com/s0md3v/ReconDog
git clone https://github.com/laramies/theHarvester
git clone https://github.com/zxllkada/Get-instagram-users-info---Any-instagram-account
git clone https://github.com/martinvigo/email2phonenumber
git clone https://github.com/aircrack-ng/rtl8812au
git clone https://github.com/thewhiteh4t/FinalRecon
git clone https://github.com/khast3x/h8mail
git clone https://github.com/sherlock-project/sherlock
git clone https://github.com/threat9/routersploit
git clone https://github.com/HiroshiManRise/anonym8
git clone https://github.com/m4ll0k/Infoga
```
