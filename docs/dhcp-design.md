# DHCP Design

DHCP is configured on routers with one pool per VLAN.

Each pool includes:
- network address
- default-router (VLAN gateway)
- dns-server

Verification:
- `show ip dhcp binding`
- PC should receive correct VLAN subnet + correct gateway
