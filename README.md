# ionic

[ionic](http://ionicframework.com/docs/cli/)用Dockerイメージ

## `Dockerfile` links

- [`0.0.1`,`latest`(Dockerfile)](https://github.com/yamamoto-febc/ionic-cli-docker/tree/master/0.0.1/)

## 使い方

### 起動コマンド書式

```bash
docker run -it --rm -p 8100:8100 -v $PWD:/workdir yamamoto-febc/ionic [オプション]
```

## whalebrewでインストールする場合

このイメージは[whalebrew](https://github.com/bfirsh/whalebrew)でのインストールに対応しています。

### インストール

```bash
$ whalebrew install yamamoto-febc/ionic
```

### 使い方

```bash
$ ionic [オプション]
```
