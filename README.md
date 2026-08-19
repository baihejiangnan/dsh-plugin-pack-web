# 🧩 DeepSeek Harness 插件包 · Profile/Web 一键复刻

> 面向 DeepSeek Harness 社区生态的「插件包」分享仓库。  
> 包含 30 项插件/依赖、完整安装命令、可复刻提示词与预览截图。

## 📸 预览

![预览 1](images/preview-1.png)
![预览 2](images/preview-2.png)
![预览 3](images/preview-3.png)
![预览 4](images/preview-4.png)
![预览 5](images/preview-5.png)
![预览 6](images/preview-6.png)

## ✨ 这是什么

这是一个 **DeepSeek Harness（DSH）插件包**，目标是把一套完整的 `profile/web` 社区插件体系打包分享。

- 环境：`profile/web`
- 插件/依赖总数：30 项
- 包含：官方内置、社区插件、自研兼容插件、补丁配置
- 适用人群：希望快速复刻 DSH Web 端插件生态的用户

## 🚀 一键安装命令

在全新 DeepSeek Harness 中，依次执行以下命令即可安装本插件包中的社区插件：

```sh
# 官方内置：无需安装
# @deepseek-ai/dsh-base
# @deepseek-ai/dsh-web-app
dsh plugin --profile web add github:baihejiangnan/dsh-session-context-menu
dsh plugin --profile web add github:mishibeikejie/zat-dsh-engine
dsh plugin --profile web add @liustack/modlens
dsh plugin --profile web add billion-context-dsh
dsh plugin --profile web add dsh-better-sidebar
dsh plugin --profile web add dsh-checkpoint-diff
dsh plugin --profile web add dsh-extension-hub
dsh plugin --profile web add dsh-tdai-memory
dsh plugin --profile web add dsh-web-mobile-fix
dsh plugin --profile web add dsh-what-changed
dsh plugin --profile web add github:vlln/dsh-navbar
dsh plugin --profile web add github:huanyuLv/dsh-balance-tide
dsh plugin --profile web add github:christophersmith2737-commits/OffPeak
dsh plugin --profile web add github:dream12347/dsh-session-manager
dsh plugin --profile web add github:lire1131/dsh-undo-plugin
dsh plugin --profile web add github:baihejiangnan/dsh-topbar-manager
dsh plugin --profile web add github:hzhz314159/dsh-side-session
dsh plugin --profile web add "https://github.com/omdsh-dev/dsh-at-file/archive/refs/tags/v0.6.3.tar.gz"
dsh plugin --profile web add github:omdsh-dev/dsh-genui
dsh plugin --profile web add github:titanwings/dsh-automation
dsh plugin --profile web add github:omdsh-dev/dsh-notification
dsh plugin --profile web add dsh-status-rotator
dsh plugin --profile web add github:a179-sanae/dsh-auto-collapse#main
dsh plugin --profile web add github:lxzy-7/dsh-plugin-guard
dsh plugin --profile web add github:LX2000WASD/dsh-web-plugin-manager
dsh plugin --profile web add github:chenw2759-wq/dsh-plugin-healthcheck
dsh plugin --profile web add "https://codeload.github.com/baihejiangnan/dsh-settings-organizer/tar.gz/refs/tags/v1.1.0"
# dsh-skin（建议使用以下 GitHub 源安装）
dsh plugin --profile web add github:wei-806206088/dsh-skin
```

> 如果当前 DSH 启用了安装保护，请使用：
> ```sh
> dshpm install <包名> --profile web
> ```

## 📋 完整复刻提示词

可以直接把下面的提示词发给别人，或粘贴给一台全新的 DeepSeek Harness 助手。

📄 独立文件：[`PROMPT.md`](PROMPT.md)

<details>
<summary>点击展开完整提示词</summary>

# 可发送给别人的 DSH 插件体系复刻提示词

> 直接把下面「提示词正文」复制发给对方，或粘贴给一台全新的 DeepSeek Harness 助手。

---

## 提示词正文

你是 DeepSeek Harness 环境配置助手。请帮我在一台**原生、未安装任何社区插件**的 DeepSeek Harness 上，完整复刻以下 `profile/web` 插件体系。

### 目标

- Profile 名称：`web`
- 目标目录：`~/.dsh/profiles/web`（Windows 为 `C:\Users\<用户名>\.dsh\profiles\web`）
- 参考备份：`dsh-backup-web-2026-08-19.json`
- 最终应包含 **30 项**插件/依赖，与我的环境一致。

### 执行步骤

#### 1. 准备 profile

如果还没有 `web` profile，请先创建或进入：

```sh
dsh web
```

确保 `~/.dsh/profiles/web` 存在。

#### 2. 安装插件

请依次执行下面的命令。若当前 DSH 启用了安装保护，请把 `dsh plugin --profile web add ...` 替换为 `dshpm install <包名> --profile web`，或通过插件市场安装。

