# 可选 MOD

在启动器的 MOD 页里可以单独启用或停用。

## 社区 MOD

启动器不自带，需要自己下载。

| MOD | 作者 | 说明 | 下载 |
|-----|------|------|------|
| 移除开拓局广场长椅老人 | Arthur | 删除开拓局广场长椅上坐着的老人。只替换 Maps/cty/cty01/sublevel/cty01_EST。默认不启用。 | [remove-plaza-elder.zip](https://github.com/epstomai/BPO/raw/main/mods/remove-plaza-elder.zip) |

## 启动器内置 MOD

启动器已经自带，正常不用下载；误删了 `data\mods` 里的文件夹时可以从这里补回。

| MOD | 说明 | 下载 |
|-----|------|------|
| 跳过 Intro | 启动时跳过厂商 Logo 与注意事项画面，直接到标题。只替换 Blueprints/UI/Startup/Startup。默认启用。 | [skip-intro.zip](https://github.com/epstomai/BPO/raw/main/mods/skip-intro.zip) |
| 直接进入游戏 | 标题画面出现后用当前选中的角色直接进入游戏，跳过标题与角色选择。没有角色时照常停在标题。默认启用。 | [auto-enter.zip](https://github.com/epstomai/BPO/raw/main/mods/auto-enter.zip) |
| 背包数量显示 | 背包消耗品显示真实堆叠数量（BaseInventory 补丁）。单机背包堆叠依赖它，建议保持启用。默认启用。 | [inv-amount.zip](https://github.com/epstomai/BPO/raw/main/mods/inv-amount.zip) |

## 安装

1. 关闭启动器。
2. 把 zip 解压到 BPLocalRun.exe 旁边的 `data\mods` 文件夹里，解压后应为
   `data\mods\<MOD 文件夹>\mod.json`（不要多套一层文件夹）。
3. 打开启动器，在 MOD 页里勾选启用，再开始游戏。

卸载：在 MOD 页取消勾选，再删掉 `data\mods` 里对应的文件夹。