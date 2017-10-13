# arch_wifi
wifi configuration for arch linux

## step1
install wpa_supplicant

## step2
create wpa_supplicant.conf file and  set your wifi configurations

## step3
create service file (network-wireless@.service) is an example

## step4
enable created service use the command 
sudo systemctl enable network-wireless@<your-wifi-device>.service

## step5
reboot your computer
