# AWS AMI for CSYE 6225

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| Shubhankar Dandekar| 001439467| dandekar.s@husky.neu.edu |
| Jayesh Iyer|001472726 | iyer.j@husky.neu.edu|
| Mitali Salvi|001630137  | salvi.mi@husky.neu.edu|
| Neha Gaikwad|001886361 |gaikwad.n@husky.neu.edu |
 
## Validate Template

```
packer validate centos-ami-template.json
```

## Build AMI
Run below script...
```
packer build \
    -var 'aws_region=us-east-1' \
    centos-ami-template.json
```
