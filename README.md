In this repository, I implemented the CSMA/CD protocol. CSMA/CD, which stands for Carrier Sense Multiple Access with Collision Detection, 
is a protocol used by computer Ethernet networks. In this protocol, any device that has a packet to send first checks if there are any packets on the network to avoid collisions. 
However, there is a possibility of collision when one node sends a packet to the network and another node (possibly far from the aforementioned node) starts sending a packet 
because there were no packets when it sensed the cable due to physical distance and propagation delay. In this case, after a while, both nodes sense the collision and stop sending packets.
Then, each node waits for a random amount of time (backoff time), and the process repeats again.

Feel free to change the variables of the program and observe the network efficiency under different conditions
