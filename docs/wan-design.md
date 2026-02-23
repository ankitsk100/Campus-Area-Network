
# WAN Design

WAN connectivity is implemented using Serial interfaces (/30 subnets).

Links:
- Main ↔ Branch (10.10.10.0/30)
- Main ↔ Cloud (10.10.10.4/30)

Notes:
- If the serial interface is DCE in Packet Tracer, configure `clock rate 64000`.
- Ensure all serial interfaces are `no shutdown`.
