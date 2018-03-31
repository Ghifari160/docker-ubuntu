# A Better Ubuntu Image on Docker #
[![Docker Hub: ghifari160/ubuntu](https://img.shields.io/badge/docker%20hub-ghifari160%2Fubuntu-ABD8EB.svg)](https://hub.docker.com/r/ghifari160/ubuntu)
[![](https://images.microbadger.com/badges/image/ghifari160/ubuntu.svg)](https://microbadger.com/images/ghifari160/ubuntu "Get your own image badge on microbadger.com")

Because the official image is lacking.

## Why this image is better than the official image ##
This image adds many utilities that is lacking on the official image.

Added packages:
```
language-pack-en-base
nano
software-properties-common
wget
```

## Installation ##
This image should be used to run a container as a daemon
```
docker run -d ghifari160/ubuntu
```

## Tags ##
| Tags                      | Ubuntu Version | Size              |
|---------------------------|----------------|-------------------|
| `latest` `16.04` `xenial` | 16.04          |[![](https://images.microbadger.com/badges/image/ghifari160/ubuntu.svg)](https://microbadger.com/images/ghifari160/ubuntu "Get your own image badge on microbadger.com")|
| `17.04` `zesty`           | 17.04          | **NOT SUPPORTED** |
| `17.10` `artful`          | 17.10          |[![](https://images.microbadger.com/badges/image/ghifari160/ubuntu:17.10.svg)](https://microbadger.com/images/ghifari160/ubuntu:17.10 "Get your own image badge on microbadger.com")|
