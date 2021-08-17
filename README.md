# 自用openwrt编译actions
基于原版openwrt编译，添加L大固件

## 使用流程
1. 创建Personal access tokens，添加至仓库Actions secrets，变量名为```TOKEN```
2. Fork P3TERX/ssh2actions作为ssh连接actions等待调用
3. Fork actions/upload-artifact作为上传至actions输出的actions等待调用
4. Fork softprops/action-gh-release作为上传至release的actions等待调用
