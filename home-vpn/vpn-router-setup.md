# VPN Setup on Router
## Router Details 
Name: AX3000 4-Stream Wi-Fi 6 Router
VPN Server: OpenVPN

Type: OpenVPN
Enabled: Yes
Service Type: UDP - uses udp for tunnels 
Interface Type: TUN - uses the network tunnel  @layer3 
Service Port - 1194, default for OpenVPN
VPN Subnet : 10.8.0.0
Netmask: 255.255.255.0 (/24)
Client Access: Home Network Only -- only use for connection to homelab devices, not internet

Certificate: Generated
