# 熊猫秘境·生态叙事 —— MR混合现实大熊猫保护教育平台

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Unreal Engine](https://img.shields.io/badge/UE5-0A0A0A.svg)
![MR/AR](https://img.shields.io/badge/MR-VR%2FAR-green)

成都数字媒体技术毕业设计 | 挑战杯/互联网+ 参赛项目

## 项目简介
基于成都大熊猫基地与雅安碧峰峡真实生态数据，打造**MR混合现实沉浸式熊猫栖息地**。用户可“走进”竹林，与AI驱动的虚拟熊猫互动，亲身感受气候变化对栖息地的影响，并创作保护故事。

**核心亮点**：真实数据 + MR沉浸 + AI叙事 + 用户共创

## 技术栈
- **引擎**：Unreal Engine 5.4+
- **MR框架**：OpenXR + MRTK
- **AI**：通义千问 / Grok / Kimi（角色对话 + 故事生成）
- **轻量版**：WebXR / Unity AR Foundation
- **数据**：GIS + 公开生态数据

## 快速开始
1. Clone 本仓库
2. 打开 WebAR_Version 文件夹，用浏览器打开 index.html 体验网页版
3. Unreal 项目在 PandaMR_Main 文件夹

## 核心功能
- MR/AR进入真实感熊猫栖息地
- 虚拟熊猫行为AI模拟与互动
- 气候变化前后对比可视化
- AI熊猫对话 + 用户故事创作分享
- 生态知识学习与保护行动打卡

## 价值
- **商业**：景区导览、教育课程、数字文创
- **社会**：生物多样性教育、野生动物保护、碳中和宣传

⭐ Star 支持一下！

## 项目结构
```bash
PandaRealm-EcoMR/
├── README.md
├── WebAR_Version/          # H5/WebXR轻量版
├── PandaMR_Main/           # Unreal Engine MR主项目
├── Docs/                   # 毕设文档、论文
├── Prompts/                # AI Prompt库
├── Assets/                 # 模型、贴图
└── LICENSE
```