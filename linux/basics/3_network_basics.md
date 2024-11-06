# interfaces information

ifconfig - show interfaces information
iwconfig - show wireless interfaces information

# interfaces modification

ifconfig [interface] [IP] netmask [MASK] broadcast [BROATCAST] - modify ip, mask and broadcast to an interface

ifconfig [interface] down
ifconfig [interface] hw ether [MAC-ADDRESS]
ifconfig [interface] up

# network information

arp-scan --interface=[interfaz] --localnet -> show devices ips in your local network
arp -a - show ips that interacted with your device recentlya


# DNS

dig [nameserver] -> show ip of a given namesarve

file /etc/resolv.conf "nameserver 8.8.8.8" -> modify dns server to use 
