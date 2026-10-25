# 与神对话启动 · Dialogue with God Launcher

[中文](#中文) | [English](#english)

## 中文

最开始只是想给自己电脑上的 AI 客户端加一段启动动画，后来又陆续加上了虚拟人觉醒、机械舱、粒子效果和星舰背景，就有了这个项目。

动画以 550W 为主题，全长约 28 秒，分辨率为 1920×1080，60 FPS。画面、音乐和机械声音都放在同一个视频里，播放时可以保持同步。

在兼容的电脑上，启动器会一边播放动画，一边提前打开桌面客户端，等窗口准备好后再切换过去，并尽量保持两个窗口的大小和位置一致。

### 在新电脑上怎么用

1. 获取完整的 `550W-快速觉醒无缝启动版.zip`。
2. 右键选择“全部解压”，放到一个准备长期保留的文件夹里。
3. 确认 `550W.exe` 和 `boot.mp4` 在同一层目录。
4. 先双击 `boot.mp4`，检查视频和声音能否正常播放。
5. 如果需要自动打开聊天窗口，先安装兼容的桌面客户端，并手动打开一次。
6. 双击**从 ZIP 中解压出来的** `550W.exe`。

目录大致如下：

```text
ConversationsWithGod/
├── 550W.exe
├── boot.mp4
└── 使用说明.txt
```

确认能用后，可以给这个 EXE 新建一个桌面快捷方式。之后保留整个文件夹即可，不要只把 EXE 单独移走。

如果下载的内容缺少压缩包或 `boot.mp4`，需要先补齐完整动画包，只有 EXE 是无法播放的。

### 关于当前版本

这里有几个容易弄混的地方：

- **独立动画版**在上面提到的 ZIP 中，可以完整解压后使用。
- `Conversations with God` 文件夹外层的同名 `550W.exe`，以及已有的 `.lnk` 快捷方式，是为我自己电脑配置的入口，里面仍然指向本机路径。换电脑时请使用 ZIP 内的版本，并重新创建快捷方式。
- **星舰聊天背景**是另外配置的一部分，目前没有包含在独立动画 ZIP 中，也还没有整理成完整的便携发行包。

所以，下载后能播放启动动画，并不代表已经安装了星舰背景。完整背景效果还需要背景工具、星舰视频和对应的本机配置。

背景工具使用的是 [Backdrop for Codex](https://github.com/TogawaSakiko-desuwa/backdrop-for-codex)，客户端兼容范围可以查看原项目说明。

### 客户端兼容性

当前启动器识别的 Windows 应用标识为：

```text
OpenAI.Codex_2p2nqsd0c76g0!App
```

如果新电脑安装的客户端不对应这个标识，动画仍然可以单独播放，但自动打开应用和窗口交接可能无法完成。目前还不支持在界面里自由选择其他程序。

只想看动画的话，直接播放 `boot.mp4` 就可以，不需要安装目标客户端。

### 快捷键

| 按键 | 操作 |
| --- | --- |
| 空格 / Enter | 跳过动画并尝试切换到目标窗口 |
| Esc | 退出动画 |
| M | 静音或恢复声音 |
| F11 | 切换窗口显示方式 |

按 Esc 退出动画时，已经提前打开的桌面客户端可能仍会保持运行。

### 遇到问题时

**提示找不到完整的星舰启动文件**

通常是运行了为我自己电脑配置的外层入口。重新解压 `550W-快速觉醒无缝启动版.zip`，使用里面的 EXE，不要用外层同名文件覆盖它。

**动画能播放，但聊天窗口没有打开**

先检查客户端能否手动打开，再确认安装版本是否与上面的应用标识匹配。程序目录中的 `550W-启动日志.txt` 可以帮助排查；发到 Issues 前，记得检查里面有没有自己的用户名或文件路径。

**黑屏或找不到视频**

确认 `boot.mp4` 没有缺失，并且和 EXE 放在同一个文件夹。也可以先用系统播放器单独播放视频，判断是不是视频本身的问题。

目前，动画与星舰聊天窗口的交接已经在我的电脑上测试过，但还没有在全新配置的电脑上完成完整安装测试。如果遇到问题，欢迎在 Issues 中说明 Windows 版本、客户端版本和具体表现。

---

## English

This started as a startup animation for the AI client on my own PC. Over time, I added a virtual character awakening sequence, a mechanical chamber, particle effects, and a starship background.

The 550W-themed animation runs for about 28 seconds at 1920×1080 and 60 FPS. The visuals, music, and mechanical sounds are included in one video file to keep playback synchronized.

On a compatible setup, the launcher opens the desktop client while the animation is playing, then switches to its window when it is ready. It also tries to keep both windows at the same size and position.

### Using it on a new PC

1. Get the complete `550W-快速觉醒无缝启动版.zip` package.
2. Right-click it and select **Extract All**. Choose a folder you plan to keep.
3. Make sure `550W.exe` and `boot.mp4` are in the same folder.
4. Open `boot.mp4` first to check that the video and sound play correctly.
5. If you want the launcher to open the chat client automatically, install a compatible desktop client and open it manually once.
6. Run the **`550W.exe` extracted from the ZIP**.

The extracted folder should look roughly like this:

```text
ConversationsWithGod/
├── 550W.exe
├── boot.mp4
└── 使用说明.txt
```

Once everything works, create a new desktop shortcut to this EXE. Keep the whole folder together rather than moving the EXE on its own.

If your download is missing the ZIP or `boot.mp4`, you will need the complete animation package first. The EXE alone cannot play the animation.

### What is included right now?

There are a few differences worth explaining:

- The ZIP mentioned above contains the **standalone startup animation edition**.
- The other `550W.exe` in the outer `Conversations with God` folder, along with the existing `.lnk` shortcuts, was configured for my own PC. These files still point to local paths. On another computer, use the version inside the ZIP and create your own shortcuts.
- The **starship chat background** is a separate part of my setup. It is not included in the standalone animation ZIP, and a complete portable package has not been released yet.

Being able to play the startup animation does not mean the starship background has been installed. That effect also needs the background tool, the starship video, and configuration on the new computer.

The background setup uses [Backdrop for Codex](https://github.com/TogawaSakiko-desuwa/backdrop-for-codex). Check the original project for supported clients and versions.

### Client compatibility

The current launcher looks for this Windows application ID:

```text
OpenAI.Codex_2p2nqsd0c76g0!App
```

If the client installed on your PC does not match this ID, you can still play the animation separately, but automatic launching and window handoff may not work. There is currently no interface for selecting a different application.

If you only want to watch the animation, open `boot.mp4` directly. No target client is needed.

### Keyboard shortcuts

| Key | Action |
| --- | --- |
| Space / Enter | Skip the animation and attempt to switch to the target window |
| Esc | Exit the animation |
| M | Mute or restore sound |
| F11 | Switch window display mode |

Exiting the animation with Esc may leave the desktop client running if it has already opened.

### Troubleshooting

**The launcher says it cannot find the complete starship startup files**

You are probably running the entry point configured for my PC. Extract `550W-快速觉醒无缝启动版.zip` again and use the EXE inside it. Do not replace it with the file from the outer folder.

**The animation plays, but the chat window does not open**

Check whether the client opens manually, then confirm that its installation matches the application ID above. The launcher writes a `550W-启动日志.txt` file in its folder to help with troubleshooting. Before posting it in Issues, check for personal information such as your username or file paths.

**The screen is black, or the video cannot be found**

Make sure `boot.mp4` is present and in the same folder as the EXE. Try opening it in your system's media player to check whether the video itself plays correctly.

The transition from the animation to the starship chat window has been tested on my own PC. A complete installation on a freshly configured computer has not been tested yet. If something goes wrong, please open an issue with your Windows version, client version, and a description of what happened.
