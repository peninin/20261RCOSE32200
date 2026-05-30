# COSE322 SYSTEM PROGRAMMING
This repository is for the optional Github assignment
## Project2 Notes
Project 2 was about packet processing with TC eBPF inside the LINUX kernel.
The client communicates using one VIP address instead of directly using backend addresses.
Packet headers are rewritten by ingress and egress eBPF programs.
eBPF maps were used to store flow information during load balancing.
I tested the implementation using vip_client and tcpdump.
This repository does not include Project1 or Project2 source code.
This project helped me understand LINUX networking and TC eBPF workflow better.
