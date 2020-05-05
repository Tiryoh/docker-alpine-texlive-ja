# tiryoh/alpine-texlive-ja

[![Docker Automated build](https://img.shields.io/docker/automated/tiryoh/alpine-texlive-ja.svg)](https://hub.docker.com/r/tiryoh/alpine-texlive-ja/)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/tiryoh/alpine-texlive-ja/latest)](https://hub.docker.com/r/tiryoh/alpine-texlive-ja/tags?page=1&name=latest)
[![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/tiryoh/alpine-texlive-ja/latest)](https://hub.docker.com/r/tiryoh/alpine-texlive-ja/tags?page=1&name=latest)


Minimal TeX Live image with Japanese font based on alpine

Docker tags and build logs are listed on this page.  
https://github.com/Tiryoh/docker_alpine-texlive-ja/wiki

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

## Install

```bash
$ docker pull tiryoh/alpine-texlive-ja
```

## Usage

```bash
$ docker run --rm -it -v $(pwd):/workdir tiryoh/alpine-texlive-ja
$ latexmk -pvc main.tex
```

## Contribute

Contributions are always welcome!

## License

(C) 2020 Daisuke Sato

This repository is released under the MIT License, see [LICENSE](./LICENSE).  
Unless attributed otherwise, everything in this repository is under the MIT License.

### Acknowledgements

This project uses [googlefonts/noto-cjk](https://github.com/googlefonts/noto-cjk), released under the [SIL Open Font License 1.1](https://github.com/googlefonts/noto-cjk/blob/be6c059ac1587e556e2412b27f5155c8eb3ddbe6/LICENSE) by [Google Inc](https://www.google.com/get/noto/help/cjk/).

This project is based on the following projects.  See the LICENSE files of each project for details.

* [Paperist/docker-alpine-texlive-ja](https://github.com/Paperist/docker-alpine-texlive-ja), released under the [MIT License](https://github.com/Paperist/docker-alpine-texlive-ja/blob/2c21cd26e049c040d879ac5686b99514851916a4/LICENSE)
  * Copyright (c) 2016 Kaito Udagawa
  * Copyright (c) 2016-2018 3846masa
* [solareenlo/docker-alpine-texlive-ja](https://github.com/solareenlo/docker-alpine-texlive-ja), released under the [MIT License](https://github.com/solareenlo/docker-alpine-texlive-ja/blob/a75eb10f7fb06258f2b98c3490afe4c355b451e5/LICENSE)
  * Copyright (c) 2016 Kaito Udagawa
  * Copyright (c) 2016-2019 3846masa
  * Copyright (c) 2019 solareenlo
