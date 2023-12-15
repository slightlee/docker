## docker compose 说明

### 文件夹说明

>env   配置文件
>
>image 镜像配置
>
>nacos 文件配置
>
>mysql 单独mysql容器部署配置
>
>nginx 单独nginx容器部署配置

### 1、standalone-nacos-mysql-8-*.yaml

> 【单机部署】同时创建mysql以及nacos容器、初始化数据库脚本，适用于window、linux 环境下compose文件
>
> standalone-nacos-mysql-8-linux.yaml【适用于linux 环境】
>
> standalone-nacos-mysql-8-win.yaml  【适用于window环境】

### 2、standalone-nacos-*.yaml

> 【单机部署】只创建nacos容器【前提 mysql已经安装、数据已经导入】
>
>  standalone-nacos-linux.yaml 【适用于linux 环境】
>
>  standalone-nacos-win.yaml   【适用于window环境】

### 3、nginx compose 文件

> nginx/nginx-linux.yaml        # linux 环境下 compose文件
>
> nginx/nginx-win.yaml          # window 环境下 compose文件

### 4、mysql compose 文件

> mysql/mysql-8-linux.yaml      # linux 环境下 compose文件
>
> mysql/mysql-8-win.yaml	# window 环境下 compose文件