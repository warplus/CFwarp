源码来源自 (http://ygkkk.blogspot.com/2022/09/gitlabcfwarpwarpwarp.html)

------------------------------------------------------------------------------------------------------------------------------

一键脚本：
```
wget -N --no-check-certificate http://gg.gg/warplus -o CFwarp.sh && bash CFwarp.sh

wget -N --no-check-certificate https://github.com/warplus/CFwarp/raw/main/CFwarp.sh && bash CFwarp.sh
```
----------------------------------------------------------------------------------------------------------------------

- 查看WARP当前统计状态：wg

- 相关WARP进程命令

手动临时关闭WARP网络接口

wg-quick down wgcf

手动开启WARP网络接口

wg-quick up wgcf

启动systemctl enable wg-quick@wgcf

开始systemctl start wg-quick@wgcf

状态systemctl status wg-quick@wgcf

重启systemctl restart wg-quick@wgcf

停止systemctl stop wg-quick@wgcf

关闭systemctl disable wg-quick@wgcf

systemctl is-active warp-svc
systemctl is-enabled warp-svc
warp-cli --accept-tos status
warp-cli --accept-tos account
warp-cli --accept-tos settings

---------------------------------------------------------------------------------------------------------


