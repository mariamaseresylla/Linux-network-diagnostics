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

## Display the routing table with ip route
## Observation
the ip route command  displays  the linux routing of  table  , it helps  idenftify the  routes used to send network  packets, including the network interface and the default gateway

in my environment:
default via 172.26.64.1 dev eth0 proto kernel
172.26.64.0/20 dev eth0 proto kernel scope link src 172.26.74.230

## Test network connectivity with ping
## Observation
The ping -c 4 1.1.1.1 command is used to test network connectivity with a remote IP address. It sends 4 ICMP packets to the destination and checks whether replies are received. It also measures response time and detects packet loss.
in my environment 
Packets transmitted: 4
Packets received: 4
Packet loss: 0%
Minimum response time: 34.704 ms
Average response time: 121.555 ms
Maximum response time: 310.381 ms

## Check DNS resolution with getent hosts

Document observations and results

 ## WHAT I LEARNED

This section will be updated as I complete the exercises and document my findings.

## SCOPE

All commands are run in my own Linux environment. Connectivity tests are limited to basic diagnostics against public services.

This project is part of my learning journey in computer networks and Linux systems.
