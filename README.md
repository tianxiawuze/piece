# 铝板模态振动分析

Abaqus 频率提取（Frequency Step）+ AutoCAD 板件草图，课程练习。

## 文件

| 文件 | 说明 |
| --- | --- |
| `a1.cae` | Abaqus 模型：部件、材料（Elastic + Density）、截面、网格与频率提取步 |
| `a1.jnl` | Abaqus 操作日志，可在 CAE 中重放重建模型 |
| `Drawing1.dxf` | AutoCAD 板件轮廓草图（约 40 × 34） |
| `Drawing1.bak` | AutoCAD 自动备份，未纳入版本管理 |

## 复现

1. 用 Abaqus CAE 打开 `a1.cae`，提交 `Job-1` 求解；
2. 或在 CAE 中 `File > Run Script` 运行 `a1.jnl`，自动重建整个模型。