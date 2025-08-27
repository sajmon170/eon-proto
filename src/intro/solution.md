# The solution

We propose a new protocol for distributed communication. It inverts most of
the current WWW-based applications' assumptions. In particular:
- it does away with client-server architecture in favor of distributed P2P
- data is distributed on end-user devices, not on centralized servers
- all user traffic is end-to-end encrypted by default
- users are the content providers, not servers
- users store sensitive data on their own devices, not on external servers
- the network allows dynamic content delivery without the use of external CGI
tools
- UI data processing is done on end user devices, not on centralized servers.

While the WWW created primitives for static content delivery the proposed
network architecture creates primitives for dynamic content delivery. This is
achived though a system of object and tags, which can be effectively added to
the network thanks to a hybrid Kademlia-Gossipsub overlay network.
