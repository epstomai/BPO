# BPO · BLUE PROTOCOL 离线启动器

BPLocalRun 离线版 v0.2.10，数据包 2026.11.05。

下载：**[BPO-v0.2.10.zip](https://github.com/epstomai/BPO/releases/download/v0.2.10/BPO-v0.2.10.zip)**
（启动器、使用说明和数据包都在里面）
国内下载慢：[加速下载](https://bpo.knia.top/BPO-v0.2.10.zip)（推荐）或 [夸克网盘](https://pan.quark.cn/s/43669edc4779)，都是同一个 zip，不用提取码

## 需要准备

1. BLUE PROTOCOL 最终版客户端（BPRP 发布的客户端即可）。
   BLUEPROTOCOL\Binaries\Win64\BLUEPROTOCOL-Win64-Shipping.exe 的 SHA-256 应为
   3e373bf5cebe9742e1300fa109f45b9bba131842498a62da1b5f33a49a9fb735
   版本不对时启动器会直接提示，不会进游戏。
2. Windows 10/11 64 位。启动器需要 Microsoft Edge WebView2 运行库（Win11 自带；
   Win10 打开启动器一片空白或打不开时，到微软官网安装 WebView2 Runtime）。

## 安装

1. 新建一个文件夹（不要放在 Program Files 里），把 BPO-v0.2.10.zip 解压进去，
   里面是 BPLocalRun.exe、使用说明.txt 和数据包 bplr-data-2026.11.05.zip（数据包不用解压）。
2. 客户端文件夹（里面有 BLUEPROTOCOL.exe、BLUEPROTOCOL、Engine）放在同一个文件夹里
   或它的上级，启动器会自动找到；找不到就在「设置与更新」里选择。
   客户端目录要可写：汉化等 MOD 的 pak 会放进 BLUEPROTOCOL\Content\Paks\~mods。
3. 打开 BPLocalRun.exe。第一次会导入（或下载）数据包并自动重启。
4. 注册一个本机账号（只存在这台电脑上），点「开始游戏」。没有角色时会走原版开场并创建角色。

杀毒软件：启动器会把 OrbitCore.dll、xinput1_3.dll、dwmapi.dll（UE4SS）放进游戏目录并随游戏加载，
可能被误报。被拦截时把本文件夹和客户端文件夹加入白名单。

联网：启动时访问 GitHub 检查和下载更新（「设置与更新」里可以关掉）；
点「发送给作者」时上传反馈包。没有在线模式、没有联机，账号和存档都在本机。

## 规则

主页底部「规则」：
- 改动：存档管理里的难度、加成、经验倍率、季节装饰、常开副本等设置生效（默认）。
- 原版：这些都不生效，和以后的在线版规则一致。帮忙测试时建议选「原版」。

## 更新

- 自动：启动器启动时检查 GitHub，有新版本会询问，确认后自动下载、替换并重启。
- 手动：关闭启动器，用新的 BPLocalRun.exe 覆盖旧的；新数据包 zip 放到 BPLocalRun.exe 旁边，
  打开启动器会自动导入。

存档在 data\state 和 data\sidecar，更新不会动它们。想备份就复制整个 data 文件夹。

## 反馈问题

关闭游戏后，在「设置与更新」→「反馈问题」里写清楚在哪、做了什么、看到了什么，
点「发送给作者」就会直接上传（游戏崩溃退出后启动器也会主动提示）。
发送失败或想自己发时，点「只导出到本地」，把程序目录「反馈包」文件夹里的 zip 发给作者。
反馈包里有最近 3 次游戏的日志、崩溃报告、请求记录和当前角色的存档，不含密码。
