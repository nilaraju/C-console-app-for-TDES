ALGORITHM:
Triple Data Encryption Standard (DES) is a type of computerized cryptography where block cipher algorithms are applied three times to each data block. The key size is increased in Triple DES to ensure additional security through encryption capabilities. Each block contains 64 bits of data. Three keys are referred to as bundle keys with 56 bits per key
Triple DES uses a “key bundle” comprising three DES keys, K1, K2, and K3, each of 56 bits (excluding parity bits). The encryption algorithm is:
ciphertext = EK3(DK2(EK1(plaintext)))
i.e., DES encrypt with K1, DES decrypt with K2, then DES encrypt with K3.
 
Decryption is the reverse:
plaintext = DK1(EK2(DK3(ciphertext)))
i.e., decrypt with K3, encrypt with K2, then decrypt with K1.

ENCRYPTION:
In Encryption, 
•	DES encrypt with K1
•	DES decrypt with K2
•	DES encrypt with K3
DECRYPTION
In decryption,
•	DES decrypt with K3
•	DES encrypt with K2
•	DES decrypt with K1
