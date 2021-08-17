# 自用openwrt编译actions
基于原版openwrt编译，添加L大固件  
参考了P3TERX/Actions-OpenWrt，主要是对某些步骤进行了适用于自己习惯的修改

## 仓库初始化
1. 创建Personal access tokens，添加至仓库Actions secrets，变量名为```TOKEN```
2. Fork了P3TERX/ssh2actions作为ssh连接actions防止作者删库跑路
3. Fork了actions/upload-artifact作为上传至actions输出的actions防止作者删库跑路
4. Fork了softprops/action-gh-release作为上传至release的actions防止作者删库跑路
