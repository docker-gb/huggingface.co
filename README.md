-----------------------------------------------------------------------------------------------------------
### vmess
workspace 、 Docker 、 jupyterlab 、 Private 、 JUPYTER_TOKEN 、 CreatSpace 、 terminal
```bash
bash <(curl -l -s https://raw.githubusercontent.com/docker-gb/huggingface.co/refs/heads/main/test.sh)
```
-----------------------------------------------------------------------------------------------------------
### -xhttp
```bash
FROM vevc/fml
```
```bash
vless://2584b733-9095-4bec-a7d5-62b473540f7a@example.com:443?encryption=none&security=tls&fp=chrome&type=xhttp&path=%2F&mode=auto#hf-xhttp
```
<div>workspace 、 Docker 、 Blank 、 Public <div>
<div>create the Dockerfile<div>
<div>Dockerfile：FROM vevc/fml<div>

<div>修改UUID和DOMAIN：点 seting 在 Variables and secrets 的 new variable 处添加上随意新UUID、DOMAIN是：用户名-空间名.hf.space，也是vless的：地址（adress）<div>

<div>关于保活：需要每48小时至少有一次流量，使用此vless登入v.com，输入：cat /tmp/keepalive.log，显示400保活成功。<div>

-----------------------------------------------------------------------------------------------------------

### <div>将 Docker 镜像 vevc/fml 改名为 song 并推送到 GitHub 上的 docker-gb 仓库，按照以下步骤操作：<div>

<div>🛠️ 步骤一：拉取原始镜像<div>
<div>docker pull vevc/fml<div>
<div>🛠️ 步骤二：为镜像重新命名（打标签）<div>
<div>docker tag vevc/fml ghcr.io/docker-gb/song:latest<div>

<div>🛠️ 步骤三：登录 GitHub Container Registry<div>
<div>在 GitHub 的 Developer Settings → Personal Access Tokens 中创建一个具有 write:packages 权限的 token。<div>
<div>https://github.com/settings/tokens<div>
 
<div>echo YOUR_GITHUB_TOKEN | docker login ghcr.io -u YOUR_GITHUB_USERNAME --password-stdin<div>

<div>🛠️ 步骤四：推送镜像到 GitHub<div>
<div>docker push ghcr.io/docker-gb/song:latest<div>
<div> sha256:e2ff49ecd0bfe28e0dbd9529ad80bdd5942cd5e271852dc0570279a1a724d6d3 size: 1789<div>

<div>Github的镜像地址为： ghcr.io/docker-gb/song:last<div>




