# SDN-Mininet-Ryu-Project
## Description
This project demonstrates Software Defined Networking using Mininet and Ryu Controller. It includes firewall implementation and bandwidth analysis using iperf.

## Topology
- 1 Switch (s1)
- 3 Hosts (h1, h2, h3)

## Features
- Traffic control using Ryu controller
- Firewall rule implementation
- Bandwidth measurement using iperf

## Commands Used

### Start Controller
python -m ryu.cmd.manager controller.py

### Start Mininet
sudo mn --topo single,3 --controller remote

### Test Connectivity
pingall

### Measure Bandwidth
iperf h1 h2
iperf h2 h3
