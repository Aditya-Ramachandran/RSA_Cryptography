[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)



# RSA Cryptography

Implemented a highly secure RSA cryptography algorithm in a server-client socket framework. The client's messages are encrypted on their local machine using a public key and the encrypted data flows to the server where it is decrypted using the generated private key. This code can be used to save your passwords or other confidential data remotely to a server without any worries of it getting hacked.

This is a practical demonstration of the algorithm where every time a socket connection is set up, a new set of pubic,private keys are generated.

The bitlength can be adjusted in the code for desired level of security.
