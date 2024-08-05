CAESAR CIPHER ENCRYPTION AND DECRYPTION

Overview

The Caesar Cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. This method was named after Julius Caesar, who used it in his private correspondence.

How It Works

The Caesar Cipher works by shifting the position of each letter in the plaintext by a fixed number of places determined by the shift value. For example, with a shift of 3:

A becomes D

B becomes E

C becomes F

and so on...

If the shift moves past the end of the alphabet, it wraps around to the beginning. For example, with a shift of 3:

X becomes A

Y becomes B

Z becomes C

The same shift value used for encryption can be used in reverse to decrypt the message.

Features

Encrypt Text: Convert plaintext into ciphertext by shifting the characters.

Decrypt Text: Convert ciphertext back into plaintext using the same shift value.

Case Sensitivity: Maintains the case of the original text (i.e., uppercase and lowercase letters are treated separately).

Non-alphabetic Characters: Leaves non-alphabetic characters (e.g., spaces, punctuation) unchanged.

How to Use

Encrypt a Message:

Input the message you want to encrypt.

Provide a shift value (integer) to determine the number of positions each character will be shifted.

The program outputs the encrypted message.

Decrypt a Message:

Input the message you want to decrypt.

Provide the same shift value used for encryption.

The program outputs the decrypted message.
