#  简单配置

### 下载项目

```
git clone https://github.com/chukangkang/clash.git
cd clash 
chmod +x abc
```



### 下载mmdb

```
rm -rf ~/.config/clash && mkdir -p ~/.config/clash
cp Country.mmdb ~/.config/clash/

```

### 启动代理

```
./abc -f hk.yaml
```

### yaml 配置模板

>默认端口： 443  按需修改
>
>默认域名：域名 全局替换
>
>默认密码： 123456 按需修改

### 代理设置

```
#全局代理
#export http_proxy="http://127.0.0.1:7890"
export https_proxy="http://127.0.0.1:7890"

#取消代理
unset http_proxy
unset https_proxy
```

