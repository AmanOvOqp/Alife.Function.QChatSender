# Alife.Function.QChatSender (QQ单向发送)

专门为 Agent / 子代理 / 多角色协作场景设计的轻量级 QQ 单向推送插件。

## 核心特性
- **纯单向发送**：仅提供 QQ 私聊/群聊消息发送、文件/图片传输能力，完全剥离接收链路。
- **杜绝抢话与冲突**：在多 Agent 或 SubAgent 架构下，防止从属 Agent 监听抢占主活动的消息回路。
- **OneBot v11 驱动**：基于标准 OneBot v11 WebSocket 协议通信。

## 模块信息
- **模块名称**：QQ单向发送
- **作者**：阿瞒
- **分类**：Alife 官方/交互方式
