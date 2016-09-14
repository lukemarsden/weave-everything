# Building AMI

Install packer from packer.io

Run:
```
packer build -var 'aws_access_key=YOUR ACCESS KEY' \
    -var 'aws_secret_key=YOUR SECRET KEY' \
    ami.json
```
