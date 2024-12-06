# badnotes

## Challenge 
This is our *ctf - challenge*! The flag is a message to decrypt containing a magic number. There is a *sender* that encrypt a message *m* with two different public keys using RSA algorithm and sends them to the *receiver*. Your role as attacker is to act as *man-in-the-middle*: once you found the ciphertexts try to recover *m* (without deriving the private keys).  

## Instructions
- clone the repository
- extract the folder from rsa_project.rar
- open the directory from the CLI
- run ```docker-compose up --build sender receiver tcpdump```
- have fun

## Hints
- You can look up every folders in rsa_project except for `receiver` and `sender` folders (please don't do that)
- Bezout's identity

