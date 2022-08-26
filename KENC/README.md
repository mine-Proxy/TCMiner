<div align="center">

# KENC文档说明

</div>

<p id="kenc"></p>

### KENC是本地->远程TC隧道，局域网部署在一台设备上即可，可与远程TCMinerProxy通过KENC协议进行通信。

<a href="https://github.com/mine-Proxy/TCMinerProxy/raw/main/KENC/windows.zip">点击下载WINDOWS客户端</a>

<a href="https://github.com/mine-Proxy/TCMinerProxy/raw/main/KENC/kenc_linux_amd64">Linux客户端AMD64</a>

<a href="https://github.com/mine-Proxy/TCMinerProxy/raw/main/KENC/kenc_linux_arm64">Linux客户端arm64</a>

<a href="https://github.com/mine-Proxy/TCMinerProxy/raw/main/KENC/kenc_arm386">Linux客户端arm386</a>

### LINUX版一键安装
```
bash <(curl -s -L https://raw.githubusercontent.com/mine-Proxy/TCMinerProxy/main/KENC/k-install.sh)
```

### 使用环境
```
TCMinerproxy版本>=2.1.0
```

## 使用说明

### 1.远程TCminerproxy先配置一个KENC协议的端口

<img src="./../image/t14.png" alt="Logo" width="300">

### 2.在TC的设置页面找到KENC配置推送, 如下图
<img src="./../image/kenc.png" alt="Logo">

### 3. KENC客户端首次打开, 或点击右上角设置, 即可更改配置推送地址, 配置设置完毕后重启KENC客户端即可拉取最新配置。
