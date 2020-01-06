# tiryoh/alpine-texlive-ja

[![Docker Automated build](https://img.shields.io/docker/automated/tiryoh/alpine-texlive-ja.svg)](https://hub.docker.com/r/tiryoh/alpine-texlive-ja/)
[![Docker Image Size](https://images.microbadger.com/badges/image/tiryoh/alpine-texlive-ja.svg)](https://microbadger.com/images/tiryoh/alpine-texlive-ja "Get your own image badge on microbadger.com")

Minimal TeX Live image with Japanese font based on alpine

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


This project is based on [Paperist/docker-alpine-texlive-ja](https://github.com/Paperist/docker-alpine-texlive-ja), released under the [MIT License](https://github.com/Paperist/docker-alpine-texlive-ja/blob/2c21cd26e049c040d879ac5686b99514851916a4/LICENSE).

```
The MIT License (MIT)
Copyright (c) 2016 Kaito Udagawa
Copyright (c) 2016-2018 3846masa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
