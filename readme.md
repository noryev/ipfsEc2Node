# ipfs EC2 Desktop Node


## Setup

Instance type: t2.micro

// add commands for setup

Setup an ipfs Desktop node in a few different configurations on an AWS EC2 Node

All of my instructions will be done using SSH [EC2 Instance Connect and Session Manager coming later]


## Advanced Configurations with Amazon Elastic File System (EFS)

Setup Guide-

## Validation and Tests

- add dashboard information here

## Sources that helped you- 

https://medium.com/textileio/tutorial-setting-up-an-ipfs-peer-part-i-de48239d82e0

- wget https://dist.ipfs.io/go-ipfs/v0.4.15/go-ipfs_v0.4.15_linux-amd64.tar.gz
- tar xvfz go-ipfs_v0.4.15_linux-amd64.tar.gz
- rm go-ipfs_v0.4.15_linux-amd64.tar.gz 
- sudo mv go-ipfs/ipfs /usr/local/bin
- rm -rf go-ipfs
