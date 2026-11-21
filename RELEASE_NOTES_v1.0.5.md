# 白银龙娘 v1.0.5

## v1.0.5 修复内容

- 走路、奔跑和飞行在准备、循环、收势切换前预读下一段的多页图集，单次动作结束前预读待机图集，减少等待解码造成的停顿。
- 逐帧处理 636 张无损 WebP 图集的 4,931 帧，清除 4,889 处轮廓外的孤立低 Alpha 杂点，校正 171,066 个低 Alpha 边缘像素的串色。通过相邻帧的位置判断保留淡入淡出的特效粒子。
- 沿用 v1.0.4 的原帧序、分辨率、音效和形象 ID。

## 下载

从发布附件下载完整形象包。 [ChatGPT_Silver_Dragon_Coopanion_v1.0.5.zip](https://github.com/ArtemisCode-arch/ChatGPT_DragonGirl_for_Coopanion/releases/download/v1.0.5/ChatGPT_Silver_Dragon_Coopanion_v1.0.5.zip)

在 Coopanion 打开「设置 → 装扮 → 导入」，选择 ZIP。更新旧版时选择「替换」。

## 校验

- 文件大小 1,175,843,702 字节
- SHA-256 `8cf5d52f4911b1949573ee3ada9e2bcaf68bcfbb88e7d1ae4023e1d459d0c5fc`

逐帧解码、动作序列索引及 ZIP 完整性检查通过。模拟 200 毫秒图集解码延迟，离线测试左右走、跑、飞、短程飞行、中途停止和单次动作回待机，共 9 个场景通过。 [校验数据](VALIDATION.json)

原角色与动画来自白龙桌宠项目。素材来源和署名随包保存在 `credits/`。 [GitHub Release](https://github.com/ArtemisCode-arch/ChatGPT_DragonGirl_for_Coopanion/releases/tag/v1.0.5)
