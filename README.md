# Aemeath · Alife 插件

Aemeath 系列自研的 [Alife](https://github.com/BDFFZI/Alife) 插件源码与发布包。

## 安装

在 Alife 的插件市场里搜索插件名直接安装；也可以自行下载对应 Release 的 zip，解压到 `Storage/Plugins/<插件ID>/` 后重载插件环境。

## 插件列表

| 插件 | 说明 |
| --- | --- |
| `Aemeath.CharacterCard` | 人格卡片 |
| `Aemeath.EgoBrowser` | ego 浏览器 |
| `Aemeath.EmotionTTS.E3` | 情感语音 E3（本地·曲线） |
| `Aemeath.EmotionTTS.E5` | 情感语音 E5（本地·LLM 融合） |
| `Aemeath.FishAudioTTS` | FishAudio 云端语音 |
| `Aemeath.MultiASR` | 多通道云端语音识别 |
| `Aemeath.Relations` | 关系档案 |
| `Aemeath.Sandbox` | 文件沙箱 |
| `Aemeath.Scenes` | 场景人格 |
| `Aemeath.VideoForge` | 生视频 |

## 说明

插件均为 .NET / C# 源码形式，由 Alife 宿主热编译加载，不含可执行文件。
运行时产生的角色私有数据（唤醒词、API Key、对话记录）不会随包分发。
