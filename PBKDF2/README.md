```
password: Array of bytes / string for the plain-text password.
salt: Securely-generated random bytes (minimum 64 bits, 128 bits is recommended)
iterations-count: e.g. 1024 iterations
hash-function: For calculating HMAC, e.g. SHA256
derived-key-len: For the output, e.g. 32 bytes (256 bits). The output data is the derived key of requested length (e.g. 256 bits).
```
Refer: `https://thecybersecguru.com/ctf-walkthroughs/mastering-compiled-beginners-guide-from-hackthebox/`
