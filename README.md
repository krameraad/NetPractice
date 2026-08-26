*This project has been created as part of the 42 curriculum by ekramer.*


# NetPractice
An exercise in *computer networking*. This project is practice for
configuring IP addresses, connecting devices through a router,
and understanding the role of gateways within networks.

The goal is to configure 10 small networks and submit them in this repository.


## Instructions
This repository contains the solutions for my configuration of exercises.
Though checked by a *Moulinette*, they're not relevant during evaluations.

To perform the evaluation,
download the `net_practice.tgz` package from *Intra*.
Unpack and navigate to the `net_practice` folder.
Here, run `run.sh` to launch a web server and open the interface in a browser.


**NetPractice** will open on the *training* tab.
Enter your login to get your personal exercise configuration.
The *evaluation* tab generates random configurations.

There are multiple levels to **NetPractice**.
A broken *network diagram* must be fixed on each level,
by adjusting the available configuration.
The `Check again` button verifies the configuration.
`Get my config` exports the configuration to a JSON file,
necessary for submitting the assignment.


## Resources
[This article](https://medium.com/@imyzf/netpractice-2d2b39b6cf0a)
on Medium explained some of the important concepts of networking.

There were also
[various](https://github.com/ricardoreves/42-net-practice)
[guides](https://github.com/caroldaniel/42sp-cursus-netpractice)
for the project made by other students that I found helpful.
Besides that, fellow students and AI helped me with some of the exercises.

Doing an evaluation on NetPractice gave me some insight on the basics.

### Terminology
- **TCP/IP addressing**: A system for identifying devices on a network and enabling them to communicate using IP addresses and TCP/IP protocols.
- **Subnet masks**: Define which portion of an IP address identifies the network and which portion identifies the device (host).
- **Default gateways**: The device, typically a router, that forwards traffic from a local network to other networks.
- **Routers and switches**: Routers connect different networks and direct traffic between them; switches connect devices within the same network and forward traffic to the appropriate device.
- **OSI layers**: A seven-layer model that describes how network communication works, from physical transmission of data (Layer 1) to applications (Layer 7).
