# 简介

桔梦(QBot_Jiemeng)是一个以词条匹配为核心的简单的 OneBot 机器人框架。

## 平台

### 验证可用的平台

- Linux-x86_64
- Linux-aarch64 (Termux Proot-distro 内可构建、可使用)

### 不支持的平台

- Windows 等*非*类 UNIX 环境: 完全放弃兼容。

## 已实现的特色应用场景举例

1. 定时消息
2. 远程指令执行
3. 可简易配置的第三方api调用
4. 用于 [Dice!](https://github.com/Dice-Developer-Team/Dice) 的牌堆调用兼容
5. 群聊检测到满足条件的信息向 bot 主或特定群聊上报消息。

## 特色

- 词条匹配触发：机制明确、简单
- Lua 扩展：可以使用 Lua 对功能进行极深的扩展。

