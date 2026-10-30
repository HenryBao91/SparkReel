# 🎨 SparkReel 星火短剧场 - AI 漫剧创作

<div align="center">

**免费 AI 短剧视频生成：MiniMax-H3-Max 视频生成模型**

[![MiniMax Version](https://img.shields.io/badge/MiniMax-H3-4FC08D?style=flat&)]()
[![SCNet](https://img.shields.io/badge/SCNet-646CFF?style=flat&logo=SCNet)]()
[![Docker](https://img.shields.io/badge/Docker-SparkReel-2490ED?style=flat&logo=docker)](https://hub.docker.com/r/henrybrain91/sparkreel)
[![License](https://img.shields.io/badge/License-%20MIT-lightgreen.svg)]()

[功能特性](#-功能特性) • [快速开始](#-快速开始) • [图文教程](#-图文教程) 


<p>
  <a href="https://www.scnet.cn/ui/aihub/agent/openaimodels/Sparkreel">
    <img src="images/logo.png" width="320" alt="访问 SCNet 官网免费体验 / Visit the official website" />
  </a>
</p>

</div>


---

## 📖 项目简介


星火短剧场是一款MiniMax-H3加持面向内容创作者的 AI 短剧生产平台，帮助用户将小说、故事梗概、剧本草稿或创意灵感，快速转化为角色、场景、分镜和视频成片。平台覆盖从剧本整理到视频导出的完整创作流程，让不会复杂剪辑和专业制作的用户，也能轻松完成短剧内容生产。





### 🎯 核心价值

- **🎨 工作流方式**：四种节点 + 类型化连线规则，所见即所得的创作流水线
- **🧩 免费试用**：MiniMax-H3 最强国产视频生成大模型，无中间格式损耗


---

## ✨ 功能特性

### 🎨 功能强大

- ✅ 文本 / 图像 / 视频 / 分组四种节点，拖拽连线构建创作流水线
- ✅ 上游产出自动注入下游：文生图 → 图生视频 → 参考生视频
- ✅ AI 剧本改写，让你的短剧更有吸引力


### 🌍 四语界面

简体中文 / English ，界面内一键切换。



### 角色与场景制作

星火短剧场支持生成<span style="color:#E74C3C">**角色形象**</span>、<span style="color:#E67E22">**场景参考图**</span>和<span style="color:#F1C40F">**道具图片**</span>。创作者可以根据剧情需要，调整<span style="color:#2ECC71">**人物外貌**</span>、<span style="color:#3498DB">**服装**</span>、<span style="color:#9B59B6">**气质**</span>、<span style="color:#1ABC9C">**环境氛围**</span>和<span style="color:#E74C3C">**画面风格**</span>，逐步形成统一的视觉设定。

参考图能够应用到后续分镜和视频生成中，帮助保持主要角色在不同镜头中的形象一致，让整部短剧更加连贯。
![img_v3_0216s_6d827841-5c46-4592-afba-c97aa0b4145g.jpg](https://mallcdn.accloud.cn/openaimodels/ac02dda38d264c1aedfe72b15b132427.jpg)  



---

### 影视风格预设

星火短剧场支持多种影视风格预设，包括<span style="color:#E67E22">**真实电影感**</span>、<span style="color:#F1C40F">**3D**</span>、<span style="color:#2ECC71">**动漫**</span>、<span style="color:#3498DB">**国风**</span>、<span style="color:#9B59B6">**漫画**</span>等多种视觉方向。

可以根据故事类型选择合适的风格，用于<span style="color:#1ABC9C">**都市情感**</span>、<span style="color:#E74C3C">**古装剧情**</span>、<span style="color:#E67E22">**悬疑推理**</span>、<span style="color:#F1C40F">**校园故事**</span>、<span style="color:#2ECC71">**动作武打**</span>、<span style="color:#3498DB">**品牌宣传**</span>和<span style="color:#9B59B6">**短视频内容创作**</span>等不同场景。
![img_v3_0216s_a4c6a5c9-a848-4dc4-a5d0-62233705bc4g.jpg](https://mallcdn.accloud.cn/openaimodels/ab73fdb98f4008e78afd7d322892eb95.jpg)  


---

### 分镜拆分

完成剧本和素材准备后，平台可以自动进行<span style="color:#E74C3C">**分镜拆分**</span>，将一段完整剧情拆解为多个镜头，并生成对应的<span style="color:#E67E22">**视频提示词**</span>。

可以查看和修改每个镜头的<span style="color:#F1C40F">**画面描述**</span>、<span style="color:#2ECC71">**人物动作**</span>、<span style="color:#3498DB">**镜头景别**</span>、<span style="color:#9B59B6">**镜头运动**</span>、<span style="color:#1ABC9C">**环境氛围**</span>和<span style="color:#E74C3C">**对白内容**</span>。通过清晰的分镜组织，创作者能够更好地控制故事节奏和画面表达。

![img_v3_0216s_77cd1a15-0965-4078-add1-6b50679b267g.jpg](https://mallcdn.accloud.cn/openaimodels/ee4c30bb8a490d592b48e821ce0a757e.jpg)  


---

### 视频生成

视频生成支持<span style="color:#E67E22">**单个镜头制作**</span>，也支持<span style="color:#F1C40F">**批量提交多个镜头任务**</span>。可以先生成**少量镜头**进行效果确认，再继续完成整集内容。

生成后可以逐个预览镜头，检查<span style="color:#2ECC71">**人物一致性**</span>、<span style="color:#3498DB">**动作连贯性**</span>、<span style="color:#9B59B6">**画面质量**</span>和<span style="color:#1ABC9C">**剧情表达**</span>，对不满意的镜头进行修改和重新生成。

当多个镜头完成后，用户可以按照剧情顺序选择需要使用的视频片段，<span style="color:#E74C3C">**一键拼接成完整剧集**</span>，并在线预览和下载成片。

整个过程不需要频繁切换多个软件，<span style="color:#E67E22">**剧本**</span>、<span style="color:#F1C40F">**角色**</span>、<span style="color:#2ECC71">**场景**</span>、<span style="color:#3498DB">**分镜**</span>和<span style="color:#9B59B6">**视频**</span>都可以在同一个工作台中管理。




---

## 🚀 快速开始

### 使用流程

1. <span style="color:#E74C3C">**创建项目**</span>，填写剧名并选择横屏或竖屏比例和整体风格。
![image.png](https://mallcdn.accloud.cn/openaimodels/8dc4b79be8bd18aa4a303633645cce7b.png)  


2. 粘贴小说、故事梗概或原始剧本，完成<span style="color:#E67E22">**剧本改写**</span>和<span style="color:#F1C40F">**内容整理**</span>。
![image.png](https://mallcdn.accloud.cn/openaimodels/4d2e6dfe46b6cdba3b56b559c78f34f7.png)  


3. 提取<span style="color:#2ECC71">**角色**</span>、<span style="color:#3498DB">**场景**</span>和<span style="color:#9B59B6">**道具**</span>，生成或上传参考素材。
![image.png](https://mallcdn.accloud.cn/openaimodels/7d677261656b65f7d9f78b95c8d2ed55.png)  


4. <span style="color:#1ABC9C">**拆分分镜**</span>，检查镜头内容并完善视频提示词。


5. <span style="color:#E74C3C">**生成视频**</span>，预览镜头并重新制作不满意的片段。
![image.png](https://mallcdn.accloud.cn/openaimodels/45ff985150f1a0d52aceea3aab6e779a.png)  


6. 选择合格镜头，<span style="color:#E67E22">**拼接导出完整短剧**</span>。
![image.png](https://mallcdn.accloud.cn/openaimodels/41dd6b0df18a265c47a3579c66e8fdeb.png)  


---

## 适用人群

星火短剧场适合<span style="color:#F1C40F">**短剧创作者**</span>、<span style="color:#2ECC71">**小说作者**</span>、<span style="color:#3498DB">**自媒体团队**</span>、<span style="color:#9B59B6">**品牌营销人员**</span>和<span style="color:#1ABC9C">**影视内容爱好者**</span>使用。无论是将一篇小说改编成短剧，还是把一个创意快速制作成可展示的视频作品，都可以从一个故事开始，逐步完成从文字到画面的转化。

**让 AI 陪你把灵感变成角色、场景和镜头，让每一个故事都拥有属于自己的影像表达。**

---


## 💬 微信群

扫码加入微信群交流：

<div align="center">
  <img src="images/wx-group.png" width="200" alt="微信群二维码" />
</div>

---

