# dragonfly

Push and pull to ipFS CLI tool based on golang.

## Usage

### push a local image

```shell
./dragonfly push -i fly-docker -s local
```

### push a dockerhub iamge

**example:**

```shell
./dragonfly push -i mysql:5.7
```

success return cid：`QmfBWHb5857UzBQfPaYJBeFL7A66ZZGzJPkyC4LcUdtCCs`

### pull

```shell
./dragonfly pull -c QmfBWHb5857UzBQfPaYJBeFL7A66ZZGzJPkyC4LcUdtCCs
```

### temporary file

All tar temporary files are stored in `/tmp` directory.

## Web UI

Web: https://dragonfly.diancun.net/

## [releases](https://github.com/diancun/dragonfly-cli/releases)
