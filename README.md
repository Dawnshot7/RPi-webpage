# RPi-webpage
Webpage for RPi functions

curl "https://autoremotejoaomgcd.appspot.com/registerpc?key=YOUR_KEY&name=NAME_TO_APPEAR_ON_YOUR_PHONE&id=ANY_UNIQUE_ID&type=linux&publicip=YOUR_PUBLIC_IP_OR_HOST_NAME&localip=$(sudo ifconfig eth0 |grep "inet addr" |awk '{print $2}' |awk -F: '{print $2}')"
YOUR_KEY - The key obtained in the point 2
NAME_TO_APPEAR_ON_YOUR_PHONE - Give it a name ie RPI3
ANY_UNIQUE_ID - make up an ID ie 314
YOUR_PUBLIC_IP_OR_HOST_NAME - the IP or DNS obtained in the point 3

KexAlgorithms diffie-hellman-group1-sha1,diffie-hellman-group-exchange-sha1

KexAlgorithms curve25519-sha256@libssh.org,ecdh-sha2-nistp256,ecdh-sha2-nistp384,ecdh-sha2-nistp521,diffie-hellman-group-exchange-sha256,diffie-hellman-group14-sha1,diffie-hellman-group-exchange-sha1,diffie-hellman-group1-sha1

MACs hmac-sha2-512-etm@openssh.com,hmac-sha2-256-etm@openssh.com,hmac-ripemd160-etm@openssh.com,umac-128-etm@openssh.com,hmac-sha2-512,hmac-sha2-256,hmac-ripemd160,umac-128@openssh.com,hmac-md5,hmac-sha1,hmac-sha1-96,hmac-md5-96​
