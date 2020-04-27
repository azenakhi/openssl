# openssl
## Generate ECDSA Private and Public Key
```bash
openssl ecparam -genkey -name secp521r1 -noout -out /tmp/ecdsa-key.pem
openssl ec -in /tmp/ecdsa-key.pem -pubout -out /tmp/ecdsa-public.pem
```
