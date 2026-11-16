# ZianIME 语音输入法使用说明 / User guide

## 安装与启用

支持 Android 8.0 及以上的 64 位 ARM（arm64-v8a）设备。

安装完成后，在 Android 系统设置中启用并选择 ZianIME 语音输入法。不同设备的菜单名称可能有所不同，可在设置中搜索“输入法”或“屏幕键盘”。

Android 启用输入法时可能显示键盘能够访问输入内容的系统提示。使用前请阅读本应用的隐私政策。

## 语音输入

1. 打开 ZianIME 语音输入法设置，下载语音模型，建议使用 Wi-Fi。
2. 授予麦克风权限。在其他应用的文字输入框中切换到 ZianIME 语音输入法。
3. 使用键盘中的语音入口开始输入。长按语音输入时持续监听，松手完成；实时预览可能随识别更新而修正。
4. 模型下载完成后可离线识别，无需连接 PC。语音识别并非始终准确，发送重要内容前请检查文字。

界面语言只改变菜单和提示。识别语言请在对应设置中单独选择。

## 文字日志

文字日志默认关闭。开启后记录完成的语音识别文字，不是所有手动键盘输入的记录。

- 支持按日期浏览、搜索、删除和导出。
- 开启自动清理后保留最近 30 个自然日；默认不自动清理。
- 关闭记录开关不会删除已有记录。
- 应用内删除不会删除您主动导出的文件。
- 对标记为密码或禁止个性化学习的输入框不记录；这依赖目标应用正确标记输入框。

## 常见问题

**下载模型失败：** 检查网络和可用存储，返回设置页重试。下载尚未完成时无法使用本地语音模型。

**无法录音：** 检查 Android 的麦克风权限、系统麦克风开关，以及是否有其他应用占用麦克风。

**识别较慢：** 本地识别速度取决于处理器、温度和系统资源。反馈时请提供设备型号和 Android 版本。

**APK 无法安装：** 核对系统版本、arm64-v8a 架构及安装包完整性。若提示签名不一致或版本降级，先停止覆盖操作并反馈，不要为了安装而直接卸载导致数据丢失。

**怎样反馈：** 使用 Issues 模板填写版本、设备、复现步骤和预期行为。只提供经过脱敏的信息；截图应遮挡账号、聊天内容和其他个人信息。

## English quick start

1. Use Android 8.0+ on an arm64-v8a device.
2. After installation, enable and select ZianIME in Android's keyboard settings. Menu names differ by device.
3. Download the speech model in the app and grant microphone permission for voice input.
4. Use the voice control from an input field. Live results may change as recognition proceeds; review important text before sending.
5. Optional history is off by default. Turning it off does not remove existing records. Exported files must be managed separately.

For installation errors, do not uninstall an existing app before checking the error and protecting your data. Include the app version, device model, Android version and reproducible steps in a public issue, without private input content or recordings.
