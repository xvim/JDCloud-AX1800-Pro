<img width="768" src="https://github.com/openwrt/openwrt/blob/main/include/logo.png"/>

## 特别提示 [![](https://img.shields.io/badge/-个人免责声明-FFFFFF.svg)](#特别提示-)

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**

- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**

- **我的路由刚好是京东云亚瑟JDCloud AX1800 Pro，我仅构建这个型号的固件！**

- **固件默认地址：192.168.1.1**

- **固件默认用户：root**

- **固件默认密码：password**

## 项目说明 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#项目说明-)

- [LiBwrt](https://github.com/LiBwrt-op/openwrt-6.x)
- [coolsnowwolf](https://github.com/coolsnowwolf/lede)
- [immortalwrt](https://github.com/immortalwrt/immortalwrt)
- [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)
- [haiibo](https://github.com/haiibo/OpenWrt)
- [breeze303](https://github.com/breeze303/openwrt-ci)

- 特别感谢以上大佬！！！！

## 常用插件列表中英文对照

| 插件中文名              | Luci App                       |
| :---------------------- | :----------------------------- |
| 网络向导                | luci-app-quickstart            |
| iStore                  | luci-app-store                 |
| 实时监控                | luci-app-netdata               |
| 释放内存                | luci-app-ramfree               |
| WireGuard 状态          | luci-app-wireguard             |
| ACME 证书               | luci-app-acme                  |
| 自定义命令              | luci-app-commands              |
| Web管理                 | luci-app-webadmin              |
| TTYD 终端               | luci-app-ttyd                  |
| 磁盘管理                | luci-app-diskman               |
| 分区扩容                | luci-app-partexp               |
| ACL 设置                | luci-app-acl                   |
| 高级设置                | luci-app-advanced              |
| 定时重启                | luci-app-autoreboot            |
| Argon 主题设置          | luci-app-argon-config          |
| 文件传输                | luci-app-filetransfer          |
| 关机                    | luci-app-poweroff              |
| 腾讯云DDNS              | luci-app-tencentddns           |
| Docker CE 容器          | luci-app-docker                |
| Docker(Dockerman)       | luci-app-dockerman             |
| Hello World             | luci-app-vssr                  |
| Clash                   | luci-app-clash                 |
| OpenClash               | luci-app-openclash             |
| PassWall                | luci-app-passwall              |
| PassWall2               | luci-app-passwall2             |
| ShadowSocksR Plus+      | luci-app-ssr-plus              |
| Bypass                  | luci-app-bypass                |
| HomeProxy               | luci-app-homeproxy             |
| MihomoTProxy            | luci-app-mihomo                |
| Chatgpt Web             | luci-app-chatgpt-web           |
| V2ray 服务器            | luci-app-v2ray-server          |
| AdGuard Home            | luci-app-adguardhome           |
| 广告屏蔽大师 Plus+      | luci-app-adbyby-plus           |
| iKoolProxy 滤广告       | luci-app-ikoolproxy            |
| 阿里云盘 WebDAV         | luci-app-aliyundrive-webdav    |
| 阿里云盘 FUSE           | luci-app-aliyundrive-fuse      |
| 阿里云盘 WebDAV Go      | luci-app-go-aliyundrive-webdav |
| UA2F防检测              | luci-app-ua2f                  |
| MentoHUST               | luci-app-mentohust             |
| minieap                 | luci-app-minieap               |
| 802.1x 客户端           | luci-app-cd8021x               |
| SYSU H3C Client         | luci-app-sysuh3c               |
| 浮动网关                | luci-app-floatip               |
| 甜糖星愿自动采集        | luci-app-ttnode                |
| DNS 过滤器              | luci-app-dnsfilter             |
| 蒲公英智能组网          | luci-app-pgyvpn                |
| 花生壳内网穿透          | luci-app-phtunnel              |
| 京东签到服务            | luci-app-jd-dailybonus         |
| OSCAM                   | luci-app-oscam                 |
| 易有云文件管理器        | luci-app-linkease              |
| Dufs                    | luci-app-dufs                  |
| DDNSTO 远程控制         | luci-app-ddnsto                |
| 微信推送                | luci-app-serverchan            |
| 全能推送                | luci-app-pushbot               |
| 上网时间控制            | luci-app-accesscontrol         |
| Tailscale               | luci-app-tailscale             |
| 解锁网易云灰色歌曲      | luci-app-unblockmusic          |
| DDNS 阿里               | luci-app-aliddns               |
| DDNS                    | luci-app-ddns                  |
| DDNS-GO                 | luci-app-ddns-go               |
| Lucky                   | luci-app-lucky                 |
| QoS Nftables 版         | luci-app-nft-qos               |
| SmartDNS                | luci-app-smartdns              |
| MosDNS                  | luci-app-mosdns                |
| LXC Containers          | luci-app-lxc                   |
| 天翼家庭云/天翼云盘提速 | luci-app-familycloud           |
| 网络唤醒                | luci-app-wol                   |
| 定时唤醒                | luci-app-timewol               |
| OLED                    | luci-app-oled                  |
| WatchCat                | luci-app-watchcat              |
| UU游戏加速器            | luci-app-uugamebooster         |
| 雷神加速器              | luci-app-leigod-acc            |
| 灵缇游戏加速器          | luci-app-LingTiGameAcc         |
| VPN 绕过                | luci-app-vpnbypass             |
| Frps                    | luci-app-frps                  |
| Frp 内网穿透            | luci-app-frpc                  |
| UPnP                    | luci-app-upnp                  |
| Nps 内网穿透            | luci-app-nps                   |
| Nps 客户端              | luci-app-npc                   |
| 迅雷快鸟                | luci-app-xlnetacc              |
| OpenConnect VPN         | luci-app-ocserv                |
| OpenVPN(客户端)         | luci-app-openvpn               |
| Ngrok反向代理           | luci-app-ngrokc                |
| uHTTPd                  | luci-app-uhttpd                |
| KMS 服务器              | luci-app-vlmcsd                |
| RP PPPoE Server         | luci-app-rp-pppoe-server       |
| IPTV 帮手               | luci-app-iptvhelper            |
| 组播代理                | luci-app-omcproxy              |
| udpxy                   | luci-app-udpxy                 |
| XUNPD IPTV              | luci-app-xupnpd                |
| 组播转换                | luci-app-msd_lite              |
| MWAN3 分流助手          | luci-app-mwan3helper           |
| AirPlay 2 音频接收器    | luci-app-airplay2              |
| ClamAV                  | luci-app-clamav                |
| Polipo                  | luci-app-polipo                |
| Dnsforwarder            | luci-app-dnsforwarder          |
| PS3 NET 服务器          | luci-app-ps3netsrv             |
| Tinyproxy               | luci-app-tinyproxy             |
| BearDropper             | luci-app-beardropper           |
| 统一文件共享            | luci-app-unishare              |
| 可道云                  | luci-app-kodexplorer           |
| NFS 管理                | luci-app-nfs                   |
| 微力同步                | luci-app-verysync              |
| Alist 文件列表          | luci-app-alist                 |
| Cloudreve               | luci-app-cloudreve             |
| USB 打印服务器          | luci-app-usb-printer           |
| 打印服务器(模块)        | luci-app-p910nd                |
| 硬盘休眠                | luci-app-hd-idle               |
| 网络共享(SMB)           | luci-app-samba4                |
| Webdav                  | luci-app-webdav                |
| Aria2 配置              | luci-app-aria2                 |
| 挂载 SMB 网络共享       | luci-app-cifs-mount            |
| Rclone                  | luci-app-rclone                |
| miniDLNA                | luci-app-minidlna              |
| Transmission            | luci-app-transmission          |
| FTP 服务器              | luci-app-vsftpd                |
| PCHiFi 数字转盘遥控     | luci-app-music-remote-center   |
| qBittorrent             | luci-app-qbittorrent           |
| aMule                   | luci-app-amule                 |
| BaiduPCS Web            | luci-app-baidupcs-web          |
| N2N VPN                 | luci-app-n2n                   |
| SoftEther VPN 服务器    | luci-app-softethervpn          |
| IPSec VPN 服务器        | luci-app-ipsec-server          |
| OpenVPN 服务器          | luci-app-openvpn-server        |
| PPTP VPN 服务器         | luci-app-pptp-server           |
| ZeroTier                | luci-app-zerotier              |
| 移动通信模组            | luci-app-modem                 |
| USB移动网络拨号服务     | luci-app-usbmodem              |
| PCI移动网络拨号服务     | luci-app-pcimodem              |
| 移动数据                | luci-app-cpe                   |
| 超级移动网络拨号服务    | luci-app-hypermodem            |
| 短信                    | luci-app-sms-tool              |
| AHCP 服务器             | luci-app-ahcp                  |
| IP/MAC绑定              | luci-app-arpbind               |
| 简单MESH                | luci-app-easymesh              |
| 流量统计                | luci-app-bandwidthd            |
| 网速测试                | luci-app-netspeedtest          |
| SQM QoS                 | luci-app-sqm                   |
| Socat                   | luci-app-socat                 |
| IP限速                  | luci-app-eqos                  |
| 定时限速                | luci-app-eqosplus              |
| 应用过滤                | luci-app-oaf                   |
| 服务质量(QoS)           | luci-app-qos                   |
| 多线多拨                | luci-app-syncdial              |
| 负载均衡                | luci-app-mwan3                 |
| Turbo ACC 网络加速      | luci-app-turboacc              |
| Macvlan                 | luci-app-macvlan               |
| Dogcom                  | luci-app-dogcom                |
| 网络带宽监视器          | luci-app-nlbwmon               |
| 实时流量监测            | luci-app-wrtbwmon              |
| IPV6                    | ipv6helper                     |


## 定制固件 [![](https://img.shields.io/badge/-Actions编译教程-FFFFFF.svg)](#定制固件-)

1. 首先要登录Gihub账号，然后Fork此项目到你自己的Github仓库
2. 修改 `configs` 目录对应文件添加或删除插件，或者上传自己的 `xx.config` 配置文件
3. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `diy-script.sh` 文件内修改
4. 添加或修改 `xx.yml` 文件，最后点击 `Actions` 运行要编译的 `workflow` 即可开始编译
5. 编译大概需要3-5小时，编译完成后在仓库主页 [Releases](https://github.com/haiibo/OpenWrt/releases) 对应 Tag 标签内下载固件

## 本地构建 [![](https://img.shields.io/badge/-本地编译教程-FFFFFF.svg)](#本地构建-)

1. Ubuntu20.04LTS

2. 不要用root用户进行编译

3. 安装编译依赖

   ```
   sudo apt update -y
   sudo apt full-upgrade -y
   sudo apt install -y ack antlr3 asciidoc autoconf automake autopoint binutils bison build-essential \
   bzip2 ccache cmake cpio curl device-tree-compiler fastjar flex gawk gettext gcc-multilib g++-multilib \
   git gperf haveged help2man intltool libc6-dev-i386 libelf-dev libglib2.0-dev libgmp3-dev libltdl-dev \
   libmpc-dev libmpfr-dev libncurses5-dev libncursesw5-dev libreadline-dev libssl-dev libtool lrzsz \
   mkisofs msmtp nano ninja-build p7zip p7zip-full patch pkgconf python3 python3-pip libpython3-dev qemu-utils \
   rsync scons squashfs-tools subversion swig texinfo uglifyjs upx-ucl unzip vim wget xmlto xxd zlib1g-dev
   ```

4. 更新feeds并生产配置

   ```
   git clone --depth 1 --single-branch https://github.com/LiBwrt-op/openwrt-6.x.git
   cd openwrt-6.x
   ./scripts/feeds update -a && ./scripts/feeds install -a
   make menuconfig
   
   ./scripts/feeds search fdisk
   
   ```

5. 下载 dl库编译固件

   ```
   make download -j$(nproc)
   make -j1 V=s
   ```

6. 二次编译

   ```
   cd openwrt-6.x
   git fetch && git reset --hard origin/kernel-6.12
   ./scripts/feeds update -a && ./scripts/feeds install -a
   make menuconfig
   make V=s -j$(nproc)
   ```

7. 如果需要重新配置

   ```
   rm -rf .config
   make menuconfig
   make V=s -j$(nproc)
   ```

8. 编译完成后输出路径

   ```
   bin/targets
   ```

   