```sh
# @deepseek-ai/dsh-base 官方内置，无需安装
# @deepseek-ai/dsh-web-app 官方内置，无需安装
dsh plugin --profile web add github:baihejiangnan/dsh-session-context-menu
dsh plugin --profile web add github:mishibeikejie/zat-dsh-engine
dsh plugin --profile web add @liustack/modlens
dsh plugin --profile web add billion-context-dsh
dsh plugin --profile web add dsh-better-sidebar
dsh plugin --profile web add dsh-checkpoint-diff
dsh plugin --profile web add dsh-extension-hub
dsh plugin --profile web add dsh-tdai-memory
dsh plugin --profile web add dsh-web-mobile-fix
dsh plugin --profile web add dsh-what-changed
dsh plugin --profile web add github:vlln/dsh-navbar
dsh plugin --profile web add github:huanyuLv/dsh-balance-tide
dsh plugin --profile web add github:christophersmith2737-commits/OffPeak
dsh plugin --profile web add github:dream12347/dsh-session-manager
dsh plugin --profile web add github:lire1131/dsh-undo-plugin
dsh plugin --profile web add github:baihejiangnan/dsh-topbar-manager
dsh plugin --profile web add github:hzhz314159/dsh-side-session
dsh plugin --profile web add "https://github.com/omdsh-dev/dsh-at-file/archive/refs/tags/v0.6.3.tar.gz"
dsh plugin --profile web add github:omdsh-dev/dsh-genui
dsh plugin --profile web add github:titanwings/dsh-automation
dsh plugin --profile web add github:omdsh-dev/dsh-notification
dsh plugin --profile web add dsh-status-rotator
dsh plugin --profile web add github:a179-sanae/dsh-auto-collapse#main
dsh plugin --profile web add github:lxzy-7/dsh-plugin-guard
dsh plugin --profile web add github:LX2000WASD/dsh-web-plugin-manager
dsh plugin --profile web add github:chenw2759-wq/dsh-plugin-healthcheck
dsh plugin --profile web add "https://codeload.github.com/baihejiangnan/dsh-settings-organizer/tar.gz/refs/tags/v1.1.0"
# dsh-skin (当前 profile 原为 workspace:*，建议按以下 GitHub 源安装)
dsh plugin --profile web add github:wei-806206088/dsh-skin
```

#### 3. 补丁配置

安装完成后，请检查 `~/.dsh/profiles/web/cordis.patch.yml`，确保包含以下内容（用于加载 `dsh-skin`，并保持我的默认 agent 预设）：

```yaml
# 可选：与我一致的默认 agent 预设
- id: agent-presets
  config:
    default: anchored-standard

# 插入 dsh-skin
- insert:
    - id: dsh-skin
      name: 'dsh-skin'
```

#### 4. 验证

- 启动 `dsh web`
- 在设置 → 插件中确认已加载上述 30 项
- 如有插件市场/管理插件，可再用它做一次完整性检查

### 插件明细（含版本与安装源）

