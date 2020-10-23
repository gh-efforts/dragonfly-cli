# Dragonfly CLI

## Download

The excutable binary is downloadable via [release](https://github.com/diancun/dragonfly-cli/releases) page.

## Usage

### Push a local image

```shell
./dragonfly push -i [image name] -s local
```

### Push a Docker Hub image

```shell
./dragonfly push -i mysql:5.7
```

### Pull image

```shell
./dragonfly pull -c QmfBWHb5857UzBQfPaYJBeFL7A66ZZGzJPkyC4LcUdtCCs
```

**All downloaded `.tar` file will saved `/tmp` directory by default.**

## WebUI

https://dragonfly.diancun.net/
