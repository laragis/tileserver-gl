# TileServerGL


## Setup

```shell
sudo apt update \
    && wget http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu66_66.1-2ubuntu2_amd64.deb \
    && sudo dpkg -i libicu66_66.1-2ubuntu2_amd64.deb 
    && rm -rf libicu66_66.1-2ubuntu2_amd64.deb
yarn install
node .
```