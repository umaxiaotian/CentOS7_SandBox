# Docker-CentOS7-Sandbox
  Docker上で動作するCentOSのサンドボックスです。
docker-compose.ymlがある位置のshellフォルダは、コンテナ内の/shellと繋がっており、ファイルのやり取りが可能です。

## SSHを使用する場合
```
USER:root
PASS:password
HOST:localhost
```

![image](https://user-images.githubusercontent.com/29545778/169651057-29b2fc93-f9dd-43af-8e45-4aade86f6e02.png)
