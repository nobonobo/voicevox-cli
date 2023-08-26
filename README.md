# voicevox-cli

CLI for [VOICEVOX](https://voicevox.hiroshiba.jp).

## install

```shell
> go install github.com/nobonobo/voicevox-cli@latest
```

## usage

prerequired:

```shell
docker run -d -p 50021:50021 voicevox/voicevox_engine:cpu-ubuntu20.04-0.10.4
```

example:

```shell
> voicevox-cli -speaker=0 -style=0 "こんにちは"
main.go:170: 四国めたん ノーマル 2
```
