# vps-common-scripts
（新手向）常用的vpn配置脚本和测试脚本Commonly used VPN configuration scripts and test scripts

1.测试脚本
————————————————————————————
wget -qO- bench.sh | bash
或者
curl -Lso- bench.sh | bash
综合工具箱
wget -O box.sh https://raw.githubusercontent.com/BlueSkyXN/SKY-BOX/main/box.sh && chmod +x box.sh && clear && ./box.sh
ARM版本
wget -O box.sh https://raw.githubusercontent.com/BlueSkyXN/SKY-BOX/main/armbox.sh && chmod +x box.sh && clear && ./box.sh

融合怪测试脚本
bash <(wget -qO- --no-check-certificate https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh)
bash <(wget -qO- --no-check-certificate https://github.com/spiritLHLS/ecs/raw/main/ecs.sh)

懒人脚本
wget -N --no-check-certificate https://raw.githubusercontent.com/veip007/hj/master/hj.sh && chmod +x hj.sh && bash hj.sh

BBR脚本
wget -N --no-check-certificate "https://raw.githubusercontent.com/mn-s/Linux-NetSpeed-2/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

御坂工具箱
wget -N https://cdn.jsdelivr.net/gh/ednovas/vpstoolbox@main/ednovastool.sh && chmod +x ednovastool.sh && ./ednovastool.sh
wget -P /root -N https://cdn.jsdelivr.net/gh/ednovas/vpstoolbox@main/ednovastool.sh && chmod +x ednovastool.sh && ./ednovastool.sh

2.VPN搭建
——————————————————————————
Make-A xray脚本  https://github.com/mack-a/v2ray-agent  （DD脚本）
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/reeceyng/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
ipv6
wget -N https://gitlab.com/rwkgyg/v2ray-agent/raw/master/install.sh && bash install.sh

魔改BBR（openVZ）
wget --no-cache -O lkl-haproxy.sh https://github.com/mzz2017/lkl-haproxy/raw/master/lkl-haproxy.sh && bash lkl-haproxy.sh
https://github.com/tcp-nanqinlang/wiki/wiki/lkl-haproxy

X-UI安装脚本
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)   一键分流

hy脚本
https://www.v2rayssr.com/hysteria.html
bash <(curl -fsSL https://git.io/hysteria.sh)

本地证书申请
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/acme-script/main/acme.sh && bash acme.sh

TUIC
wget -N https://gitlab.com/rwkgyg/tuic-yg/raw/main/tuic.sh && bash tuic.sh


naive
wget -N https://gitlab.com/rwkgyg/naiveproxy-yg/raw/main/naiveproxy.sh && bash naiveproxy.sh

3.warp
——————————————————————————————
一键WARP脚本  https://gitlab.com/rwkgyg/CFwarp
wget -N --no-check-certificate https://gitlab.com/rwkgyg/cfwarp/raw/main/CFwarp.sh && bash CFwarp.sh


fscarmen 一键脚本 (https://github.com/fscarmen/warp):
 - 首次运行 wget -N https://raw.githubusercontent.com/fscarmen/warp/main/menu.sh && bash menu.sh
 - 日常维护 warp

warp-Go
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/warp-go.sh && bash warp-go.sh


甲骨文保活
curl -L https://gitlab.com/spiritysdx/Oracle-server-keep-alive-script/-/raw/main/oalive.sh -o oalive.sh && chmod +x oalive.sh && bash oalive.sh

宝塔卸载脚本
wget http://download.bt.cn/install/bt-uninstall.sh

sh bt-uninstall.sh

修改root密码
passwd root

