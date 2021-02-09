# ceaser.py
Julius Ceaser Encryption Algorithm

Julius Ceasar, the Roman statesman, used to protect the messages he sent to his generals by encrypting them using a cipher. A Caesar cipher shifts each letter by a number of letters. For example, if you shift the letter a by three, then you get the letter d, and so on.

If the shift goes beyond the end of the alphabet, then you just need to rotate back to the beginning of the alphabet. In the case of a rotation by three, x would become a. Here’s how the alphabet would look after the rotation:

Original alphabet: abcdefghijklmnopqrstuvwxyz
Alphabet rotated by three: defghijklmnopqrstuvwxyzabc
The following code implements rotate_chr(), a function that takes a character and rotates it by three. rotate_chr() will return the rotated character. Here’s the code:

Basically we are using ord() and chr() to achieve this; 
ord ---> Returns the integer ordinal of a one-character string.
chr ---> Returns the character, basically inverse of ord()

Hope you enjoy it, I was inspired by https://realpython.com/python-map-function/ to do this as I love changing, tweaking a few things.
There is never a direct and one method in Python>>>
Enjoy >>>>>>>>