| # | 包名 | 版本 | 安装源 | 命令 |
|---:|---|---|---|---|
| 1 | **@deepseek-ai/dsh-base** | 内置 | 官方内置 | 无需安装 |
| 2 | **@deepseek-ai/dsh-web-app** | 内置 | 官方内置 | 无需安装 |
| 3 | **@baihejiangnan/dsh-session-context-menu** | 0.2.14 | `github:baihejiangnan/dsh-session-context-menu` | `dsh plugin --profile web add github:baihejiangnan/dsh-session-context-menu` |
| 4 | **zat-dsh-engine** | 0.6.2 | `github:mishibeikejie/zat-dsh-engine` | `dsh plugin --profile web add github:mishibeikejie/zat-dsh-engine` |
| 5 | **@liustack/modlens** | 3.18.6 | `3.18.6` | `dsh plugin --profile web add @liustack/modlens` |
| 6 | **billion-context-dsh** | 0.2.2 | `^0.2.2` | `dsh plugin --profile web add billion-context-dsh` |
| 7 | **dsh-better-sidebar** | 0.12.3 | `^0.12.3` | `dsh plugin --profile web add dsh-better-sidebar` |
| 8 | **dsh-checkpoint-diff** | 0.5.0 | `^0.5.0` | `dsh plugin --profile web add dsh-checkpoint-diff` |
| 9 | **dsh-extension-hub** | 0.2.13 | `^0.2.13` | `dsh plugin --profile web add dsh-extension-hub` |
| 10 | **dsh-tdai-memory** | 0.2.10 | `^0.2.10` | `dsh plugin --profile web add dsh-tdai-memory` |
| 11 | **dsh-web-mobile-fix** | 1.0.2 | `^1.0.2` | `dsh plugin --profile web add dsh-web-mobile-fix` |
| 12 | **dsh-what-changed** | 0.4.0 | `^0.4.0` | `dsh plugin --profile web add dsh-what-changed` |
| 13 | **@vlln/dsh-navbar** | 0.3.0 | `github:vlln/dsh-navbar` | `dsh plugin --profile web add github:vlln/dsh-navbar` |
| 14 | **dsh-balance-tide** | 0.2.0 | `github:huanyuLv/dsh-balance-tide` | `dsh plugin --profile web add github:huanyuLv/dsh-balance-tide` |
| 15 | **dsh-offpeak** | 1.0.0 | `github:christophersmith2737-commits/OffPeak` | `dsh plugin --profile web add github:christophersmith2737-commits/OffPeak` |
| 16 | **dsh-session-manager** | 0.1.9 | `github:dream12347/dsh-session-manager` | `dsh plugin --profile web add github:dream12347/dsh-session-manager` |
| 17 | **dsh-undo-savepoint** | 0.3.5 | `github:lire1131/dsh-undo-plugin` | `dsh plugin --profile web add github:lire1131/dsh-undo-plugin` |
| 18 | **dsh-topbar-manager** | 0.3.0 | `github:baihejiangnan/dsh-topbar-manager` | `dsh plugin --profile web add github:baihejiangnan/dsh-topbar-manager` |
| 19 | **@dsh-external/dsh-side-session** | 0.3.0 | `github:hzhz314159/dsh-side-session` | `dsh plugin --profile web add github:hzhz314159/dsh-side-session` |
| 20 | **dsh-at-file** | 0.6.3 | `https://github.com/omdsh-dev/dsh-at-file/archive/refs/tags/v0.6.3.tar.gz` | `dsh plugin --profile web add "https://github.com/omdsh-dev/dsh-at-file/archive/refs/tags/v0.6.3.tar.gz"` |
| 21 | **@omdsh-dev/dsh-genui** | 0.8.7 | `github:omdsh-dev/dsh-genui` | `dsh plugin --profile web add github:omdsh-dev/dsh-genui` |
| 22 | **@dsh-external/dsh-automation** | 0.1.6 | `github:titanwings/dsh-automation` | `dsh plugin --profile web add github:titanwings/dsh-automation` |
| 23 | **dsh-notification** | 0.1.2 | `github:omdsh-dev/dsh-notification` | `dsh plugin --profile web add github:omdsh-dev/dsh-notification` |
| 24 | **dsh-status-rotator** | 0.3.0 | `^0.3.0` | `dsh plugin --profile web add dsh-status-rotator` |
| 25 | **dsh-auto-collapse** | 0.1.3 | `github:a179-sanae/dsh-auto-collapse#main` | `dsh plugin --profile web add github:a179-sanae/dsh-auto-collapse#main` |
| 26 | **dsh-plugin-guard** | 0.3.2 | `github:lxzy-7/dsh-plugin-guard` | `dsh plugin --profile web add github:lxzy-7/dsh-plugin-guard` |
| 27 | **dsh-web-plugin-manager** | 0.4.6 | `github:LX2000WASD/dsh-web-plugin-manager` | `dsh plugin --profile web add github:LX2000WASD/dsh-web-plugin-manager` |
| 28 | **dsh-plugin-healthcheck** | 0.1.0 | `github:chenw2759-wq/dsh-plugin-healthcheck` | `dsh plugin --profile web add github:chenw2759-wq/dsh-plugin-healthcheck` |
| 29 | **dsh-settings-organizer** | 1.1.0 | `https://codeload.github.com/baihejiangnan/dsh-settings-organizer/tar.gz/refs/tags/v1.1.0` | `dsh plugin --profile web add "https://codeload.github.com/baihejiangnan/dsh-settings-organizer/tar.gz/refs/tags/v1.1.0"` |
| 30 | **dsh-skin** | 1.0.0 | `github:wei-806206088/dsh-skin` | `dsh plugin --profile web add github:wei-806206088/dsh-skin` |

---

> 提示：命令中的版本/来源来自我 2026-08-19 的 profile/web 导出；如果某些插件已更新，安装结果可能与我的版本略有差异。



</details>

## 🔖 推荐 Topics

上传到 GitHub 后，建议给仓库添加以下 Topics：

```text
deepseek-harness, dsh, dsh-plugin, dsh-plugins, plugin-pack, dsh-plugin-pack-web, 插件包, deepseek, ai-plugins, profile-web, dsh-profile
```

## 🛠️ 自研兼容插件

为了尽可能提升本插件包在不同 DSH 环境下的兼容性，我加入了以下自研插件：

1. **dsh-settings-organizer**（兼容插件 1）  
   https://github.com/baihejiangnan/dsh-settings-organizer

2. **dsh-topbar-manager**（兼容插件 2）  
   https://github.com/baihejiangnan/dsh-topbar-manager

> 说明：以上 1 和 2 均为我自研的兼容性插件；它们用于帮助插件包在更多 DeepSeek Harness 版本/环境中稳定加载与使用。

## 🤝 致谢

感谢以下社区项目与作者：

- [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) — DSH 插件精选列表
- [dsh-market](https://github.com/dsh-market/dsh-market) — DSH 可视化插件市场
- 本插件包中所有第三方插件的作者与维护者
- DeepSeek Harness 社区

## 📄 开源证明

本仓库使用 **MIT License** 开源，详见 [`LICENSE`](LICENSE)。

---

> 数据导出时间：2026-08-19 ｜ 环境：`C:/Users/ABD18/.dsh/profiles/web`
