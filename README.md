# DeepHarness

DeepHarness 把 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 的 Web 界面封装成 Windows 桌面客户端。**无需安装任何开发环境**（不用装 Node、不用装 dsh），双击即可使用。

## 系统要求

- Windows 10 / 11（64 位）

## 下载与安装

### 方式一：安装版（推荐）

1. 在右侧 **Releases** 下载 `DeepHarness-Setup-0.1.0.exe`
2. 双击运行，按提示完成安装
3. 从开始菜单或桌面快捷方式启动 **DeepHarness**

### 方式二：绿色版（免安装）

1. 下载 `DeepHarness-0.1.0.exe`
2. 双击即可运行

> 首次启动需要初始化，可能需要 1~2 分钟，请耐心等待窗口弹出。

## 首次使用：配置 API Key

首次启动后需要在设置里填写你的 `DEEPSEEK_API_KEY`：

1. 打开 DeepHarness，进入设置（Settings）
2. 填入 DeepSeek API Key
3. 保存后即可开始对话

> API Key 只保存在本机（`~/.dsh`），不会随软件上传。

## 常见问题

- **双击没反应 / 弹出 SmartScreen**：这是未签名应用的正常提示，点「更多信息 → 仍要运行」；首次启动较慢，请等待 1~2 分钟。
- **提示 dsh 服务未就绪**：等待更久或重启应用（首次初始化 profile 较慢）。
- **能看界面但不能聊天**：检查是否已正确填写 API Key。
- **安全软件拦截**：如被 Windows Defender 或杀毒软件拦截，请添加信任。

## 许可说明

本软件使用了 DeepSeek Harness、Electron 等开源组件（MIT License），其版权归各自作者所有。
