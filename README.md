# AES
AES
program will read parameters, key, plaintext and ciphertext from a file named “input.txt” 
Then program creates a file named “output.txt” and writes the encryption and decryption results to “output.txt”. 
Input file details are :
1. First line is the coefficients of an irreducible polynomial m(x) (degree is 8) over Z2, from the leading coefficient to the constant term, separated by one blank space.
2. Second line is the key (in hexadecimal format, 32 digits, without blank space).
3. Third line is the plaintext (in hexadecimal format, 32 digits, without blank space).
4. Fourth line is the ciphertext (in hexadecimal format, 32 digits, without blank space).
In “output.txt”:
1. First line is the ciphertext (encryption result of the plaintext in input.txt).
2. Second line is the plaintext (decryption result of the ciphertext in input.txt).
