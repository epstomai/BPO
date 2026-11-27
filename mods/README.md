# 可选 MOD / Optional mods

[中文](#中文) · [English](#english)

## 中文

在启动器的 MOD 页里可以单独启用或停用。

### 社区 MOD

启动器不自带，需要自己下载。

| MOD | 作者 | 说明 | 下载 |
|-----|------|------|------|
| 移除开拓局广场长椅老人 | Arthur | 删除开拓局广场长椅上坐着的老人。只替换 Maps/cty/cty01/sublevel/cty01_EST。默认不启用。 | [remove-plaza-elder.zip](https://github.com/epstomai/BPO/raw/main/mods/remove-plaza-elder.zip) |

### 启动器内置 MOD

启动器已经自带，正常不用下载；误删了 `data\mods` 里的文件夹时可以从这里补回。

| MOD | 说明 | 下载 |
|-----|------|------|
| 直接进入游戏 | 标题画面出现后用当前选中的角色直接进入游戏，跳过标题与角色选择。没有角色时照常停在标题。默认启用。 | [auto-enter.zip](https://github.com/epstomai/BPO/raw/main/mods/auto-enter.zip) |
| 背包数量显示 | 背包消耗品显示真实堆叠数量（BaseInventory 补丁）。单机背包堆叠依赖它，建议保持启用。默认启用。 | [inv-amount.zip](https://github.com/epstomai/BPO/raw/main/mods/inv-amount.zip) |
| 跳过 Intro | 启动时跳过厂商 Logo 与注意事项画面，直接到标题。只替换 Blueprints/UI/Startup/Startup。默认启用。 | [skip-intro.zip](https://github.com/epstomai/BPO/raw/main/mods/skip-intro.zip) |

### 安装

1. 关闭启动器。
2. 把 zip 解压到 BPLocalRun.exe 旁边的 `data\mods` 文件夹里，解压后应为
   `data\mods\<MOD 文件夹>\mod.json`（不要多套一层文件夹）。
3. 打开启动器，在 MOD 页里勾选启用，再开始游戏。

卸载：在 MOD 页取消勾选，再删掉 `data\mods` 里对应的文件夹。

## English

Each mod can be enabled or disabled on the launcher's MOD page.

### Community mods

Not shipped with the launcher; download them yourself.

| Mod | Author | Description | Download |
|-----|------|------|------|
| Remove the plaza bench elder | Arthur | Removes the old man sitting on the bench in the Pioneer Bureau (开拓局) plaza. Replaces only Maps/cty/cty01/sublevel/cty01_EST. Disabled by default. | [remove-plaza-elder.zip](https://github.com/epstomai/BPO/raw/main/mods/remove-plaza-elder.zip) |

### Built-in mods

Already shipped with the launcher, normally no need to download them; use these to restore a folder deleted from `data\mods`.

| Mod | Description | Download |
|-----|------|------|
| Enter the game directly | Once the title screen appears, enters the game with the selected character, skipping the title and character selection. Without a character it stays on the title as usual. Enabled by default. | [auto-enter.zip](https://github.com/epstomai/BPO/raw/main/mods/auto-enter.zip) |
| Inventory amounts | Shows the real stack size of consumables in the bag (BaseInventory patch). Offline bag stacking relies on it; keep it enabled. Enabled by default. | [inv-amount.zip](https://github.com/epstomai/BPO/raw/main/mods/inv-amount.zip) |
| Skip intro | Skips the publisher logos and notice screens at start and goes straight to the title. Replaces only Blueprints/UI/Startup/Startup. Enabled by default. | [skip-intro.zip](https://github.com/epstomai/BPO/raw/main/mods/skip-intro.zip) |

### Installation

1. Close the launcher.
2. Extract the zip into the `data\mods` folder next to BPLocalRun.exe, so that you get
   `data\mods\<mod folder>\mod.json` (no extra folder level).
3. Open the launcher, tick the mod on the MOD page, then start the game.

Uninstall: untick it on the MOD page, then delete its folder from `data\mods`.
