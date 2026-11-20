# v1.0.4 — 高清无损 WebP / 透明渲染 / 右行走修复

## 更新内容

- 由 720×720 高清原始动画重建素材：普通动作 512×512，羽毛和发光特效等重点动作 720×720。
- 使用无损 WebP 并处理透明通道/预乘 Alpha，改善羽毛、灯泡、魔法光球等半透明细节。
- 调整离屏绘制与完整帧提交逻辑，减少切换动画时的透明背景闪烁和空白帧。
- 重新挑选右行走稳定步态，避免尾巴在连续行走时异常消失。
- 走路与小跑采用原生 24 FPS 动作帧，调整脚步声同步和循环衔接。
- 保留原形象 ID、声音、角色造型、对话框以及互动动作。

## 动作演示

v1.0.2 的动作演示，包含行走、拎起与落地，以及「龙族契约」。

https://github.com/user-attachments/assets/2821ab9f-1992-4145-b252-271aead0bc63

## 安装

1. 下载 [白龙形象包 v1.0.4（约 1.18 GB）](https://github.com/ArtemisCode-arch/ChatGPT_DragonGirl_for_Coopanion/releases/download/v1.0.4/ChatGPT_Silver_Dragon_Coopanion_v1.0.4.zip)。
2. 在 Coopanion 打开「设置 → 装扮 → 导入」，选择下载的 ZIP 并确认。
3. 在形象列表中选中「ChatGPT • 白银龙娘」。更新旧版时，在导入确认框中选择替换。

完整版适用 Coopanion v0.2.16 起的导入规则。超过 128 MiB 的包会在确认时显示体积提醒。

## 校验信息

- 安装包：`ChatGPT_Silver_Dragon_Coopanion_v1.0.4.zip`
- 文件大小：1,177,439,253 bytes
- SHA256：`d5af857833a74d162682bff3e8d9444f70e94f551fb4c0f30db7a0ac891cc08e`

## 验证范围

共 41 组动作、4,931 帧和 636 张无损图集。已在 Linux / Chromium 环境完成 Figure API 2 的动作及导入兼容检查。Coopanion 原版的 Windows 导入与动作播放尚未实测。

## 素材与授权

原角色和动画来自 [白龙桌宠](https://github.com/jingh12312-rgb/bailong-desktop-pet)，高清素材参考 [Wunsch2048 发布内容](https://github.com/Wunsch2048/codex-bailong-desktop-pet/releases/tag/v1.3.0)。完整包内的 `credits/` 保留原始声明。发布前请确认原项目素材的公开分发授权。
