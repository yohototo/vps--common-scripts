# vps-common-scripts
（新手向）常用的vpn配置脚本和测试脚本Commonly used VPN configuration scripts and test scripts  

## 1.测试脚本   
```
wget -qO- bench.sh | bash
```  
或者  
```
curl -Lso- bench.sh | bash
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
融合怪测试脚本  
```
bash <(wget -qO- --no-check-certificate https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh)
```  
```
bash <(wget -qO- --no-check-certificate https://github.com/spiritLHLS/ecs/raw/main/ecs.sh)
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

## 2.VPN搭建  
---
Make-A xray脚本  
[八合一]  https://github.com/mack-a/v2ray-agent  （DD脚本）  
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
[hihy安装脚本] https://www.v2rayssr.com/hysteria.html  
```
bash <(curl -fsSL https://git.io/hysteria.sh)
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
---

## 3.warp  
奈飞解锁检测
```
wget -O nf https://github.com/sjlleo/netflix-verify/releases/download/v3.1.0/nf_linux_amd64 && chmod +x nf && ./nf
```
---
[原版p3tex](https://github.com/P3TERX/warp.sh)  
```
bash <(curl -fsSL git.io/warp.sh) install
```
```
bash <(curl -fsSL git.io/warp.sh) menu
```

[一键WARP脚本]  https://gitlab.com/rwkgyg/CFwarp 
```
wget -N --no-check-certificate https://gitlab.com/rwkgyg/cfwarp/raw/main/CFwarp.sh && bash CFwarp.sh
``` 


[fscarmen 一键脚本]  https://gitlab.com/fscarmen/warp  
 - 首次运行
 ```
 wget -N https://gitlab.com/fscarmen/warp/-/raw/main/menu.sh && bash menu.sh
 ```  
 - 日常维护
```
warp
```

warp-Go  
```javascript data-lang="java"  
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/warp-go.sh && bash warp-go.sh`  
```
---
甲骨文保活  
```javascript data-lang="java"  
curl -L https://gitlab.com/spiritysdx/Oracle-server-keep-alive-script/-/raw/main/oalive.sh -o oalive.sh && chmod +x oalive.sh && bash oalive.sh`
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
test

