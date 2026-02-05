# IP Addressing Scheme

The network uses private IPv4 addressing with one /24 subnet
assigned to each department.

This approach simplifies troubleshooting and supports scalability.

## Subnet Allocation

| Department | Subnet | Default Gateway |
|-----------|--------|-----------------|
| Department 1 | 192.168.10.0/24 | 192.168.10.1 |
| Department 2 | 192.168.20.0/24 | 192.168.20.1 |
| Department 3 | 192.168.30.0/24 | 192.168.30.1 |
| Department 4 | 192.168.40.0/24 | 192.168.40.1 |
| Department 5 | 192.168.50.0/24 | 192.168.50.1 |

## DHCP Strategy
- Centralized DHCP on the router
- Separate DHCP pool per subnet
- Supports wired and wireless clients
