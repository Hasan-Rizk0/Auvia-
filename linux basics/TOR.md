
Tor is a decentralized network and privacy tool designed to help you stay anonymous and uncensored while using the internet. 

This process is done by routing your internet traffic through a series of relays.

----------------------------------------------------------------------

Decentralized ---> The system doesn’t rely on a single, central server to handle all your data. Instead, your traffic is dynamically routed through different volunteer-run relays each time you make a connection.

----------------------------------------------------------------------

Nodes and relays are the same. Almost any Computing device that is configured to route Tor traffic and registered with the Tor network (assuming it meets the criteria), it becomes a Tor relay.


--------------------------------------------------------------------------

The TOR network functions the same as a Proxy or a VPN ----> Hides your IP address and gives you anonymity. However, the TOR is often the best one to guarantee the user's  anonymity.


--------------------------------------------------------------------------

How does it work?:

First, the tor client build a circuit with three randomly chosen relays (guard relay, middle relay, exit relay) and make a handshake with each one of them alone to get a common encryption/decryption key. Then, before the user sends the request to the first relay (guard relay) first it encrypts the request with three layers of encryption using the keys of the three relays, then it sends it the guard relay, then the guard relay decrypt using its key the first layer of encryption and pass it to the middle relay which does the same thing to the second layer of encryption and pass it to the third relay which also does the same thing and then send it to the destination. And when the response arrive the exit relay is the first one to take the response it encrypts the response with the first layer of encryption using it own key and pass it to the middle layer then the middle layer adds a layer of encryption using its own key too and pass it to the guard layer then the guard layer add the final layer of encryption and send it to the tor client which decrypts all the layers of security using the keys and send it to the user.
