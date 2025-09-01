### vmess
workspace 、 Docker 、 jupyterlab 、 Private 、 JUPYTER_TOKEN
```bash
bash <(curl -l -s https://raw.githubusercontent.com/docker-gb/huggingface.co/refs/heads/main/test.sh)
```

### -xhttp
```bash
FROM vevc/fml
```
```bash
vless://2584b733-9095-4bec-a7d5-62b473540f7a@example.com:443?encryption=none&security=tls&fp=chrome&type=xhttp&path=%2F&mode=auto#hf-xhttp
```
workspace 、 Docker 、 Blank 、 Public <div>
create the Dockerfile<div>
Dockerfile：FROM vevc/fml<div>

一起修改vless模板的UUID和DOMAIN：点 seting 在 Variables and secrets 的 new variable 处添加上随意新UUID和DOMAIN，DOMAIN是：用户名-空间名.hf.space，也是vless的：地址（adress）

关于保活：需要每48小时至少有一次流量，使用此vless登入v.com，输入：cat /tmp/keepalive.log，显示400保活成功。










