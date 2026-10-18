# BCSFE-Chinese-Locale

BCSFE-Python（Battle Cats Save Editor for Python）的**简体中文（zh-CN）语言包**附属项目。

- 上游项目：https://codeberg.org/fieryhenry/BCSFE-Python （GitHub 镜像：https://github.com/fieryhenry/BCSFE-Python）
- 官方本地化说明：见上游仓库 `LOCALIZATION.md`

## 覆盖情况

- 语言代码：`zh-CN`
- 与官方英文基准完全对齐：**800 / 800 键**，无缺失、无多余
- 所有 `{key}` / `{{key}}` 占位符与色彩标签（`<@q>` `<@t>` `<@s>` `<@e>` `<@w>` `<@su>`）均与 en 一致
- 术语对照猫咪大战争简体中文社区/维基核实（加码多多、城堡宝开发队、猫炮、猫薄荷、喵力达、首领旗、白金券、传说券等）

## 安装方法

### 方法一：复制目录（本地）

将本仓库的 `zh-CN` 目录复制到：

```
src/bcsfe/files/locales/zh-CN/
```

重启编辑器后，在语言菜单选择「简体中文」即可。

### 方法二：编辑器内直接拉取外部语言包

在编辑器的语言管理功能中，输入本仓库地址：

```
https://github.com/laihainb666/BCSFE-Chinese-Locale.git
```

即可自动安装 / 检查更新。

## 目录结构

```
zh-CN/
├── metadata.json          # 语言包元数据（名称 / 作者）
├── core/                  # 核心界面文案（9 个文件）
└── edits/                 # 存档编辑功能文案（18 个文件）
```

## 维护

- 作者：Marvis（由用户 laihainb666 托管）
- 上游 en 基准更新后，本包会同步补齐新增键并重新校验。
