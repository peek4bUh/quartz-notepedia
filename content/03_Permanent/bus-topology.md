---
title: Bus Topology
parent: "[[computing-moc]]"
language: english
tags:
  - permanent
---


The **bus topology** is a type of connection relies upon a single connection which is known as a backbone cable. Is similar to the leaf off of a tree in the sense that devices (leaves) stem from where the branches are on this cable.

Because all data destined for each device travels along the same cable, it is very quickly prone to becoming slow and bottlenecked if devices within the topology are simultaneously requesting data. This bottleneck also results in very difficult troubleshooting because it quickly becomes difficult to identify which device is experiencing issues with data all travelling along the same route.

Bus topologies are one of the easier and more cost-efficient topologies to set up because of their expenses, such as cabling or dedicated networking equipment used to connect these devices.

Lastly, another disadvantage of the bus topology is that there is little redundancy in place in case of failures. This disadvantage is because there is a single point of failure along the backbone cable. If this cable were to break, devices can no longer receive or transmit data along the bus.

![[bus-topology.excalidraw|100%]]

## References

- TryHackMe. (2021, July 10). <span class="reference-title">Intro to LAN: Introducing LAN Topologies</span>. [https://tryhackme.com/room/introtolan](https://tryhackme.com/room/introtolan)
- https://www.elprocus.com/bus-topology-in-computer-networks/

## See Also

- [[ring-topology|Ring Topology]]
- [[star-topology|Star Topology]]
