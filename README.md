# go-devcontainer
## 使い方
このディレクトリをクローンし、`go-devcontainer` ディレクトリに入ります。

`ctrl` + `shift` + `p` > "Open Folder in Container"

## Tips
`devcontainer.json` の `runArgs`

|オプション|説明|
|:--|:--|
|`--cap-add`|Linux ケーパビリティの追加|
|`--security-opt seccomp=undefined`|コンテナに対するseccomp制限を無効化|


## 参考
[Docker 向け Seccomp セキュリティプロファイル](https://matsuand.github.io/docs.docker.jp.onthefly/engine/security/seccomp/)