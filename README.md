# cis-ubuntu-packer
### What's this? 
####  This project packs a "Center for Itnernet Security" benchmark hardened Ubuntu image for Google Compute Engine
`CIS Hardened Ubuntu Image`
1. Edit the file: packer.json
1. Authenticate / get a JWT token for Gcloud
```sh
gcloud auth application-default login
```
1. Pack a CIS hardened Ubuntu Image
```sh
packer build ./packer.json
```

---
2019 Gordon Young - gjyoung1974@gmail.com
