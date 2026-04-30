🍔 BurgerKingDom VR

VR 汉堡店经营模拟游戏 —— 在虚拟现实中亲手制作汉堡并管理你的餐厅。

👥 团队成员
姓名	负责模块
유흡	汉堡制作系统、顾客点单系统
유일연	VR 环境搭建、店铺空间及交互开发
손천익	经济系统实现、商店系统开发
장양	游戏测试与数值平衡、UI 设计
🛠 开发环境
Unity 2022.3.62f3 LTS
Meta XR SDK / XR Interaction Toolkit
Git + GitHub（使用 Git LFS 管理大型资源）
🌿 分支说明
分支	用途
main	稳定发布版本（随时可运行）
develop	日常开发集成分支
feature/*	功能开发分支（如 feature/grill-system）
🚀 如何开始
# 1. 克隆仓库
git clone <your-repo-url>

# 2. 进入项目目录
cd BurgerKingDom-VR

# 3. 切换到开发分支
git checkout develop

然后使用 Unity Hub 打开项目（版本：2022.3.62f3 LTS）

📂 项目结构
Assets/
├── _Imported/            # 第三方插件、SDK
│
└── _Project/
    ├── Art/              # 模型、贴图、材质
    ├── Audio/            # 音效、音乐
    ├── Prefabs/          # 预制体
    ├── Scenes/           # 场景文件
    ├── Scripts/          # C# 脚本
    └── Settings/         # XR 配置等
📌 项目特点
🍔 真实汉堡制作流程（切菜 / 烤肉 / 组装）
🧾 顾客点单与排队系统
💰 动态经济系统（收入 / 成本 / 升级）
🕶 沉浸式 VR 交互体验

⚠️ 常见问题
打不开项目 → 检查 Unity 版本
XR 无法运行 → 检查 Meta XR SDK 是否正确导入
大文件拉取失败 → 确认 Git LFS 已安装
