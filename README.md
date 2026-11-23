# Exclusion Protocol

> **Forge the exclusion. Survive the city.**
> A PVE urban survival modpack for Minecraft 1.20.1.

<!-- [One-line worldview — reserved for the Creator's own words] -->

Forge 1.20.1 · Latest release: see **Releases**

---

## What is this

Exclusion Protocol is a PVE urban survival modpack: ruined-city exploration, modular in-house systems (black-market economy / stamina surge), performance-tuned at the core. The player's only action is **import** — everything else is baked into the pack.

PVP is never disabled, but it has been demoted from core selling point to optional play — in a large open world, conflict carries costs the player must weigh.

## Installation (the only player action)

1. Launcher (any mrpack-capable launcher, e.g. Prism Launcher) → Import modpack → pick `ExclusionProtocol_PC_vX.Y.Z.mrpack` from this repo's releases
2. Wait for automatic download & assembly
3. Enter the world

No manual configuration, no dependency installs, no version alignment — every config prescription is baked into `overrides`.

## Repository layout

```
ExclusionProtocol/
├── modrinth.index.json     # mod manifest (URLs + SHA1/SHA512 dual hashes, no mod binaries)
├── overrides/              # configs, in-house mods, acceptance checklist, pre-baked default_configs
│   ├── mods/               # in-house jars + GPL-patched builds (with change notes)
│   ├── defaultconfigs/     # zero-manual-config source for new worlds
│   └── mods/安装说明与验收清单.txt  (installation guide & acceptance checklist)
└── releases/               # historical mrpack builds
```

In-house mod sources live in the sister repo **[ExclusionForge](../ExclusionForge)**.

## Version history

Full changelog and per-version downloads live on the **Releases** page — each release is a new entry, this file requires zero maintenance.

## Rights

All original content in this repository (configs, docs, modpack structure, acceptance checklists) is **All Rights Reserved** by the author. Third-party mods belong to their respective authors and are distributed under their own licenses (`modrinth.index.json` contains URLs and integrity hashes only, no mod binaries). GPL-patched builds ship with the pack along with change notes. For in-house mod licenses (ExclusionEconomy / StaminaSurge), see the sister repo.

**The author is maskday (GitHub: Shy).** The in-house jars' `authors` fields credit maskday and Mask (engineering collaboration) — both refer to the same author as this account.

## Contact

heiyimianju (at) gmail (dot) com

---

# 禁区协议（中文版）

> **Forge the exclusion. Survive the city.**
> 一部 PVE 城市生存整合包，Minecraft 1.20.1。

<!-- [一句话世界观 · 创造者手书位 —— 此处待创造者补笔] -->

Forge 1.20.1 · 最新版本见 **Releases**

---

## 这是什么

《禁区协议》是一部 PVE 城市生存整合包：废墟城市探索、模块化自研系统（黑市经济 / 体力涌泉）、性能组合拳打底——玩家唯一动作是**导入**，其余一切已固化进包。

PVP 永不关闭，但它已从核心卖点降级为外挂玩法——大地图环境下的争斗需要玩家自己权衡代价。

## 安装（唯一玩家动作）

1. 启动器（PCL2 等支持 mrpack 的启动器）→ 导入整合包 → 选择本仓库 release 中的 `ExclusionProtocol_PC_vX.Y.Z.mrpack`
2. 等待自动下载与装配
3. 进世界

无手动配置、无前置依赖安装、无版本对齐——所有配置处方已烧入包内 `overrides`。

## 仓库结构

```
ExclusionProtocol/
├── modrinth.index.json     # mod 清单（URL + SHA1/SHA512 双哈希，不含任何 mod 二进制）
├── overrides/              # 配置、自研 mod、验收清单、预烧 default_configs
│   ├── mods/               # 自研 jar + GPL 补丁件（附改动说明）
│   ├── defaultconfigs/     # 新世界零手动配置源
│   └── mods/安装说明与验收清单.txt
└── releases/               # 历版 mrpack
```

自研模组源码见姊妹仓库 **[ExclusionForge](../ExclusionForge)**。

## 版本史

完整版本史与各版下载见仓库 **Releases** 页——每次发版只新增 release，本文件零维护。

## 权利声明

本仓库中由作者原创的内容（配置、文档、整合包结构、验收清单）**保留所有权利**。第三方模组归各自作者所有，按各自许可分发（`modrinth.index.json` 仅含 URL 与完整性哈希，不含任何 mod 二进制）。GPL 补丁件随包分发并附改动说明。自研模组（ExclusionEconomy / StaminaSurge）许可见姊妹仓库。

**本作作者 maskday（GitHub 账号 Shy）。** 自研 jar 内 authors 字段署名 maskday 与 Mask（工程协作署名），与本账号同属作者。

## 联系

heiyimianju (at) gmail (dot) com
