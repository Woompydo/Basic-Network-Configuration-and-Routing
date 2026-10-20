This is what we're trying to achieve: a basic network that allows me to send PDUs between computers through a router.

![](img/Ciscores.png)

We will be using the Cisco 2911 router because it is a suitable model for practicing basic routing. We will also use Cisco 2960 switches to connect multiple computers to the network, as the router has a limited number of physical Ethernet interfaces. Finally, we will add two more computers.

![](img/addingphysical.png)

We will use Copper Straight-Through cables to connect the computers to the switches and the switches to the router. First, select the Copper Straight-Through cable, click on a computer, and connect the cable to its FastEthernet0 port. Then, click on the switch and connect the other end to a FastEthernet port, such as FastEthernet0/1. Repeat these steps for the other computers, using a different Ethernet port on the switch for each computer.
