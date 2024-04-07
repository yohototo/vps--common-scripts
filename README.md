# vps-common-scripts
（新手向）常用的vpn配置脚本和测试脚本Commonly used VPN configuration scripts and test scripts  
- [1.测试脚本](#1.测试脚本)
- [2.vpn搭建](#2.vpn搭建)
- [3.warp](#3.warp)
- [4.UI客户端备份](#4.UI客户端备份)

## <a id="1.测试脚本"></a> 
## 1.测试脚本   
```
wget -qO- bench.sh | bash
```  
或者  
```
curl -Lso- bench.sh | bash
```
#### 测速脚本  
纯测速脚本
```
wget -qO- --no-check-certificate https://raw.githubusercontent.com/oooldking/script/master/superbench.sh | bash
```
---
```
bash <(wget -qO- bash.spiritlhl.net/ecs-cn)
```
或
```
bash <(wget -qO- --no-check-certificate https://github.com/spiritLHLS/ecsspeed/raw/main/script/ecsspeed-cn.sh)
```
国内用
```
bash <(wget -qO- --no-check-certificate https://ghproxy.com/https://raw.githubusercontent.com/spiritLHLS/ecsspeed/main/script/ecsspeed-cn.sh)
```
---
#### 综合工具箱  
```
wget -O box.sh https://raw.githubusercontent.com/BlueSkyXN/SKY-BOX/main/box.sh && chmod +x box.sh && clear && ./box.sh
```  
#### ARM版本  
```
wget -O box.sh https://raw.githubusercontent.com/BlueSkyXN/SKY-BOX/main/armbox.sh && chmod +x box.sh && clear && ./box.sh
```  
---
#### 融合怪测试脚本  
```
bash <(wget -qO- --no-check-certificate https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh)
```  
```
bash <(wget -qO- --no-check-certificate https://github.com/spiritLHLS/ecs/raw/main/ecs.sh)
```  
#### eooce
```
curl -fsSL https://raw.githubusercontent.com/eooce/ssh_tool/main/ssh_tool.sh -o ssh_tool.sh && chmod +x ssh_tool.sh && ./ssh_tool.sh
```  
懒人脚本  
```
wget -N --no-check-certificate https://raw.githubusercontent.com/veip007/hj/master/hj.sh && chmod +x hj.sh && bash hj.sh
```  

BBR脚本  
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/mn-s/Linux-NetSpeed-2/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```  

御坂工具箱  
```
wget -N https://cdn.jsdelivr.net/gh/ednovas/vpstoolbox@main/ednovastool.sh && chmod +x ednovastool.sh && ./ednovastool.sh
```  
```
wget -P /root -N https://cdn.jsdelivr.net/gh/ednovas/vpstoolbox@main/ednovastool.sh && chmod +x ednovastool.sh && ./ednovastool.sh
```
证书申请脚本one55
```
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/acme-script/main/acme.sh && bash acme.sh
mikasa
```
```
1243e4287b4538a6670134f7c03669fb01
```

## <a id="2.vpn搭建"></a> 
## 2.VPN搭建
---
[fscarmen sing-box 全家桶](https://github.com/fscarmen/sing-box)
```
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/sing-box/main/sing-box.sh)
```
[甬哥sing-box 四协议共存](https://github.com/yonggekkk/sing-box_hysteria2_tuic_argo_reality)
```
bash <(curl -Ls https://gitlab.com/rwkgyg/sing-box-yg/raw/main/sb.sh)
```

[hy2一键 misaka](https://blog.misaka.rest/2023/09/02/hysteria2-script/)
```
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/hysteria-install/main/hy2/hysteria.sh && bash hysteria.sh
```

[hy1一键](https://github.com/Misaka-blog/hysteria-install)
```
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/hysteria-install/main/hy1/hysteria.sh && bash hysteria.sh
```
[hihy](https://github.com/emptysuns/Hi_Hysteria)
```
su - root #switch to root user.
bash <(curl -fsSL https://git.io/hysteria.sh)
```
---
[Make-A xray脚本八合一（DD脚本）](https://github.com/mack-a/v2ray-agent)  
```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```    
```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/reeceyng/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```
ipv6  
```
wget -N https://gitlab.com/rwkgyg/v2ray-agent/raw/master/install.sh && bash install.sh
```
---
[Argo + Xray](https://github.com/fscarmen/argox#argox-for-vps-%E8%BF%90%E8%A1%8C%E8%84%9A%E6%9C%AC)
```
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/argox/main/argox.sh)
```
---
魔改BBR（openVZ）https://github.com/tcp-nanqinlang/wiki/wiki/lkl-haproxy  
```
wget --no-cache -O lkl-haproxy.sh https://github.com/mzz2017/lkl-haproxy/raw/master/lkl-haproxy.sh && bash lkl-haproxy.sh
```  

---
X-UI安装脚本  
```
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
```
一键分流 
```
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```   
---
hy1脚本  
[Yg hy] (https://gitlab.com/rwkgyg/hysteria-yg) 
```
wget -N https://gitlab.com/rwkgyg/hysteria-yg/raw/main/hysteria.sh && bash hysteria.sh
```

TUIC  
```
wget -N https://gitlab.com/rwkgyg/tuic-yg/raw/main/tuic.sh && bash tuic.sh
```  
```
wget -N --no-check-certificate https://gitlab.com/Misaka-blog/tuic-script/-/raw/main/tuic.sh && bash tuic.sh
```

naive  
```
wget -N https://gitlab.com/rwkgyg/naiveproxy-yg/raw/main/naiveproxy.sh && bash naiveproxy.sh
```
```
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/naiveproxy-script/main/naiveproxy.sh && bash naiveproxy.sh
```
---
本地证书申请  
misaka
```
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/acme-script/main/acme.sh && bash acme.sh
```
api
```
wget -N --no-check-certificate https://raw.githubusercontent.com/CCCOrz/auto-acme/main/acme.sh && bash acme.sh
```
ygkkk
```
wget -N https://gitlab.com/rwkgyg/acme-script/raw/main/acme.sh && bash acme.sh
```
(证书路径)
```
/root/cert.crt
```
```
/root/private.key
```

```
/etc/v2ray-agent/tls/
```
---
## <a id="3.warp"></a>
## 3.WARP  
奈飞解锁检测
```
wget -O nf https://github.com/sjlleo/netflix-verify/releases/download/v3.1.0/nf_linux_amd64 && chmod +x nf && ./nf
```
---
[p3tex](https://github.com/P3TERX/warp.sh)  
```
bash <(curl -fsSL git.io/warp.sh) install
```
```
bash <(curl -fsSL git.io/warp.sh) menu
```

[一键WARP脚本](https://gitlab.com/rwkgyg/CFwarp) 
```
wget -N --no-check-certificate https://gitlab.com/rwkgyg/cfwarp/raw/main/CFwarp.sh && bash CFwarp.sh
``` 


[fscarmen 一键脚本](https://gitlab.com/fscarmen/warp)  
 - 首次运行
 ```
 wget -N https://gitlab.com/fscarmen/warp/-/raw/main/menu.sh && bash menu.sh
 ```  
 - 日常维护
```
warp
```

warp-Go  
```javascript data-lang="python"  
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/warp-go.sh && bash warp-go.sh`  
```
---
甲骨文保活（oracle alive）  
```javascript data-lang="java"  
curl -L https://gitlab.com/spiritysdx/Oracle-server-keep-alive-script/-/raw/main/oalive.sh -o oalive.sh && chmod +x oalive.sh && bash oalive.sh
```
[甲骨文保活脚本](https://gitlab.com/spiritysdx/Oracle-server-keep-alive-script)
```
curl -L https://gitlab.com/spiritysdx/Oracle-server-keep-alive-script/-/raw/main/oalive.sh -o oalive.sh && chmod +x oalive.sh && bash oalive.sh
```

宝塔卸载脚本  
```
wget http://download.bt.cn/install/bt-uninstall.sh
```  

```
sh bt-uninstall.sh
``` 

修改root密码  
```javascript data-lang="java"
passwd root
```
---  
## <a id="4.UI客户端备份"></a>   
## 4.UI客户端备份   
[v2rayN 备份](https://github.com/yohototo/v2rayN-backup)  
[Clash Verge 备份](https://github.com/yohototo/clash-verge-1.3.6-backup)  
[Nekoray 备份](https://github.com/yohototo/Backup-nekoray)  
[Nekoray for Android备份](https://github.com/yohototo/Backup-NekoBoxForAndroid/releases/tag/1.2.9)

1.[百度一下]

[百度一下]:https://www.baidu.com 

2.[Google](https://www.google.com)


# 1
## 2
### 3
#### 4
##### 5
###### 6
####### 7

666658588859klkl5959恐龙看烂 you are my only撒5589打水

