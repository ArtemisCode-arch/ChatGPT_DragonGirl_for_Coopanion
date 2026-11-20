# v1.0.4 — 高清无损 WebP / 透明渲染 / 右行走修复

## 更新内容

- 由 720×720 高清原始动画重建素材：普通动作 512×512，羽毛和发光特效等重点动作 720×720。
- 使用无损 WebP 并处理透明通道/预乘 Alpha，改善羽毛、灯泡、魔法光球等半透明细节。
- 调整离屏绘制与完整帧提交逻辑，减少切换动画时的透明背景闪烁和空白帧。
- 重新挑选右行走稳定步态，避免尾巴在连续行走时异常消失。
- 走路与小跑采用原生 24 FPS 动作帧，调整脚步声同步和循环衔接。
- 保留原形象 ID、声音、角色造型、对话框以及互动动作。

## 安装

在 DeskHollow v0.1.05 / v0.1.05-R2 中，先切换到其他形象，选择「导入形象」并导入完整 ZIP；更新时选择替换旧版，之后切换回 ChatGPT 白银龙娘。

**不要把 GitHub 自动生成的 Source code ZIP 当成形象安装包。** 请下载 Release 附件中的 `ChatGPT_Silver_Dragon_DeskHollow_v1.0.4.zip`。

## 校验信息

- 安装包：`ChatGPT_Silver_Dragon_DeskHollow_v1.0.4.zip`
- 文件大小：1,177,439,253 bytes
- SHA256：`d5af857833a74d162682bff3e8d9444f70e94f551fb4c0f30db7a0ac891cc08e`

## 测试与边界

包内 `VALIDATION.json` 记载：41 组动作素材、4,931 帧、636 张无损图集；Linux/Chromium 环境下完成 DeskHollow Figure API 的动作及导入兼容测试。

尚未在用户的 Windows 原生桌面合成环境中进行实机测试。如果仍存在整块白色闪烁，应检查 Electron / 显卡驱动与透明窗口合成链路。

## 素材与授权

原角色和动画来自 [白龙桌宠](https://github.com/jingh12312-rgb/bailong-desktop-pet)，高清素材参考 [Wunsch2048 发布内容](https://github.com/Wunsch2048/codex-bailong-desktop-pet/releases/tag/v1.3.0)。完整包内的 `credits/` 保留原始声明。发布前请确认原项目素材的公开分发授权。
