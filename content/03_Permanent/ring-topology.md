---
title: Ring Topology
parent: "[[computing-moc]]"
language: english
aliases:
  - token topology
---


The **ring topology** or **token topology** boasts some similarities. Devices such as computers are connected directly to each other to form a loop, meaning that there is little cabling required and less dependence on dedicated hardware such as within a star topology.

A ring topology works by sending data across the loop until it reaches the destined device, using other devices along the loop to forward the data. Interestingly, a device will only send received data from another device in this topology if it does not have any to send itself. If the device happens to have data to send, it will send its own data first before sending data from another device.

Because there is only one direction for data to travel across this topology, it is fairly easy to troubleshoot any faults that arise. However, this is a double-edged sword because it isn't an efficient way of data travelling across a network, as it may have to visit many multiple devices first before reaching the intended device.

Lastly, ring topologies are less prone to bottlenecks, such as within a bus topology, as large amounts of traffic are not travelling across the network at any one time. The design of this topology does, however, mean that a fault such as cut cable, or broken device will result in the entire networking breaking.

![[ring-topology.excalidraw|100%]]

## References

- _TryHackMe_. (2021, July 10). <span class="reference-title">Intro to LAN: Introducing LAN Topologies</span>. [https://tryhackme.com/room/introtolan](https://tryhackme.com/room/introtolan)

## See Also

- [[bus-topology|Bus Topology]]
- [[star-topology|Star Topology]]
