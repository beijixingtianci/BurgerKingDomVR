# BurgerKingDom VR

VR 汉堡店经营模拟游戏 —— 在虚拟现实中亲手制作汉堡并管理你的餐厅。

---

## 团队成员

| 姓名 | 负责模块 |
|---|---|
| 유흡 | 汉堡制作系统、顾客点单系统 |
| 유일연 | VR 环境搭建、店铺空间及交互开发 |
| 손천익 | 经济系统实现、商店系统开发 |
| 장양 | 游戏测试与数值平衡、UI 设计 |

---

## 开发环境

- Unity 2022.3.62f3 LTS
- Meta XR SDK / XR Interaction Toolkit
- Git + GitHub（配合 Git LFS 管理大型资源）

---

## 分支说明

| 分支 | 用途 |
|---|---|
| `main` | 稳定发布版本，随时可运行 |
| `develop` | 日常集成分支，所有新功能先合并到这里 |
| `feature/*` | 个人功能开发分支（如 `feature/grill-system`） |

---

## 如何开始

1. 克隆仓库到本地
2. 使用 **Unity 2022.3.62f3 LTS** 打开项目
3. 切换到 `develop` 分支获取最新开发进度

---

## 项目结构

Assets/
_Imported/ ← 第三方插件、SDK
_Project/
Art/ ← 模型、贴图、材质
Audio/ ← 音效、音乐
Prefabs/ ← 预制体
Scenes/ ← 场景文件
Scripts/ ← 所有 C# 脚本
Settings/ ← XR 配置等
