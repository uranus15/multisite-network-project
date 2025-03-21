Site 1 and Site 2 each have their own router and switch.
Both routers are connected via a point-to-point link with IP addresses 10.0.0.1/30 and 10.0.0.2/30.
Each site has a local network (192.168.1.0/24 for Site 1 and 192.168.2.0/24 for Site 2).
OSPF (Open Shortest Path First) is used for routing between the sites.
The switches are configured with VLAN 1 for simplicity, and ports are configured to connect to the routers and local devices.
Security Settings:
Access Control Lists (ACLs) are configured to permit traffic from the local network and deny all other traffic.
ACLs are applied to the relevant interfaces to control inbound traffic.
DHCP Configuration:
DHCP excluded addresses are set to avoid conflicts with static IP addresses.
DHCP pools are created for each site to assign IP addresses dynamically to devices.
DNS Server Configuration:
DNS server settings are configured to provide DNS resolution within the local network.
This configuration provides a more advanced setup for your small office network, incorporating security measures, dynamic IP address allocation, and DNS resolution.
