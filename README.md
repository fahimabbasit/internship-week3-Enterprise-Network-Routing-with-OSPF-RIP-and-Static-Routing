# Advanced Routing Configuration Using OSPF, RIPv1, RIPv2, Static Routing, Route Redistribution and Floating Static Routes

## Project Overview

This project demonstrates the implementation of a hybrid enterprise network using multiple routing technologies in GNS3. The topology integrates OSPF Multi-Area Routing, RIP Version 1, RIP Version 2, Static Routing, Route Redistribution, Default Static Routing, and Floating Static Routes to provide end-to-end connectivity and route redundancy.

The network was designed to simulate communication between different routing domains using an Autonomous System Boundary Router (ASBR) and an Area Border Router (ABR).

---

## Objectives

- Configure Multi-Area OSPF.
- Configure RIP Version 1.
- Configure RIP Version 2.
- Configure Static Routing.
- Configure Default Static Route.
- Configure Route Redistribution.
- Configure Floating Static Routes.
- Verify complete network connectivity.
- Implement backup routing using Floating Static Routes.

---

## Network Components

- 8 Cisco Routers
- Multi-Area OSPF
- Area Border Router (ABR)
- Autonomous System Boundary Router (ASBR)
- RIP Version 1
- RIP Version 2
- Static Routing
- Default Static Route
- Floating Static Route
- Route Redistribution

---

## Routing Protocol Allocation

| Router | Role |
|---------|------|
| R1 | OSPF Area 0 |
| R2 | OSPF Area 0 |
| R3 | ABR (Area 0 & Area 1) |
| R4 | ASBR |
| R5 | Static Routing |
| R6 | RIP Version 1 |
| R7 | RIP Version 2 |
| R8 | OSPF Area 1 |

---

## Features

- Multi-Area OSPF
- Dynamic Routing
- Static Routing
- Default Route
- Route Redistribution
- Route Redundancy
- Floating Static Routes
- End-to-End Connectivity
- Network Verification

---

## Repository Structure
Project/ │ ├── GNS3_Project/ ├── Configurations/ ├── Screenshots/ ├── Week3_Report.pdf └── README.md

---

## Verification

The following tests were successfully completed:

- OSPF Neighbor Verification
- Routing Table Verification
- RIP Route Verification
- Route Redistribution Verification
- Static Route Verification
- Floating Static Route Verification
- End-to-End Ping Verification

---

## Software Used

- GNS3
- Cisco IOS Routers
- Microsoft Word
- GitHub

---

## Author

**Fahim Abbas**

Network Administration Internship Program
