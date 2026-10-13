# BongoCat_LoggerEnhancement

该项目用于增强 **Bongo Cat（Steam 游戏）** 的日志功能，为原版游戏增加 **房间聊天记录** 和 **拍一拍定位** 两项功能。

- **房间聊天记录**：房间内其他 cat 发送的聊天消息会被记录到游戏日志中。
- **拍一拍定位**：当房间内的其他用户通过鼠标点击你的 cat 时，日志会记录是哪一只 cat 拍了拍你。

> [!WARNING]
>
> 拍一拍定位功能的日志输出格式为：`%user 拍了拍你`。
>
> 该功能暂不支持多语言，因此日志内容仅会以中文输出。

# 使用方法

1. 打开游戏安装目录：
   - Steam → 选择游戏 → 点击设置齿轮图标 → 管理 → 浏览本地文件
   - 默认目录结构：`$SteamGameStorage$\BongoCat`
2. 进入 `\BongoCat_Data\Managed` 目录。
3. 使用下载的文件替换目录中的对应文件。
4. 重启游戏。

> [!WARNING]
>
> 替换文件前请先关闭游戏。

# 游戏效果

点击自己的 cat 设置，在【其他】选项中选择【打开日志文件夹】。

在打开的文件夹中找到并打开 `Player.log`，即可看到新增的日志内容。

示例：

```bash
[2026-10-12 10:24:21] koto: hello!!!
[2026-10-12 10:24:21] koto拍了拍你
[2026-10-12 10:24:21] koto拍了拍你
```

------

# BongoCat_LoggerEnhancement

This project enhances the logging functionality of **Bongo Cat (Steam game)** by adding **room chat logging** and **pat tracking**.

- **Room Chat Logging**: Chat messages sent by other cats in the room will be recorded in the game log.
- **Pat Tracking**: When another user clicks your cat with their mouse, the log will record which cat patted you.

> [!WARNING]
>
> The output format for the pat tracking feature is: `%user 拍了拍你`.
>
> This feature does not currently support multiple languages, so the pat message is only output in Chinese.

# Installation

1. Open the game installation directory:
   - Steam → Select the game → Click the gear icon → Manage → Browse local files
   - Default directory structure: `$SteamGameStorage$\BongoCat`
2. Navigate to the `\BongoCat_Data\Managed` directory.
3. Replace the corresponding files with the downloaded files.
4. Restart the game.

> [!WARNING]
>
> Make sure the game is closed before replacing the files.

# Result

Open your cat's settings and select **Open Log Folder** under the **Other** section.

In the opened folder, find and open `Player.log`. The enhanced log output will look like this:

```bash
[2026-10-12 10:24:21] koto: hello!!!
[2026-10-12 10:24:21] koto拍了拍你
[2026-10-12 10:24:21] koto拍了拍你
```
