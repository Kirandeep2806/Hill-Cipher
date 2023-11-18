# Hill Cipher

The repo contains **Hill Cipher Encryption and Decryption**

It allows to encrypt the text using the Hill Cipher technique, and decryption can as well. Checkout the snippets below.

```python
import hillcipher as hc

key = [[17,17,5],[21,18,21],[2,2,19]]
text = "PAY MORE MONEY"

enc = hc.encrypt(text, key)
dec = hc.decrypt(enc, key)

print(enc, dec)
```

The _2`<sup>`nd`</sup>` parameter_ (i.e., **key**) is optional and can be excluded, but ensure that the alphabets count in the input string are the multiples of 3.

```python
import hillcipher as hc

text = "PAY MORE MONEY"

enc = hc.encrypt(text)
dec = hc.decrypt(enc)

print(enc, dec)
```
