Playfair, Hill, and Vigenère Ciphers

This repository contains Python implementations of three classical encryption techniques:

Playfair Cipher

Hill Cipher

Vigenère Cipher

These ciphers are used for encrypting and decrypting text-based messages. Below is an overview of each cipher and how to use the provided implementation.

Ciphers Overview

1. Playfair Cipher

The Playfair Cipher is a digraph substitution cipher that encrypts text by pairing letters and replacing them using a 5x5 key matrix.

Key Features:

Uses a 5x5 matrix of letters

Replaces letter pairs using predefined rules

Eliminates the letter 'J' and replaces it with 'I'

2. Hill Cipher

The Hill Cipher is a polygraphic substitution cipher that uses matrix multiplication to encrypt plaintext.

Key Features:

Uses linear algebra for encryption

Requires an invertible key matrix

Works on blocks of text instead of single letters

3. Vigenère Cipher

The Vigenère Cipher is a polyalphabetic substitution cipher that uses a repeating key to shift letters.

Key Features:

Uses a repeating key for shifting letters

Resistant to frequency analysis

Simple encryption and decryption process
