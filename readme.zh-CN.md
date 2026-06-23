# Awesome Badminton

[English](./readme.md) | [中文](./readme.zh-CN.md)

羽毛球视频分析、比赛分析、数据集与自动剪辑项目综述。

## 目录

* [推荐上手](#推荐上手)
* [数据集与基准](#数据集与基准)
* [羽毛球视频与比赛分析](#羽毛球视频与比赛分析)
  * [基础视觉感知](#基础视觉感知)
  * [动作与事件分析](#动作与事件分析)
  * [综合系统与战术分析](#综合系统与战术分析)
* [羽毛球视频剪辑与集锦生成](#羽毛球视频剪辑与集锦生成)

---

## 推荐上手

适合优先了解或尝试的代表性项目，覆盖视频分析、应用系统和比赛数据分析等常见入口。

* [SoloShuttlePose](https://github.com/sunwuzhou03/SoloShuttlePose) - 轻量级单打羽毛球分析流程，覆盖场地、球网、球员、羽毛球和事件检测。
  `推荐` `端到端` `视频分析`

* [Good-Badminton](https://github.com/yo-WASSUP/Good-Badminton) - AI 羽毛球鹰眼系统，适合作为应用型羽毛球视觉项目参考。
  `推荐` `鹰眼` `计算机视觉`

* [CoachAI](https://github.com/wywyWang/CoachAI) - 基于深度学习的羽毛球比赛数据分析平台，适合从比赛数据和战术分析角度入门。
  `推荐` `比赛分析` `战术分析`

---

## 数据集与基准

羽毛球视频分析、轨迹跟踪、击球识别、比赛分析和视频剪辑相关的数据集、标注与基准。

* [CoachAI-Projects](https://github.com/wywyWang/CoachAI-Projects) - 羽毛球分析研究项目集合，包括 ShuttleSet、ShuttleSet22、击球预测、移动预测、击球影响、RallyNet 和 CoachAI 羽毛球环境。
  `数据集` `比赛分析` `战术分析` `官方`

* [Shuttlecock Trajectory Dataset](https://hackmd.io/@TUIK/rJkRW54cU) - TrackNet 类羽毛球跟踪方法使用的羽毛球轨迹数据集。
  `数据集` `羽毛球跟踪` `轨迹`

* [badminton-db](https://github.com/kwban/badminton-db) - 羽毛球数据库 / 数据集资源。
  `数据集` `badminton-db`

* [MM25-FineBadminton](https://github.com/iLearn-Lab/MM25-FineBadminton) - 细粒度羽毛球视频理解数据集与基准。
  `数据集` `视频理解` `细粒度`

* [BST-Badminton-Stroke-type-Transformer](https://github.com/Va6lue/BST-Badminton-Stroke-type-Transformer) - 基于骨架的羽毛球击球类型识别项目，并提供 ShuttleSet、BadmintonDB、TenniSet 等数据处理支持。
  `数据集` `击球识别` `骨架` `transformer`

---

## 羽毛球视频与比赛分析

这类项目从羽毛球视频或结构化比赛数据中提取信息，例如基础视觉要素、球员动作、击球事件、回合过程、统计结果和战术分析。

### 基础视觉感知

主要识别和定位羽毛球运动中的基础要素，包括场地、球网、羽毛球、球员、轨迹、位置和空间映射。

* [TrackNet-Badminton-Tracking-tensorflow2](https://github.com/Chang-Chia-Chi/TrackNet-Badminton-Tracking-tensorflow2) - TrackNet 羽毛球跟踪的 TensorFlow2 实现。
  `羽毛球跟踪` `tracknet` `tensorflow2`

* [TrackNetV3](https://github.com/qaz812345/TrackNetV3) - 带轨迹预测与轨迹修正的羽毛球跟踪项目。
  `羽毛球跟踪` `轨迹预测` `轨迹修正` `pytorch`

* [Badminton-Analysis](https://github.com/ToanNguyenKhanh/Badminton-Analysis) - 使用计算机视觉检测羽毛球比赛中的球员和羽毛球。
  `球员检测` `羽毛球检测` `计算机视觉`

* [Good-Badminton](https://github.com/yo-WASSUP/Good-Badminton) - AI 羽毛球鹰眼系统。
  `鹰眼` `计算机视觉` `空间分析`

* [badminton-ai-vision](https://github.com/AnInsomniacy/badminton-ai-vision) - 羽毛球分析相关 AI 视觉项目。
  `计算机视觉` `ai-vision`

* [badminton-pipeline-repro](https://github.com/ychenfen/badminton-pipeline-repro) - 复现型羽毛球视频分析流程。
  `流程` `场地映射` `球员跟踪` `视频分析`

* [Badminton-tracking](https://github.com/vascokk/Badminton-tracking) - 羽毛球跟踪项目。
  `跟踪` `羽毛球`

* [Competition-2023-PyTorch-Badminton](https://github.com/FanChiMao/Competition-2023-PyTorch-Badminton) - PyTorch 羽毛球比赛项目，和羽毛球跟踪 / 检测相关。
  `比赛` `pytorch` `跟踪`

---

### 动作与事件分析

在基础视觉识别之上，进一步分析球员动作、姿态、击球类型、击球时刻、击球事件、球路变化和回合内事件。

* [badminton-pose-analysis](https://github.com/deepaktalwardt/badminton-pose-analysis) - 面向羽毛球训练与姿势纠正的姿态分析和击球分类项目。
  `姿态估计` `击球分类` `训练辅助`

* [badminton_training](https://github.com/youngzs/badminton_training) - 羽毛球姿态识别与移动距离估计。
  `姿态估计` `训练` `移动分析`

* [Badminton-AI-coach](https://github.com/ChengChen-0312/Badminton-AI-coach) - 羽毛球 AI 教练 / 训练辅助项目。
  `ai-coach` `姿态估计` `训练`

* [qualitative-badminton-player-analysis](https://github.com/lgupta-mle/qualitative-badminton-player-analysis) - 羽毛球运动员定性分析项目。
  `球员分析` `定性分析`

* [Automated-Hit-frame-Detection-for-Badminton-Match-Analysis](https://github.com/arthur900530/Automated-Hit-frame-Detection-for-Badminton-Match-Analysis) - 羽毛球比赛分析中自动击球帧检测的官方实现。
  `击球帧检测` `事件检测` `比赛分析`

* [A-New-Perspective-for-Shuttlecock-Hitting-Event-Detection](https://github.com/wish44165/A-New-Perspective-for-Shuttlecock-Hitting-Event-Detection) - 羽毛球击球事件检测项目。
  `击球事件检测` `事件检测`

---

### 综合系统与战术分析

汇总把多个模块组织起来的完整分析系统，或直接面向比赛理解、数据分析、战术分析和教练报告的项目。

* [SoloShuttlePose](https://github.com/sunwuzhou03/SoloShuttlePose) - 轻量级单打羽毛球分析流程，覆盖场地、球网、球员、羽毛球和事件检测。
  `端到端` `场地检测` `球网检测` `球员检测` `羽毛球跟踪` `事件检测`

* [Badminton_Analytics_Project](https://github.com/muhammadyasin79/Badminton_Analytics_Project) - 包含羽毛球检测、姿态估计和球员移动分析的羽毛球分析项目。
  `端到端` `分析` `姿态估计` `移动分析`

* [BadmintonAnalyticsCV](https://github.com/Siddharth194/BadmintonAnalyticsCV) - 使用 TrackNet / YOLO 类模块的羽毛球分析项目。
  `计算机视觉` `分析` `集锦生成`

* [Badminton-VisionAI](https://github.com/CJMK1/Badminton-VisionAI) - 羽毛球视觉 AI 项目。
  `vision-ai` `视频分析`

---

## 羽毛球视频剪辑与集锦生成

这类项目关注对羽毛球比赛视频进行切分、抽取、过滤、编辑或集锦生成。

* [badminton_video_edit_analyze](https://github.com/CptJack333/badminton_video_edit_analyze) - 羽毛球视频编辑与分析项目。
  `视频编辑` `视频分析`

* [huji](https://github.com/hhoao/huji) - 跨平台 AI 运动视频剪辑应用，支持乒乓球和羽毛球。
  `自动剪辑` `视频剪辑` `羽毛球` `乒乓球`

* [MatchClip-AI](https://github.com/kevin24067/MatchClip-AI) - 运动 / 羽毛球比赛剪辑项目。
  `比赛剪辑` `自动剪辑`
