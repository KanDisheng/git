# Git in Docker

[![Docker Stars](https://img.shields.io/docker/stars/samedocker/git.svg)](https://hub.docker.com/r/samedocker/git/)
[![Docker Pulls](https://img.shields.io/docker/pulls/samedocker/git.svg)](https://hub.docker.com/r/samedocker/git/)
[![Docker Automated Build](https://img.shields.io/docker/automated/samedocker/git.svg)](https://hub.docker.com/r/samedocker/git/)
[![Docker Build Status](https://img.shields.io/docker/build/samedocker/git.svg)](https://hub.docker.com/r/samedocker/git/)
[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-On-blue.svg)](https://hub.docker.com/r/samedocker/git/)
[![Docker Store](https://img.shields.io/badge/Docker%20Store-On-blue.svg)](https://store.docker.com/community/images/samedocker/git)

[![Homepage](https://img.shields.io/badge/Homepage-Go-orange.svg)](http://Git.SameDocker.com)
[![Feedback](https://img.shields.io/badge/Feedback-Go-orange.svg)](https://github.com/SameDocker/Git/issues)
[![GitHub](https://img.shields.io/badge/GitHub-Go-orange.svg)](https://github.com/SameDocker/Git)

## Usage

> [Docker](https://www.docker.com) service is required.

[Book for Docker](http://Docker.BookStorm.cn)

### Install

```bash
$ curl -sSL https://raw.githubusercontent.com/SameDocker/Git/master/install.sh | bash
```

Now you can use Git anywhere.

```bash
$ git init
```

### Uninstall

```bash
$ curl -sSL https://raw.githubusercontent.com/SameDocker/Git/master/uninstall.sh | bash
```

### Update

```bash
$ curl -sSL https://raw.githubusercontent.com/SameDocker/Git/master/update.sh | bash
```

### Advanced Usage

```bash
docker run \
--rm \
--interactive \
--tty \
--name samedocker-git \
--volume "$PWD":/git \
--volume "$HOME":/root \
samedocker/git \
init
```

See [`git.sh`](git.sh) to get more information.

## Contributor

- [Candison November](http://www.kandisheng.com) - Founder
- [Other Contributors](https://github.com/SameDocker/Git/graphs/contributors) - Contributor

## Information

- [Homepage](http://www.SameDocker.com)
- [Feedback](https://github.com/SameDocker/Git/issues)
- [GitHub](https://github.com/SameDocker/Git)