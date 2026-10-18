---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 26b76dd11f08eea463a4908e7791bc6b_94ac1484cac711f18e0e52540064ee0f
    ReservedCode1: hipLqmuStOpOJTax7srwKN2wMYINfL537GamYqtOx7P0YxEOgHWG7eIwqv4oyP01fQPFThN7e7Pos4YrKAyNq54mhfcNsoNPS83b4HplQsNHikmEY7S3L6FjZeNo3LaHhRUBROLo99/WhVzC5MDC6mbEmzF9BhGN/hxkU652x0Dl8ekCo3sunG2WmfA=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 26b76dd11f08eea463a4908e7791bc6b_94ac1484cac711f18e0e52540064ee0f
    ReservedCode2: hipLqmuStOpOJTax7srwKN2wMYINfL537GamYqtOx7P0YxEOgHWG7eIwqv4oyP01fQPFThN7e7Pos4YrKAyNq54mhfcNsoNPS83b4HplQsNHikmEY7S3L6FjZeNo3LaHhRUBROLo99/WhVzC5MDC6mbEmzF9BhGN/hxkU652x0Dl8ekCo3sunG2WmfA=
---



# BCSFE-Chinese-Locale

BCSFE-Python（Battle Cats Save Editor for Python）的**简体中文（zh-CN）语言包**附属项目。

- 上游项目：https://codeberg.org/fieryhenry/BCSFE-Python （GitHub 镜像：https://github.com/fieryhenry/BCSFE-Python）
- 官方本地化说明：见上游仓库 `LOCALIZATION.md`

## 这是什么格式

本仓库采用 BCSFE-Python **标准外部语言包（External Locale）** 格式：

- 根目录 `locale.json`：外部语言包声明（名称 / 作者 / 版本）
- `files/`：语言包内容（`metadata.json` + `core/` + `edits/`），运行时会被复制到外部语言包目录

## 覆盖情况

- 语言代码：`zh-CN`
- 与官方英文基准完全对齐：**800 / 800 键**，无缺失、无多余
- 所有 `{key}` / `{{key}}` 占位符与色彩标签（`<@q>` `<@t>` `<@s>` `<@e>` `<@w>` `<@su>`）均与 en 一致
- 术语对照猫咪大战争简体中文社区/维基核实（加码多多、城堡宝开发队、猫炮、猫薄荷、喵力达、首领旗、白金券、传说券等）

## 安装方法

### 方法一：编辑器内直接安装（推荐，支持一键更新）

在 BCSFE-Python 编辑器的语言管理功能中，输入本仓库地址：

```
https://github.com/laihainb666/BCSFE-Chinese-Locale.git
```

即可自动安装。以后版本更新，在编辑器里执行「更新外部内容」即可拉取最新版，无需手动拷贝。

### 方法二：手动复制

将本仓库 `files/` 目录下的 `metadata.json`、`core/`、`edits/` 三个内容，放到 BCSFE 的**数据文件夹**的 `locales/zh-CN/` 下（注意：不是源码目录 `src/bcsfe/files/locales/`）：

| 平台 | 语言包目录 |
|---|---|
| Windows | `%USERPROFILE%\Documents\bcsfe\locales\zh-CN\` |
| Linux / Termux | `~/.local/share/bcsfe/locales/zh-CN\` |
| macOS | `~/Documents/bcsfe/locales/zh-CN/` |

放置完成后**完全重启**编辑器，在语言菜单选择「简体中文」。

## 目录结构

```
BCSFE-Chinese-Locale/
├── locale.json          # 外部语言包声明（名称 / 作者 / 版本）
└── files/               # 语言包内容
    ├── metadata.json    # 语言包元数据
    ├── core/            # 核心界面文案（9 个文件）
    └── edits/           # 存档编辑功能文案（19 个文件）
```

## 维护

- 作者：Marvis（由用户 laihainb666 托管）
- 上游 en 基准更新后，本包会同步补齐新增键并重新校验。
*（内容由AI生成，仅供参考）*
