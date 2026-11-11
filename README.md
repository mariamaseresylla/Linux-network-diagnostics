# Linux-network-diagnostics
A beginner-friendly Linux Network diagnostics project using command-line tools

## Project Objectives

Identify network interfaces and IP addresses.
Understand IPv4 and IPv6 addressing.
Inspect the routing table and default gateway.
Test network connectivity.
Explore DNS name resolution.
Understand subnetting and IP address ranges.
Document and understand the results of each command.

 ## Tools & Environment

- Operating system: Ubuntu Linux 24.04 (WSL2)

- Commands: ip, ping, ip route, getent, ipcalc

- Version control: Git and GitHub

## Project Progress

## Inspect network interfaces with ip addr
## Observations:

The ip addr command displays the network interfaces of my computer, their IPv4 and IPv6 addresses, and their current status.

- In my environment:

Main network interface: eth0
IPv4 address: 172.26.74.230/20
IPv6 link-local address: fe80::215:5dff:febc:c347/64
Interface status: UP and LOWER_UP
UP means that the network interface is enabled, while LOWER_UP means that the network link is operational.

Display the routing table with ip route

Test network connectivity with ping

Check DNS resolution with getent hosts

Document observations and results

 ## WHAT I LEARNED

This section will be updated as I complete the exercises and document my findings.

## SCOPE

All commands are run in my own Linux environment. Connectivity tests are limited to basic diagnostics against public services.

This project is part of my learning journey in computer networks and Linux systems.
