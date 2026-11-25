# pkg3certifiction

pkgtool 核心形式化与治理文档的存证仓库（certification / proof-of-authorship snapshot）。

## 仓库用途

本仓库用于在公开时间线上固定 pkgtool 项目核心文档的存在时间与作者署名，作为「第一提出者 / 原创者」的存证。仓库内的 `Document.7z` 为作者整理并加密（密码保护）的核心文档归档。

## 作者与版权

- 作者：Yu Yiming
- 联系邮箱：yu3174096586@gmail.com
- GitHub：https://github.com/yuyimimimi
- 版权：Copyright © 2026 Yu Yiming. All rights reserved.

## 归档内容（`Document.7z` 解密后，共 33 份文档）

核心理论 / 形式化：

- 04-架构设计规约.md —— 架构设计规约（理论本体）
- 91-对象依赖图检测规则法.md —— 对象依赖图检测规则法（可执行形式化，LAW / DERIVED / OPEN 三层规则）
- 90-Gen3静态分析流水线.md —— Gen3 静态分析流水线
- 81-后端统一设计语言.md —— 后端统一设计语言
- 42-用户架构思维与指导方式蒸馏.md —— 用户架构思维与指导方式

架构 / 治理 / 证据：

- 00-项目总入口.md —— 项目总入口与全貌
- 01-项目章程与协作规则.md、05-状态问题与风险台账.md、07-决策记录ADR.md、08-术语证据与文件索引.md
- 11 / 13 / 14 / 17 / 22 / 23 / 24 / 47 / 93 / 96 / 98 / 99 —— 架构、模块、包与对象绑定等核心规范
- gen2_PROJECT-MANUAL.md、gen2_ARCHITECTURE-TOPOLOGY.md、gen2_NODE-MODEL.md、gen2_API-CONTRACT.md、gen2_DECISIONS.md、gen2_RISK-REGISTER.md、gen2_ROADMAP.md、gen2_SOURCE-CLASSIFICATION.md、gen2_STANDARD-SUBSYSTEM.md —— 治理与工程证据
- 顶层_PROJECT-MANUAL.md —— 顶层项目管理
- AUTHORS.md —— 作者与版权声明

## 备注

- 本仓库仅作存证，不构成对任何第三方内容的授权。
- 未经作者书面许可，不得复制、分发或用于商业用途。

## 存证指纹

- 加密归档 `Document.7z` 的 SHA-256：

```
CF1DEA81D0948610FC4FC4077EB056E538CDF989C9D3B9262024500B7CE140AE
```

- 解密后原文（上述 33 份文档，按文件名排序取各文件 SHA-256 后汇总）的清单指纹 SHA-256：

```
1736427d88342d1769a0ed5f647a98c5bdab61ededaa9844aaaaf61dd24dc495
```

`Document.7z` 为加密归档，解密密码由作者持有；原文清单指纹用于验真（作者可在需要时解密并公开内容，使指纹对得上）。
