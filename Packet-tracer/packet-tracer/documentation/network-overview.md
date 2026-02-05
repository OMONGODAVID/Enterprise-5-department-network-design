Network overview documentation.
# Network Overview

This project represents a small-to-medium enterprise 5 department campus network
designed using Cisco Packet Tracer.

The network consists of five departments, each operating on its own
IP subnet while sharing centralized network services.

## Design Objectives
- Logical separation of departments
- Centralized IP address management using DHCP
- Support for wired and wireless users
- Integration of VoIP phones and network printers
- Scalable design for future growth

## High-Level Architecture
- One central router connecting all departments
- Each department connected via a dedicated router interface
- One access switch per department
- Wireless Access Point per department
- Shared server segment

## Traffic Flow
- Intra-department traffic is switched locally
- Inter-department traffic is routed through the central router
- DHCP requests are handled centrally by the router
- Wireless traffic is bridged into the department LAN

This architecture reflects common enterprise LAN design principles.
