

what is cryptography algorithm :  A cryptographic algorithm is a set of steps that can be used to convert plain text into cipher text. A cryptographic algorithm is also known as an ****encryption algorithm.**** 
eg : [[Cryptography algorithm in transaction.canvas|Cryptography algorithm in transaction]]

Types of Cryptography :

There are two types of cryptography 
- [[Asymmentric key cryptography.canvas|Asymmentric key cryptography ]]
- [[Symmentric key algorithm.canvas|Symmentric key algorithm]]

Blockchain uses : [[Asymmentric key cryptography.canvas|Asymmentric key cryptography]]

What is Digital Signature ?

[[Digital Signature.canvas|Digital Signature]]

- A digital signature provides validation and authentication like normal signatures
- It ensures security and integrity of data recorded on the blockchain
- It uses asymmentric key cryptography in which the information can be shared using the public key.


Private key : Only know to the key holder, it is used to sign transactions (like a password only user know it).

Public key : By use (Elliptic curve digital signature algorithm- ECSDA) the private key is translated into public key which can be seen by the users around the world to see the transaction.

## Signing the transaction : 

So basically when a user initiates a transaction in the blockchain the private key that ensures the transaction is safe at the same time which is changed by ECDSA and hashed data into public key so other can see the transaction without misusing your private key.

In one word your private key is responsible for both your public key and account address
