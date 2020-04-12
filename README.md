# Gitlab-docker

使用Docker建立Gitlab Server 及Gitlab Runner。

# Running
#### 1. 啟動Gitlab Server
```
docker-compose up -d
```
#### 2. 啟動Gitlab Runner
```sh
runner-tool start {Runner Name}
```
#### 3. 註冊Gitlab Runner
```sh
runner-tool register {Runner Name}
```
#### 4. 棄用Gitlab Runner 
```sh
runner-tool drop {Runner Name}
```
#### 5. 進入Gitlab Runner 容器
```sh
runner-tool exec {Runner Name}
```
