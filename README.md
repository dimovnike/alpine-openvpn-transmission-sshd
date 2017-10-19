Container with transmission, openvpn and sshd. The purpose of sshd is to provide socks proxy via vpn. Extends image dimovnike/alpine-openvpn-transmission.

## To configure ssh:

docker run -p<port>:22 -v /path/to/folder/with/authorized\_keys/:/root/.ssh 

If you dont provide a folder with authorized\_keys file you will not be able to login.

## To configure the rest, refer to images:

dimovnike/alpine-openvpn-transmission and dimovnike/alpine-openvpn
