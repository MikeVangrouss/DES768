# DES768 Encryption Cipher
Data Encryption Standard Encryption Cipher 768 bits

DES uses 56-bit keys. However, the internal keys are much larger. The DES uses the 56-bit key to generate the 16 * 48-bit subkeys, or 768 bits. The 56-bit limitation of the key is artificial, so it can be enlarged up to 768 bits. In 2014 the DES-768 was released, it uses the same principle as the DES but the 16 subkeys are generated by a one-way hash function. The result is an algorithm that works at the same speed as the DES but with a 768-bit key. The same is true for Triple DES with independent subkeys, which results in a 2304-bit key. Note that weak keys do not exist in DES-768, nor in Triple DES-2304 since subkeys are generated by a one-way hash function. 
