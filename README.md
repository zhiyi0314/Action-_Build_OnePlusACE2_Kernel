# 使用GitHub Action 构建一加ACE2内核（KernelSU,SukiSU,KernelSU NEXT）
Forked by [Action by Numbersf](https://github.com/Numbersf/Action-Build) 
## 当前状态:
- [x] KSU
- [x] MKSU
- [ ] MKSU-SUSFS
- [x] SukiSU-SUSFS
- [x] KSUN-SUSFS
## 可选功能:
- [x] BBG防格机
- [x] 自定义内核后缀

## 注意：
- 只用于OKI5.10的构建，请不要问除（一加ACE2）以外其他机型的问题（不做隔空适配）
- 可选原版KernelSU,，MKSU，SukiSU,KernelSU NEXT(同样支持Wild KSU管理器)
- SukiSU不接受关于KPM的反馈，因为本身就有BUG（能用是能用，能接受不时重启以及卡死就可以）
- 除了SukiSU外，勾选SUSFS都需要安装模块，否则无法调整设置
- Action思路以及（大）部分代码 来自[Numbersf](https://github.com/Numbersf) ，为大佬点Follow和Star！
- 已经Fork的用户，请回到我的仓库看看，能正常使用就可以不同步我的更新（因为改一个字也是改，测试时会提交大量的commit）

### 当上游更新仓库时，SUSFS可能没有同步上游，所以有时候会导致SUSFS不可用，请等待上游仓库更新，或者使用旧版

### 请注意主页的更新日志！
- KernelSU补丁依旧打不上，包括1.0.5（已破防）
- 不要用Test（测试）版本action,编译出来也不能用susfs
- 删除MKSU-SUSFS（补丁全都不生效，没招了）
- 关于MKSU和KSU，一段时间内是不会添加SUSFS了
- [哈基白的网盘coolapk@Frost_dog](https://www.123pan.com/s/u33Zjv-GTlWA)，更新日志在他的动态（他的内核添加了很多特性，极力推荐，上酷安为白白点个关注）
## 使用此仓库发布内核须知：
- 所有带SUSFS的Action都可以自选SUSFS模块下载（SukiSU不需要）
- 所有已经构建成功的Ak3包都可以在包内添加manager.apk实现在刷写内核时安装管理器
