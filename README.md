# NaiveProxy  一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/naiveproxy.sh && bash naiveproxy.sh
```
## 源项目
- https://github.com/klzgrad/naiveproxy


# Hysteria 2  一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/hysteria.sh && bash hysteria.sh
```
## 源项目
- https://github.com/apernet/hysteria



# TUIC v5    一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/tuic5.sh && bash tuic5.sh
```
## 源项目
- https://github.com/EAimTY/tuic


# ARGOX     一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/argox.sh && bash argox.sh
```
## 源项目
- https://github.com/fscarmen/ArgoX


# JUICITY   一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/juicity.sh && bash juicity.sh
```
## 源项目
- https://github.com/juicity/juicity
### nekobox配置方法 
##### 在手动配置节点处，类型选择“自定义（其他核心）”，输入节点名称，服务器 IP 地址及端口号，核心选择 Juicity，命令设置成 run -c %config%，后缀设置为 json。在下方配置处将脚本生成的 CLI 客户端配置文件复制到里面，然后修改 listen 字段为 127.0.0.1:%socks_port%，server 字段为 %server_addr%:%server_port%，然后点击确定保存即可
![Image text](https://raw.githubusercontent.com/voyku/naiveproxy/main/img/nekojuicity.jpg)


# MIERU   一键配置脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/voyku/naiveproxy/main/mieru.sh && bash mieru.sh
```
## 源项目
- https://github.com/enfein/mieru
## 下载客户端
- https://github.com/enfein/mieru/releases/tag/v2.1.0
### 客户端配置方法 
##### 在其目录下，创建一个名为client_config.json的文件 ，在当前目录打开PowerShell命令行，然后输入命令 ./mieru apply config client_config.json ，然后输入 ./mieru start
![Image text](https://raw.githubusercontent.com/voyku/naiveproxy/main/img/mieru.jpg)
### nekobox配置方法
##### nekobox配置一个socks节点
![Image text](https://raw.githubusercontent.com/voyku/naiveproxy/main/img/nekomieru.jpg)

