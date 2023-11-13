## docker compose 说明



## 目录说明 

> conf    		  # 放置nginx.conf 配置文件 不用修改
>
> conf.d  		  # 放置 default.conf 默认配置文件 【自定义配置文件放在此处】
>
> html    		  # 放置默认静态文件
>
> logs    		  # 放置nginx日志文件
>
> ssl     		  # 放置ssl证书文件
>
> nginx-linux.yaml  # linux 环境下 compose文件
>
> nginx-win.yaml	# window 环境下 compose文件

## 操作说明 

### linux 环境

> 1、把当前nginx整个文件夹复制到linux服务器home目录下
>
> 2、nginx所在目录执行 `docker compose -f nginx.yaml up -d` 命令启动 nginx

```shell
docker compose -f nginx-linux.yaml up -d
```

### window 环境

> 1、、nginx所在目录执行 `docker compose -f nginx-win.yaml up -d` 命令启动 nginx

```shell
docker compose -f nginx-win.yaml up -d
```

### 
