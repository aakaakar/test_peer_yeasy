Hyperledger Fabric Membersrvc
===
Docker images for [Hyperledger](https://www.hyperledger.org) fabric membersrvc.

Note: in fabric 1.0, the membersrvc is decoupled as [farbic-cop](https://github.com/yeasy/docker-hyperledger-fabric-cop).

# Supported tags and respective Dockerfile links

* [`latest` (latest/Dockerfile)](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc/blob/master/Dockerfile): Same with 0.6-dp.
* [`0.6-dp` (0.6-dp/Dockerfile)](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc/blob/0.6-dp/Dockerfile): Use 0.6-developer-preview branch code.

For more information about this image and its history, please see the relevant manifest file in the [`yeasy/docker-hyperledger-fabric-membersrvc` GitHub repo](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc).

If you want to quickly deploy a local cluster without any configuration and vagrant, please refer to [Start hyperledger clsuter using compose](https://github.com/yeasy/docker-compose-files#hyperledger).

# What is docker-hyperledger-fabric-membersrvc?
Docker image with hyperledger fabric membersrvc deployed. 

# How to use this image?
The docker image is auto built at [https://registry.hub.docker.com/u/yeasy/hyperledger-fabric-membersrvc/](https://registry.hub.docker.com/u/yeasy/hyperledger-fabric-membersrvc/).

## In Dockerfile
```sh
FROM yeasy/hyperledger-fabric-membersrvc:latest
```

# Which image is based on?
The image is built based on [hyperledger fabric base](https://hub.docker.com/r/yeasy/hyperledger-fabric-base) image.

# What has been changed?
## install dependencies
Install required  libsnappy-dev, zlib1g-dev, libbz2-dev.

## install rocksdb
Install required  rocksdb 4.1.

## install hyperledger fabric member srvc
Install hyperledger fabric membersrvc 

# Supported Docker versions

This image is officially supported on Docker version 1.7.0+.

Support for older versions (down to 1.0) is provided on a best-effort basis.

# Known Issues
* N/A.

# User Feedback
## Documentation
Be sure to familiarize yourself with the [repository's `README.md`](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc/blob/master/README.md) file before attempting a pull request.

## Issues
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc/issues).

You can also reach many of the official image maintainers via the email.

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/yeasy/docker-hyperledger-fabric-membersrvc/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
