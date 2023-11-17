## docker compose 说明



## 目录说明 

> env 			     # 配置文件
>
> image 			   # 镜像配置
>
> mysql-8-linux.yaml   # linux 环境下 compose文件
>
> mysql-8-win.yaml	 # window 环境下 compose文件

## 操作说明 

### linux 环境

> 单机部署
>
> 1、mysql所在目录执行 `docker compose -f mysql-8-linux.yaml up -d` 命令启动 nginx

```shell
docker compose -f mysql-8-linux.yaml up -d
```

### window 环境

> 单机部署
>
> 1、mysql所在目录执行 `docker compose -f mysql-8-win.yaml up -d` 命令启动 nginx

```shell
docker compose -f mysql-8-win.yaml up -d
```
