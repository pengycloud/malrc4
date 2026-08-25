# Malrc4
This is a showcase of a malware that uses RC4 encryption to encrypt the contents of a file with the specified key and rewrites the file with the encrypted bytes. "encrypt.c" and "decrypt.c" can both be used to encrypt or decrypt file.txt because that's how rc4 encryption and decryption logic works. And so both are the same with just different filenames.
## Build
```
git clone https://github.com/pengycloud/malrc4.git
cd malrc4
gcc encrypt.c -o encrypt
gcc decrypt.c -o decrypt
```
## Usage
To encrypt file.txt:<br>
`./encrypt`\
To decrypt file.txt:<br>
`./decrypt`
## Showcase
Compiling it.\
![](https://github.com/pengycloud/malrc4/blob/main/screenshots/gcc.png)<br><br>
Test for encryption and decryption.\
![](https://github.com/pengycloud/malrc4/blob/main/screenshots/test.png)
## ⚠️Disclaimer
### This is for Educational purposes only!
