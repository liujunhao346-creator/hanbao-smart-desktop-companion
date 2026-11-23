# 憨包智能桌面伙伴

「憨包」是一个 Codex 自定义宠物包。它戴着红围巾，做什么都一脸呆萌，嘴角挂着一条垂到围巾上的口水。待机、跑动、挥手、跳跃、任务失败、等待输入、工作和检查等 9 种状态共有 57 帧，另有 16 个视线方向。

![憨包的待机动画](preview/idle.gif)

[查看所有动作和视线方向](preview/hanbao-motion.gif)

## 安装

1. [下载仓库 ZIP](https://github.com/liujunhao346-creator/hanbao-smart-desktop-companion/archive/refs/heads/main.zip) 并解压。
2. 在 Codex 桌面应用中打开 **设置 → 宠物 → 打开文件夹**。
3. 将解压目录里的 `hanbao` 文件夹复制进去。文件夹内应直接包含 `pet.json` 和 `spritesheet.webp`。
4. 回到 **设置 → 宠物**，刷新后选择 **憨包**。可在这里唤醒宠物，也可在 Codex 对话中输入 `/pet`。

精灵图为 v2 格式，尺寸 1536×2288，网格为 8 列×11 行，每格 192×208 像素。请使用支持 v2 本地宠物的 Codex 桌面版本。

## 来源和许可

憨包的全身造型和动作参考了 [zhangd732/Pet_Doubao](https://github.com/zhangd732/Pet_Doubao/tree/562b866)，脸部造型参考了红围巾流口水表情图。这里发布的是为 Codex 重新生成和编排的宠物包。上游仓库的代码和参考原图均未随包分发。

本仓库原创配置与文档采用 [MIT 许可证](LICENSE)。精灵图和预览涉及的第三方角色形象、参考图和品牌标识不属于该许可范围。项目为非官方社区作品。
