## PvP

PvP is a work in progress. It lets you use duel rooms under a low latency environment (LAN). The friends list also works

## Setting it up on a single PC

- Open `Data/Setting.json` and set `MultiplayerEnabled` to `true`
- Open `Data/ClientData/ClientSettings.json` and set `MultiplayerToken` to some random text value
- Copy / paste the entire `YgoMaster` folder so that it creates `YgoMaster - Copy`
- Inside that `YgoMaster - Copy` folder edit `Data/ClientData/ClientSettings.json` and set `MultiplayerToken` to a different random text value to the previous folder
- Run `YgoMaster.exe` in the `YgoMaster` folder
- Run `YgoMasterClient.exe` in both folders

## Setting it up on LAN/WAN

- Modify `BaseIP` in both `Data/Setting.json` and `Data/ClientData/ClientSettings.json` to point to the IP of the machine which runs `YgoMaster.exe`
- Play around with `MultiplayerNoDelay` (`Setting.json` / `ClientSettings.json`) to see which works best for you (it disables nagle's algorithm)

## Starting duels

- Click `DUEL` in the home menu
- Click `Duel Room (PvP)` and create a duel room as you would in the normal game






## 中文翻译BY TWS
## PvP
PvP正在进行测试中。它允许您在插网线的环境下使用决斗室。好友列表也适用

## 在单台电脑上对战

- 打开 `Data/Setting.json` 设置 `MultiplayerEnabled` 为 `true`
- 打开 `Data/ClientData/ClientSettings.json` 设置 `MultiplayerToken` 为一些随机文本值
- 复制/粘贴整个 `YgoMaster` 文件夹为 `YgoMaster - 复制`作为第二个客户端
- 在`YgoMaster-Copy`文件夹中编辑`Data/ClientData/ClientSettings.json`，并将`MultiplayerToken`设置为与前一文件夹不同的随机文本值
- 运行`YgoMaster`文件夹内的 `YgoMaster.exe`
- 同时运行 `YgoMaster` 和文件夹 `YgoMaster - 复制`文件夹内的`YgoMasterClient.exe` 

## 在网上对战设置

- 修改`Data/Setting.json`和`Data/ClientData/ClientSettings.json`中的`BaseIP`，以指向运行`YgoMaster.exe`的机器的IP`
- 玩`MultiplayerNoDelay`（`Setting.json`/`ClientSettings.json`），看看哪一个最适合你（它禁用了nagle的算法）

## 开始决斗

- 单击主菜单中的`DUEL`
- 点击`决斗室（PvP）`并创建一个决斗室，就像在普通游戏中一样
