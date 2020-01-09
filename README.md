# RPi-webpage
Webpage for RPi functions

curl "https://autoremotejoaomgcd.appspot.com/registerpc?key=YOUR_KEY&name=NAME_TO_APPEAR_ON_YOUR_PHONE&id=ANY_UNIQUE_ID&type=linux&publicip=YOUR_PUBLIC_IP_OR_HOST_NAME&localip=$(sudo ifconfig eth0 |grep "inet addr" |awk '{print $2}' |awk -F: '{print $2}')"
YOUR_KEY - The key obtained in the point 2
NAME_TO_APPEAR_ON_YOUR_PHONE - Give it a name ie RPI3
ANY_UNIQUE_ID - make up an ID ie 314
YOUR_PUBLIC_IP_OR_HOST_NAME - the IP or DNS obtained in the point 3
