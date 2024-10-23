# Wi-Fi-HACK
pkg update
pkg upgrade
pkg install tsu
pkg install python
pkg install git
pkg install -y root-repo
pkg install -y git tsu python wpa-supplicant pixiewps iw openssl
termux-setup-storage
git clone --depth 1 https://github.com/IAR-CYBER-143/Wi-Fi-HACK
# Then Exit Termux
# Now Run

sudo python Wi-Fi-HACK/RISAT-Shot.py -i wlan0 -K

then exit and again run 

sudo python Wi-Fi-HACK/RISAT-Shot.py -i wlan0 --iface-down -K
