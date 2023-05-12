# docker-lxd-network
If you have installed docker and lxd on the same mache, and the internet connection is not working on your lxd containers, try running this command on the host machine

` iptables -I DOCKER-USER  -j ACCEPT && iptables-save`
