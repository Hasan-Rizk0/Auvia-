
SSH (Secure Shell) it is a protocol used to secure the connection between two devices by encrypting the exchanged data between the two devices.

SSH works on top of TCP (standard)

TCP is a protocol that makes the connection between two devices reliable but not secure.

How does it work?:

First, a TCP connection is established. After that, the SSH client and server negotiate encryption keys using a key exchange algorithm (like Diffie-Hellman or Curve25519), exchanging only public values (k) (never private secrets). This key exchange creates a shared session key used for encrypting all further communication.

Once the secure channel is established, authentication occurs—either by sending a password (encrypted) or by proving ownership of a previously generated SSH key pair (public/private keys). Finally, all data exchanged between the two devices is encrypted using the session key for the rest of the connection.

-----------------------------------------------------------------------

IMPORTANT NOTE:

***The session key is used for encryption and it is generated every time the SSH connection occur and the SSH key (public/private) is used to prove the identity.