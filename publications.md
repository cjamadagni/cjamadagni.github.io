---
layout: page
title: Publications
---


### [Dynamic 3D Graph Visualizations in Julia](http://dl.acm.org/citation.cfm?id=3015595)  
A major problem with graph visualization libraries and packages is the lack of interactivity and 3D visualization. This makes understanding and analyzing complex graphs and topologies difficult. Existing packages and tools which do provide similar functionality are difficult to use, install, integrate and have many dependencies. This paper discusses NetworkViz.jl, a Julia package which addresses the issues of existing graph visualization platforms while ensuring simplicity, efficiency, a diverse set of features and easy integration with other packages. This package supports two- and three-dimensional visualizations and uses a force-directed graph drawing approach to generate aesthetically pleasing and easy-to-use graphs. The library was built entirely in Julia due to its good documentation, large open source community and in order to fully utilize the inherent advantages provided by the language. As graph visualizations are important for analyzing complex networks, testing routing algorithms, as teaching aids, etc., we believe that NetworkViz.jl will be of integral use in the fields of research and education.



### [VirtTorrent: BitTorrent for Inter-VM File Distribution](http://dl.acm.org/citation.cfm?id=3015595)
A major problem in virtualized cloud datacenters today is the inefficiency of communication between virtual machines, i.e. inter-VM communication. Efforts have gone into optimizing communication between VMs present on the same physical server in the cloud, i.e. co-resident or co-located VMs; however, optimizing communication between VMs present on different physical servers is a separate issue. As these communicate via the TCP/IP network stack, improvements in performance or efficiency are normally proposed by customizations to the communication protocols requisite to the datacenter. We propose a mechanism to increase the average speed of inter-VM file distribution in the cloud for VMs on separate physical servers by implementing a BitTorrent-like peer-to-peer (P2P) system. The proposal, named VirtTorrent, uses direct communication between VMs in the cloud to implement a protocol similar to BitTorrent, allowing files to be distributed swiftly and with minimal network congestion. As inter-VM communication and network congestion are both important issues in the datacenter, we believe that VirtTorrent can make a marked improvement in the scenarios laid out in this paper.
