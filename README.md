## Chord-
Chord Protocol is a scalable lookup protocol for peer-to-peer networks. In this project I have simulated a network of multiple peer systems which use chord protocol for disseminating the data over the network. The algorithm provides structured distributed hash tables for hoping the data to the correct node. Chord uses consistent hashing for this specific operation. Chord protocol assigns each ip address of node and file key an identifier using a Consistent hashing. A finger table / routing table is created at each node which provides the ip of the correct node.

# Stack used
The protocol have been implemented in F#. For similating multiple active node working concurrently Actor-model is used.
