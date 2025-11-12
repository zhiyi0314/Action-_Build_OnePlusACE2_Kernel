# 使用GitHub Action 构建一加ACE2内核（KernelSU,SukiSU,KernelSU NEXT）
注意：
- 只用于OKI5.10的构建，请不要问除（一加ACE2）以外其他机型的问题
- 可选原版KernelSU,，MKSU，SukiSU,Kernelsu NEXT(同样支持Wild Ksu)
- SukiSU不接受关于KPM的反馈，因为本身就有BUG
- 除了SukiSU外，勾选SUSFS都需要安装模块，否则无法调整设置
- action思路以及部分代码 来自[https://github.com/Numbersf] 
  (其实大部分都是从人家那里偷来的还没求授权)
### 注意：当上游更新仓库时，SUSFS可能没有同步上游，所以有时候会导致SUSFS不可用，请等待上游仓库更新，或者使用旧版
### 请注意主页的更新日志！
- KernelSU补丁依旧打不上，包括1.0.5，求经中...
- 不要用Test（测试）版本action,编译出来也不能用susfs
- 删除Mksu-SUSFS（补丁全都不生效，没招了）
- Release中加入哈基白的网盘以及Ksu@Bai
