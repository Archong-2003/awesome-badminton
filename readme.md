# Awesome Badminton

[English](./readme.md) | [中文](./readme.zh-CN.md)

A curated list of badminton video analysis, match analysis, datasets, and automatic video clipping projects.

For bilingual README navigation on GitHub, keep the default English entry as `readme.md`, create a translated `readme.zh-CN.md`, and add language links at the top of both files. Keeping two files avoids making one README too long while still giving readers a simple language switch.

## Contents

* [Easy Start](#easy-start)
* [Datasets and Benchmarks](#datasets-and-benchmarks)
* [Badminton Video and Match Analysis](#badminton-video-and-match-analysis)
  * [Basic Visual Perception](#basic-visual-perception)
  * [Action and Event Analysis](#action-and-event-analysis)
  * [Integrated Systems and Tactical Analysis](#integrated-systems-and-tactical-analysis)
* [Badminton Video Clipping and Highlight Generation](#badminton-video-clipping-and-highlight-generation)

---

## Easy Start

Representative projects worth checking first, covering video analysis, application-style systems, and match data analysis.

* [SoloShuttlePose](https://github.com/sunwuzhou03/SoloShuttlePose) - Lightweight singles badminton analysis pipeline with court, net, player, shuttlecock and event detection.
  `recommended` `end-to-end` `video-analysis`

* [Good-Badminton](https://github.com/yo-WASSUP/Good-Badminton) - AI badminton Hawk-Eye style system; a useful reference for a more application-oriented badminton CV project.
  `recommended` `hawk-eye` `computer-vision`

* [CoachAI](https://github.com/wywyWang/CoachAI) - Badminton match data analysis platform based on deep learning; a good entry point for match data and tactical analysis.
  `recommended` `match-analysis` `tactical-analysis`

---

## Datasets and Benchmarks

Datasets, annotations and benchmarks for badminton video analysis, trajectory tracking, stroke recognition, match analysis and video clipping.

* [CoachAI-Projects](https://github.com/wywyWang/CoachAI-Projects) - Research projects around badminton analytics, including ShuttleSet, ShuttleSet22, stroke forecasting, movement forecasting, shot influence, RallyNet and CoachAI badminton environment.
  `dataset` `match-analysis` `tactical-analysis` `official`

* [Shuttlecock Trajectory Dataset](https://hackmd.io/@TUIK/rJkRW54cU) - Shuttlecock trajectory dataset used by TrackNet-style shuttlecock tracking methods.
  `dataset` `shuttlecock-tracking` `trajectory`

* [badminton-db](https://github.com/kwban/badminton-db) - Badminton database / dataset resource.
  `dataset` `badminton-db`

* [MM25-FineBadminton](https://github.com/iLearn-Lab/MM25-FineBadminton) - Fine-grained badminton video understanding dataset and benchmark.
  `dataset` `video-understanding` `fine-grained`

* [BST-Badminton-Stroke-type-Transformer](https://github.com/Va6lue/BST-Badminton-Stroke-type-Transformer) - Skeleton-based badminton stroke-type recognition project with data processing support for ShuttleSet, BadmintonDB and TenniSet.
  `dataset` `stroke-recognition` `skeleton` `transformer`

---

## Badminton Video and Match Analysis

Projects that extract information from badminton videos or structured match data, such as basic visual elements, player actions, hitting events, rally flow, statistics and tactical analysis.

### Basic Visual Perception

Projects focused on recognizing and locating the basic visual elements of badminton, including the court, net, shuttlecock, players, trajectories, positions and spatial mapping.

* [TrackNet-Badminton-Tracking-tensorflow2](https://github.com/Chang-Chia-Chi/TrackNet-Badminton-Tracking-tensorflow2) - TensorFlow2 implementation of TrackNet for badminton shuttlecock tracking.
  `shuttlecock-tracking` `tracknet` `tensorflow2`

* [TrackNetV3](https://github.com/qaz812345/TrackNetV3) - Shuttlecock tracking with trajectory prediction and rectification.
  `shuttlecock-tracking` `trajectory-prediction` `trajectory-rectification` `pytorch`

* [Badminton-Analysis](https://github.com/ToanNguyenKhanh/Badminton-Analysis) - Computer vision project for detecting players and shuttlecocks in badminton games.
  `player-detection` `shuttlecock-detection` `computer-vision`

* [Good-Badminton](https://github.com/yo-WASSUP/Good-Badminton) - AI badminton Hawk-Eye style system.
  `hawk-eye` `computer-vision` `spatial-analysis`

* [badminton-ai-vision](https://github.com/AnInsomniacy/badminton-ai-vision) - AI vision project for badminton analysis.
  `computer-vision` `ai-vision`

* [badminton-pipeline-repro](https://github.com/ychenfen/badminton-pipeline-repro) - Reproduction-style badminton video analysis pipeline.
  `pipeline` `court-mapping` `player-tracking` `video-analysis`

* [Badminton-tracking](https://github.com/vascokk/Badminton-tracking) - Badminton tracking project.
  `tracking` `badminton`

* [Competition-2023-PyTorch-Badminton](https://github.com/FanChiMao/Competition-2023-PyTorch-Badminton) - PyTorch badminton competition project related to shuttlecock tracking / detection.
  `competition` `pytorch` `tracking`

---

### Action and Event Analysis

Projects that go beyond basic visual recognition to analyze player motion, pose, stroke type, hit timing, hitting events, trajectory changes and rally-level events.

* [badminton-pose-analysis](https://github.com/deepaktalwardt/badminton-pose-analysis) - Pose analysis and shot classification for badminton coaching and pose correction.
  `pose-estimation` `shot-classification` `coaching`

* [badminton_training](https://github.com/youngzs/badminton_training) - Badminton posture recognition and movement distance estimation.
  `pose-estimation` `training` `movement-analysis`

* [Badminton-AI-coach](https://github.com/ChengChen-0312/Badminton-AI-coach) - AI coaching / training assistant for badminton.
  `ai-coach` `pose-estimation` `training`

* [qualitative-badminton-player-analysis](https://github.com/lgupta-mle/qualitative-badminton-player-analysis) - Qualitative badminton player analysis project.
  `player-analysis` `qualitative-analysis`

* [Automated-Hit-frame-Detection-for-Badminton-Match-Analysis](https://github.com/arthur900530/Automated-Hit-frame-Detection-for-Badminton-Match-Analysis) - Official implementation for automated hit-frame detection in badminton match analysis.
  `hit-frame-detection` `event-detection` `match-analysis`

* [A-New-Perspective-for-Shuttlecock-Hitting-Event-Detection](https://github.com/wish44165/A-New-Perspective-for-Shuttlecock-Hitting-Event-Detection) - Shuttlecock hitting event detection project.
  `hitting-event-detection` `event-detection`

---

### Integrated Systems and Tactical Analysis

Projects that organize multiple modules into complete analysis systems, or directly focus on match understanding, data analysis, tactical analysis and coaching reports.

* [SoloShuttlePose](https://github.com/sunwuzhou03/SoloShuttlePose) - Lightweight singles badminton analysis pipeline with court, net, player, shuttlecock and event detection.
  `end-to-end` `court-detection` `net-detection` `player-detection` `shuttlecock-tracking` `event-detection`

* [Badminton_Analytics_Project](https://github.com/muhammadyasin79/Badminton_Analytics_Project) - Badminton analytics project with shuttlecock detection, pose estimation and player movement analysis.
  `end-to-end` `analytics` `pose-estimation` `movement-analysis`

* [BadmintonAnalyticsCV](https://github.com/Siddharth194/BadmintonAnalyticsCV) - Badminton analytics project using TrackNet / YOLO-style computer vision modules.
  `computer-vision` `analytics` `highlight-generation`

* [Badminton-VisionAI](https://github.com/CJMK1/Badminton-VisionAI) - Badminton vision AI project.
  `vision-ai` `video-analysis`

* [CoachAI](https://github.com/wywyWang/CoachAI) - Badminton match data analysis platform based on deep learning.
  `coachai` `match-analysis` `deep-learning`

---

## Badminton Video Clipping and Highlight Generation

Projects focused on cutting, extracting, filtering, editing or generating highlights from badminton match videos.

* [badminton_video_edit_analyze](https://github.com/CptJack333/badminton_video_edit_analyze) - Badminton video editing and analysis project.
  `video-editing` `video-analysis`

* [huji](https://github.com/hhoao/huji) - Cross-platform AI sports video clipping application for table tennis and badminton.
  `automatic-editing` `video-clipping` `badminton` `table-tennis`

* [MatchClip-AI](https://github.com/kevin24067/MatchClip-AI) - Sports / badminton match clipping project.
  `match-clipping` `automatic-editing`
