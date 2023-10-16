# TileServerGL


## Setup

```shell
sudo apt update \
    && wget http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu66_66.1-2ubuntu2_amd64.deb \
    && sudo dpkg -i libicu66_66.1-2ubuntu2_amd64.deb 
    && rm -rf libicu66_66.1-2ubuntu2_amd64.deb

sudo apt-get -y --no-install-recommends install \
      build-essential \
      ca-certificates \
      wget \
      pkg-config \
      xvfb \
      libglfw3-dev \
      libuv1-dev \
      libjpeg-turbo8 \
      libicu66 \
      libcairo2-dev \
      libpango1.0-dev \
      libjpeg-dev \
      libgif-dev \
      librsvg2-dev \
      gir1.2-rsvg-2.0 \
      librsvg2-2 \
      librsvg2-common \
      libcurl4-openssl-dev \
      libpixman-1-dev \
      libpixman-1-0

yarn install
node .
```