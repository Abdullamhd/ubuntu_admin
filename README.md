Server Adminstration 
---

## Installing SSH Keys in remote server . 

1- Generate A Key 

```
ssh-keygen

```

```bash

cat ~/.ssh/id_rsa.pub | ssh abdullah@IP_ADDRESS "mkdir -p ~/.ssh && cat >> ~/.ssh/authorized_keys"

```

---

