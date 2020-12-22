# gossip_test
## Description

In order to prove the efficiency of gossip protocol, a python(3) code has been developed to complete with high probability and fault tolerance in which each node (Node5000, Node5010, Node5020, Node5030, Node5040) sends out some data to a set of other nodes. The message is propagated and communicate through the system node by node like a virus.

Program uses Socket programming, protocol UDP to send(sendto) and recieve(recvfrom) data from different nodes that are the base classes of this Gossip namely Nodexyz. It uses Object-Oriented features of creating multiple instances of something with common properties. For continuously receiving and sending data between different nodes, two threads have been used, which makes the test multithreading.
