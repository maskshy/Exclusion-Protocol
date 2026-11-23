# 禁区协议 / Exclusion Protocol

> **Forge the exclusion. Survive the city.**
> A PVE urban survival modpack for Minecraft 1.20.1.

<!-- [一句话世界观 · 创造者手书位 —— 此处待创造者补笔] -->

Forge 1.20.1 · NeoForge 生态 512-mod 量级精选 · 当前版本 **v0.9.9**

---

## 这是什么

《禁区协议》是一部 PVE 城市生存整合包：废墟城市探索、模块化自研系统（黑市经济 / 体力涌泉）、性能组合拳打底——玩家唯一动作是**导入**，其余一切已固化进包。

PVP 永不关闭，但它已从核心卖点降级为外挂玩法——大地图环境下的争斗需要玩家自己权衡代价。

## 安装（唯一玩家动作）

1. 启动器（FCL 等支持 mrpack 的启动器）→ 导入整合包 → 选择本仓库 release 中的 `ExclusionProtocol_PC_vX.Y.Z.mrpack`
2. 等待自动下载与装配
3. 进世界

无手动配置、无前置依赖安装、无版本对齐——所有配置处方已烧入包内 `overrides`。

## 仓库结构

```
ExclusionProtocol/
├── modrinth.index.json     # mod 清单（URL + SHA1/SHA512 双哈希，不含任何 mod 二进制）
├── overrides/              # 配置、自研 mod、验收清单、预烧 defaultconfigs
│   ├── mods/               # 自研 jar + GPL 补丁件（附改动说明）
│   ├── defaultconfigs/     # 新世界零手动配置源
│   └── mods/安装说明与验收清单.txt
└── releases/               # 历版 mrpack
```

自研模组源码见姊妹仓库 **[ExclusionForge](../ExclusionForge)**。

## 版本史

| 版本 | 内容 |
|------|------|
| v0.9.9 | LC 双模板正路（common/server 分治 + 环境迁就城市） |
| v0.9.8 | LC NPE 绕道（哨兵 + 维度表） |
| v0.9.7 | 预烧模板格式修正 + 密度拉满 |
| v0.9.6 | 城市生成修复（selectedProfile 破案）+ 旧 GUI 清退 |
| v0.9.5 | CAS 崩溃终局修复（二进制 patch，GPL 合规） |
| v0.9.4 | 优化组合拳六件套 |
| v0.9.2 | 城市引擎入包（Lost Cities + Modern Tweaks） |
| v0.9.0 | 黑市终端批（ExclusionEconomy 0.2.0） |

## 权利声明

本仓库中由作者原创的内容（配置、文档、整合包结构、验收清单）**保留所有权利**。第三方模组归各自作者所有，按各自许可分发（`modrinth.index.json` 仅含 URL 与完整性哈希，不含任何 mod 二进制）。GPL 补丁件随包分发并附改动说明。自研模组（ExclusionEconomy / StaminaSurge）许可见姊妹仓库。

**本作作者 maskday（GitHub 账号 Shy）。** 自研 jar 内 authors 字段署名 maskday 与 Mask（工程协作署名），与本账号同属作者。
