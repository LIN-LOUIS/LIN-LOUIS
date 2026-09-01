
<div align="center">

# 你好，我是林致义 · Louis Lin 👋

### 多模态 AI · 医学 AI · 机器人视觉 · 具身智能 · AI Agent

**浙江财经大学 · 数据科学与大数据技术 本科在读**

📍 China &nbsp; | &nbsp; 📧 3165303925@qq.com

[English](./README_CN.md) · [GitHub](https://github.com/LIN-LOUIS)

</div>

---

## 👨‍💻 关于我

目前就读于**浙江财经大学数据科学与大数据技术专业**，研究和项目方向主要集中在人工智能与机器人交叉领域。

目前重点关注：

- 🧠 **多模态学习与大模型**
- 🏥 **医学人工智能与医学图像分析**
- 🤖 **机器人感知与具身智能**
- 👁️ **计算机视觉**
- 🛠️ **LLM Agent 与 AI 工程**

目前在**香港中文大学（深圳）王昌淼教授**指导下开展多模态皮肤病智能诊断相关研究。

同时具备 **RoboMaster 机器人视觉、医学 AI 项目以及具身智能行业研究**经历。

> 🎯 目前关注的实习方向：  
> **多模态大模型 / 大模型算法 / 机器人算法 / 具身智能 / VLA / Agent 开发**

---

## 🔬 研究方向

- **多模态 AI：** Vision-Language Learning、对比学习、图文检索
- **医学 AI：** 皮肤疾病分类、医学图像分析、模型评测
- **计算机视觉：** 目标检测、传统视觉、位姿估计
- **机器人：** 机器人视觉、ROS2、视觉控制、具身智能
- **LLM / Agent：** RAG、知识检索、Agent Workflow、多模态 Agent

---

# 🚀 核心项目

## 🩺 多模态皮肤病智能诊断

**项目负责人 / 核心算法开发**  
**指导教师：香港中文大学（深圳）王昌淼教授**

围绕皮肤病识别、多模态知识对齐、跨数据集泛化及模型可解释性开展医学多模态 AI 研究。

### 项目数据

- 👥 负责 **2 人科研团队**
- 💻 承担项目**全部核心算法代码开发**
- 🗂️ 处理 **15,849 条 SkinCon 样本**
- 📊 搭建 **3 类模型评测任务**
  - Zero-shot Classification
  - Multi-label Classification
  - Image-Text Retrieval
- 🧪 在 **5 类医学数据集**开展实验
  - SkinCon
  - HAM10000
  - ISIC
  - PAD-UFES-20
  - Derm7pt
- 📈 SkinCon 整体 **AUROC 达 0.797**
- 🔍 开展 Ablation Study 与 Bad Case Analysis
- 🧠 复现并实现 **HCE、CGBR** 等模块
- 🔗 探索对比学习在医学图像—文本语义对齐中的应用

### 模型流程

```text
医学图像 / Metadata / Text
             │
             ▼
          数据预处理
             │
             ▼
        分层特征提取
             │
             ▼
        概念关系推理
             │
             ▼
       图像-文本语义对齐
             │
             ▼
        多模态特征表示
             │
      ┌──────┼──────┐
      ▼      ▼      ▼
 Zero-shot 多标签分类 图文检索
```

### 技术栈

`Python` `PyTorch` `Medical AI` `Multimodal Learning`  
`Contrastive Learning` `Computer Vision` `Model Evaluation`

🔗 [Skin Cancer 项目仓库](https://github.com/LIN-LOUIS/Skin-cancer)

> 🚧 项目仍在持续完善，目前逐步整理训练、评测与实验代码。

---

## 🤖 RoboMaster 机器人视觉

**杭州电子科技大学 PHOENIX 战队 · 视觉组顾问**

围绕 RoboMaster 装甲板识别、视觉定位和机器人自瞄开展计算机视觉与机器人算法实践。

### 核心工作

- 🎯 参与 **RoboMaster 装甲板识别**
- 🧠 结合 **YOLOv5 + OpenCV 传统视觉**
- 👁️ 使用**工业相机**进行真实场景图像采集
- 💻 使用 **C++ / OpenCV** 开发视觉处理模块
- 🔍 完成灯条识别并提取 **6 个关键角点**
- 📐 基于 **PnP** 完成目标位姿及距离估计
- 🐧 在 **Linux** 环境完成算法开发与调试
- 🤖 了解机器人从视觉感知到控制输入的完整链路

### 视觉处理链路

```text
工业相机
   │
   ▼
 YOLOv5
候选目标检测
   │
   ▼
OpenCV 精处理
   │
   ├── Gaussian Blur
   ├── Canny
   ├── Morphology
   ├── Contour Detection
   └── Polygon Approximation
   │
   ▼
灯条 / 装甲板识别
   │
   ▼
关键点提取
   │
   ▼
  PnP
   │
   ▼
三维位姿估计
   │
   ▼
机器人控制输入
```

### 计算机视觉实践

- 透视变换
- 图像降噪
- 边缘检测
- 形态学处理
- 轮廓检测
- 灯条识别
- PyTorch CNN 模型训练

🔗 [PHOENIX 视觉组训练仓库](https://github.com/LIN-LOUIS/hdu_rm_ArmorNet.git)

---

# 💼 实习经历

## 🤖 具身智能 / AI 猎头实习生

**上海脉图 · 2026.07 – 至今**

聚焦**具身智能、人形机器人与智能硬件**赛道的人才研究及公司 Mapping。

- 🏢 累计 Mapping **50+ 家具身智能 / 机器人公司**
- 🔬 完成 **16 家企业深度 Mapping**
- 📄 筛选 **500+ 份技术人才简历**
- 📞 累计触达 **200+ 名候选人**
- 💬 完成 **60+ 次深度候选人沟通**
- 📤 完成 **30+ 名候选人推荐**
- 🎯 推动 **10+ 名候选人进入客户面试**
- ✅ 推动 **1 名 VLA 算法候选人完成 Offer 转化**

覆盖 **8+ 类核心岗位**：

`VLA` · `机器人算法` · `计算机视觉` · `硬件研发`  
`电机控制` · `质量` · `供应链` · `市场`

通过实习建立了对以下方向的系统理解：

- 具身智能公司与技术路线
- VLA / 机器人算法人才画像
- 机器人研发团队组织结构
- 算法与硬件团队分工
- 技术岗位能力评估
- 公司技术路线与组织 Mapping

---

## 🏥 医学 AI 项目实习生

**深圳市大数据研究院 · 2024.07 – 2024.09**

参与医学 AI / CV 方向项目的数据处理与模型评测工作。

- 使用 **Python 编写批量数据处理脚本**
- 完成医学数据清洗与标准化
- 检查异常样本和标签问题
- 参与模型测试与指标整理
- 分析模型预测结果
- 整理 Bad Case 与实验记录

---

# 🛠️ 技术栈

### AI / Deep Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

`CNN` `YOLOv5` `nnU-Net` `Contrastive Learning`  
`Multimodal Learning` `Zero-shot Classification` `Image-Text Retrieval`

### Robotics / System

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

`PnP` `TCP/UDP` `CAN` `串口通信` `Shell`

### LLM / Agent

`RAG` `LangChain` `Dify` `Knowledge Base`  
`Workflow Design` `Multimodal Retrieval`

### Development

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

`Python` `C` `C++` `R` `NumPy` `Pandas` `Git` `LaTeX`

---

# 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=LIN-LOUIS&show_icons=true&hide_border=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LIN-LOUIS&layout=compact&hide_border=true" />

</div>

---

# 🧭 目前正在做

- 🔬 多模态医学 AI
- 🩺 皮肤癌 / 皮肤病智能诊断
- 🧠 Vision-Language Models
- 🤖 机器人感知
- 🦾 具身智能与 VLA
- 🛠️ LLM Agent / RAG
- ⚙️ PyTorch / C++ / ROS2 工程能力提升

---

# 🎯 关注的机会

目前关注以下实习 / 科研方向：

**多模态大模型 · LLM · 医学 AI · CV · 机器人算法 · 具身智能 · VLA · AI Agent**

尤其希望参与：

> **AI Research × 真实工程落地 × Robotics**

相关项目。

---

# 📫 联系方式

- 📧 **Email：** 3165303925@qq.com
- 💻 **GitHub：** [@LIN-LOUIS](https://github.com/LIN-LOUIS)

---

<div align="center">

### Thanks for visiting 👋

**Research · Build · Iterate**

[English Version](./README.md)

</div>
````
