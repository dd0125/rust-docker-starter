# rust ビルド

```
docker exec rust-docker-starter-rust bash -c "cd /opt/src/ && rustc sample.rs"
```
そのままビルドした場合、その環境で動くバイナリが生成される。
WindowsやMacなど別環境で動かしたい場合は、rustc に対して、target を設定する。

# 実行

```
docker exec rust-docker-starter-rust bash -c "/opt/src/sample"
```

