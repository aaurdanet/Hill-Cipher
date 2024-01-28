Hill Cipher Encryption

This code implements the Hill cipher algorithm to encrypt a plaintext file using a keytext file. The Hill cipher is a substitution cipher based on linear algebra, where the encryption involves matrix multiplication.
Author

    Antonio Urdaneta


Compilation

To compile the code, use the following commands based on the programming language:
C

bash

gcc -o HillCipher HillCipher.c
./HillCipher kX.txt pX.txt


Input Files

    kX.txt: Keytext file containing the key for encryption.
    pX.txt: Plaintext file to be encrypted.

Note

    All input files are expected to contain simple 8-bit ASCII characters.
    The code assumes that the key and plaintext files are correctly formatted and accessible.
    The execution commands have been tested on Eustis.

How to Run

    Provide the keytext file (kX.txt) and plaintext file (pX.txt) as command-line arguments.
    The program will read the keytext file, extract the key matrix, and then encrypt the plaintext using the Hill cipher.
    The result will be displayed as the ciphertext.

Example

bash

./HillCipher kX.txt pX.txt

Output

    The Key Matrix is displayed.
    The original Plaintext is displayed.
    The resulting CipherText is displayed.
