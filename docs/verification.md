
# Verification Checklist

## Switch Checks
- `show vlan brief`
- `show interfaces trunk`

## Router Checks
- `show ip interface brief`
- `show ip route`
- `show ip protocols`

## DHCP Checks
- `show ip dhcp binding`
- On PCs: verify correct IP / gateway

## Connectivity Tests
- Ping within same VLAN
- Ping across VLANs (inter-VLAN)
- Ping from Main Campus VLANs to Branch VLANs
- Ping to Cloud network (if reachable)
- `traceroute <destination>`
