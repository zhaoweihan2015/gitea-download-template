# gitea-download-template
一个测试能用的docker部署的gitea服务，为了无外网环境下通过局域网完成git合作开发

#### 开启服务

```cmd
docker compose up -d
```

#### 查看服务日志

```cmd
docker compose logs
```

#### 查看当前开启的服务

```cmd
docker ps
```

#### 关闭所有服务

```cmd
docker stop $(docker ps -q)
```

