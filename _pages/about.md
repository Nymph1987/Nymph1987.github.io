---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- 语言切换按钮 -->
<div style="text-align: right; margin-bottom: 20px;">
  <img src="/images/icon_切换中英文.png" alt="切换语言" style="width: 40px; height: 40px; cursor: pointer;" onclick="toggleLanguage()" id="langBtn">
  <span id="langLabel" style="font-size: 14px; margin-left: 8px; color: #666;">English</span>
</div>

<!-- 中文内容 -->
<div id="zh-content" style="display: none;" markdown="1">

我是广州大学计算机科学与网络工程学院计算机科学与技术专业**2022级本科生**，专业排名 **1/130**，加权平均分 **93.08/100**，绩点 **3.89/4**。

我的研究兴趣集中于**多模态情感识别**，包括语音、人脸、生理信号融合，以及图神经网络、自监督学习、多模态大语言模型等方向。目前有一篇论文已被 *Multimedia Systems* 录用（第一作者，**待正式见刊**），另有一篇相关工作在投（第二作者）；主持省级大创项目一项，参与国家级大创项目一项；拥有授权软著一项和公开发明专利一项。

我曾参与 ICRCV-Hongkong 分会场会议，并跟随导师彭凌西参与编写《人工智能通识》（ISBN: 978-7-115-67650-4）和《AI大模型开发实战》（ISBN: 978-7-111-79703-6）两本教材，主要负责内容撰写、案例设计与代码实现。

## 教育背景与能力

- **英语水平**：CET-4 524，CET-6 513
- **核心课程**：机器学习与数据挖掘（98）、人工智能原理（95）、离散数学（96）、高等数学（98）、概率论与数理统计（99）
- **技术能力**：熟练使用 Python，能够基于 PyTorch、TensorFlow 开展深度学习开发；熟悉 OpenCV、Transformers、Scikit-learn、Pandas 等工具；具备 Linux 环境配置、服务器部署、实验设计、算法落地和论文撰写能力。

## 代表性研究成果

- **GraphDREAM** (*Multimedia Systems*, 第一作者，已录用待见刊)：提出“净化-拓扑-校准”渐进学习框架，在 IEMOCAP、MELD、CH-SIMSv2 和 MOSEI 四个数据集上取得了有竞争力的性能。
- **CRM-Net** (在投，第二作者)：借鉴认知精细化感知机理，在 CMU-MOSI 和 CMU-MOSEI 上取得显著性能提升。
- **MoodLens** (软件著作权)：基于多模态情感识别技术的网页系统，融合人脸、语音、文本实时分析情感状态并提供 emoji 反馈。

## GraphDREAM 方法示意图

下面直接展示论文中的方法示意图，用于介绍 GraphDREAM 的整体框架。论文目前尚未正式线上出版，因此这里仅展示方法图和说明，不公开全文 PDF。

<img src="/images/model.png" alt="GraphDREAM 方法示意图" style="width: 100%; max-width: 900px;">

GraphDREAM 主要围绕三个关键环节展开：

- **净化（Purification）**：削弱低质量模态或噪声样本对表征学习的干扰。
- **拓扑（Topology）**：显式建模多模态之间的结构关系，增强跨模态交互能力。
- **校准（Calibration）**：优化分类边界与输出分布，提高预测稳定性和泛化能力。

在实验结果上，GraphDREAM 的多项指标刷新了对比基线：例如 IEMOCAP 六分类加权 F1 提升至 **72.52%**，CH-SIMSv2 五分类准确率达到 **57.74%**，MOSEI 二分类准确率达到 **86.43%**。

## GraphDREAM 案例展示

下面直接展示论文中的部分案例图，用于说明模型在具体样本上的表现与分析思路。

<img src="/images/generated/graphdream-case.png" alt="GraphDREAM 案例展示" style="width: 100%; max-width: 900px;">

这些案例主要用于展示模型在多模态输入下的识别效果、跨模态关系理解能力，以及在复杂情绪样本上的表现特征。

## 项目经历

### 省级大创

**《协同感知与语义锚定：基于跨模态注意力机制的多模态情感计算研究》**（负责人）

针对真实场景中的模态缺失与噪声干扰问题，提出基于跨模态注意力的鲁棒情感识别方法。我主导设计局部-全局图神经网络架构与主导模态校正模块，负责模型训练调优与算法探索，提升了不完整数据场景下的识别准确率与鲁棒性。

### 国家级大创

**《骨康智链——针对骨科术后康复的多模态融合个性化方案生成》**（核心团队成员）

面向骨科术后康复方案个性化制定问题，设计多模态融合生成模型。我负责核心算法研发，参与特征划分、模态编码器和多任务解码器设计，用于解决模态缺失与康复预测问题。

## 软著与专利

- **《MoodLens 多模态情感识别分析网页系统结构说明 v1.0》**：第一作者授权软著，检索号 **2026SR0527316**
- **《一种基于自监督微调的工业缺陷检测方法》**：发明公布 **CN120526218A**

## 竞赛与荣誉

- 2025 亚太地区大学生数学建模竞赛 (APMCM) — **国家级一等奖**
- 2025 微维杯大学生数学建模挑战赛 — **国家级一等奖**
- 2025 全球人工智能算法精英大赛 — **省级二等奖 / 国家优秀奖**
- 2024 全国大学生英语作文大赛 — **省级一等奖**
- 校一等奖学金、国家励志奖学金、校优秀学生、院优秀学生干部

## 资料与证明

- [个人简历 PDF](/files/%E5%B9%BF%E5%B7%9E%E5%A4%A7%E5%AD%A6%E5%90%B4%E8%B6%8A_%E4%B8%AA%E4%BA%BA%E7%AE%80%E5%8E%86.pdf)
- [成绩单及排名](/files/%E6%88%90%E7%BB%A9%E5%8D%95%E5%8F%8A%E6%8E%92%E5%90%8D.pdf)

## 比赛与能力证明展示

### APMCM 证书

<img src="/images/generated/award-apmcm.png" alt="APMCM 证书" style="width: 100%; max-width: 900px;">

### 微维杯证书

<img src="/images/generated/award-shuwei.png" alt="微维杯证书" style="width: 100%; max-width: 900px;">

### 英语能力证明

<img src="/images/generated/award-english.png" alt="英语能力证明" style="width: 100%; max-width: 900px;">

### 软件著作权证明

<img src="/files/%E8%BD%AF%E8%91%97-%E8%AE%A1%E7%A7%91231%EF%BC%88%E5%88%9B%EF%BC%89%E5%90%B4%E8%B6%8A_01.png" alt="软件著作权证明" style="width: 100%; max-width: 900px;">

## 补充展示

### 学术活动

<img src="/images/学术会议.jpg" alt="学术会议" style="width: 100%; max-width: 720px;">

参与 ICRCV-Hongkong 分会场等学术交流活动，持续关注多模态智能、情感计算与相关前沿研究。

### 教材编写

<img src="/images/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%80%9A%E8%AF%86_ISBN%20978-7-115-67650-4.png" alt="人工智能通识" style="width: 100%; max-width: 720px;">

参与《人工智能通识》与《AI大模型开发实战》的内容撰写、案例设计与代码实现。

欢迎对多模态 AI、情感计算、智能交互感兴趣的同学和朋友交流合作！

---

GitHub：Nymph1987  
打赏：如有需要可私下联系  
© 2026 吴越，技术支持：Jekyll & AcademicPages, a fork of Minimal Mistakes.  
Site last updated 2026-08-02， [Sitemap](/sitemap/)

</div>

<!-- 英文内容 -->
<div id="en-content" style="display: block;" markdown="1">

I am an undergraduate student majoring in Computer Science and Technology at Guangzhou University, with a major ranking of **1/130**, a weighted GPA of **93.08/100**, and a GPA of **3.89/4**.

My research interests focus on **multimodal emotion recognition**, including the fusion of speech, facial expressions, and physiological signals, as well as graph neural networks, self-supervised learning, and multimodal large language models. One of my papers has been accepted by *Multimedia Systems* as first author and is **awaiting formal publication**. I also have another related work under review as second author. In addition, I have led one provincial-level innovation project, participated in one national-level innovation project, and obtained one software copyright and one published invention patent.

I have attended the ICRCV-Hongkong session and contributed to the writing, case design, and code implementation of two AI textbooks under the supervision of Prof. Peng Lingxi: *Introduction to Artificial Intelligence* and *Hands-on Development of AI Large Models*.

## Education and Skills

- **English proficiency**: CET-4 524, CET-6 513
- **Core courses**: Machine Learning and Data Mining, Principles of Artificial Intelligence, Discrete Mathematics, Advanced Mathematics, Probability and Statistics
- **Technical skills**: Proficient in Python and deep learning development with PyTorch and TensorFlow; familiar with OpenCV, Transformers, Scikit-learn, and Pandas; capable of Linux deployment, experiment design, algorithm implementation, and academic writing.

## Selected Research Highlights

- **GraphDREAM** (*Multimedia Systems*, first author, accepted and awaiting publication): a progressive framework featuring purification, topology modeling, and calibration for multimodal emotion recognition.
- **CRM-Net** (under review, second author): a cognition-inspired method for improving performance on CMU-MOSI and CMU-MOSEI.
- **MoodLens** (software copyright): a web-based multimodal emotion recognition system integrating face, voice, and text analysis.

## GraphDREAM Framework Illustration

The following figure is directly embedded to introduce the overall framework of GraphDREAM. Since the paper has not yet been formally published online, I only present the method illustration and explanation here instead of the full paper PDF.

<img src="/images/model.png" alt="GraphDREAM Framework Illustration" style="width: 100%; max-width: 900px;">

GraphDREAM mainly includes three key stages:

- **Purification**: reducing the interference of noisy modalities or low-quality inputs.
- **Topology**: explicitly modeling structural relations across modalities.
- **Calibration**: improving prediction stability and generalization by refining output distributions.

In experiments, GraphDREAM achieved strong results across multiple benchmarks. For example, the weighted F1 on IEMOCAP 6-class reached **72.52%**, the 5-class accuracy on CH-SIMSv2 reached **57.74%**, and the binary accuracy on MOSEI reached **86.43%**.

## GraphDREAM Case Visualization

The following embedded figure presents part of the case analysis from the paper, showing how the model behaves on specific multimodal samples.

<img src="/images/generated/graphdream-case.png" alt="GraphDREAM Case Visualization" style="width: 100%; max-width: 900px;">

These examples are used to illustrate the model's recognition behavior, cross-modal understanding, and performance on complex emotional samples.

## Project Experience

### Provincial Innovation Project

**Collaborative Perception and Semantic Anchoring: Multimodal Emotion Computing Based on Cross-modal Attention** (Principal Investigator)

This project targets missing modalities and noisy inputs in real-world settings. I led the design of a local-global graph neural architecture and a dominant-modality correction module, and was responsible for training, tuning, and algorithm exploration.

### National Innovation Project

**BoneRehab Intelligence Chain: Personalized Multimodal Plan Generation for Orthopedic Postoperative Rehabilitation** (Core Team Member)

This project focuses on personalized rehabilitation planning. I contributed to the core algorithm design, including feature partitioning, modality encoders, and a multitask decoder for multimodal generation and prediction.

## Software Copyright and Patent

- **MoodLens Multimodal Emotion Recognition Web System Structure Specification v1.0**: authorized software copyright, registration no. **2026SR0527316**
- **An Industrial Defect Detection Method Based on Self-supervised Fine-tuning**: invention publication **CN120526218A**

## Awards & Honors

- 2025 Asia and Pacific Mathematical Contest in Modeling (APMCM) — **National First Prize**
- 2025 Weiwei Cup Mathematical Contest in Modeling — **National First Prize**
- 2025 Global AI Algorithm Elite Competition — **Provincial Second Prize / National Excellence Award**
- 2024 National College English Writing Contest — **Provincial First Prize**
- University First-Class Scholarship, National Encouragement Scholarship, Outstanding Student, Outstanding Student Leader

## Materials

- [CV PDF](/files/%E5%B9%BF%E5%B7%9E%E5%A4%A7%E5%AD%A6%E5%90%B4%E8%B6%8A_%E4%B8%AA%E4%BA%BA%E7%AE%80%E5%8E%86.pdf)
- [Transcript and Ranking](/files/%E6%88%90%E7%BB%A9%E5%8D%95%E5%8F%8A%E6%8E%92%E5%90%8D.pdf)

## Award and Certificate Display

### APMCM Certificate

<img src="/images/generated/award-apmcm.png" alt="APMCM Certificate" style="width: 100%; max-width: 900px;">

### Mathematical Modeling Certificate

<img src="/images/generated/award-shuwei.png" alt="Mathematical Modeling Certificate" style="width: 100%; max-width: 900px;">

### English Ability Certificate

<img src="/images/generated/award-english.png" alt="English Ability Certificate" style="width: 100%; max-width: 900px;">

### Software Copyright

<img src="/files/%E8%BD%AF%E8%91%97-%E8%AE%A1%E7%A7%91231%EF%BC%88%E5%88%9B%EF%BC%89%E5%90%B4%E8%B6%8A_01.png" alt="Software Copyright" style="width: 100%; max-width: 900px;">

## Additional Presentation

### Academic Activity

<img src="/images/学术会议.jpg" alt="Academic Activity" style="width: 100%; max-width: 720px;">

### Textbook Participation

<img src="/images/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%80%9A%E8%AF%86_ISBN%20978-7-115-67650-4.png" alt="AI Textbook" style="width: 100%; max-width: 720px;">

I am always open to communication and collaboration on multimodal AI, affective computing, and intelligent interaction.

---

GitHub: Nymph1987  
Support: available on request  
© 2026 Yue Wu, Powered by Jekyll & AcademicPages, a fork of Minimal Mistakes.  
Site last updated 2026-08-02, [Sitemap](/sitemap/)

</div>

<script>
function setSidebarLanguage(lang) {
  var mappings = [
    ['author-name-zh', 'author-name-en'],
    ['author-bio-zh', 'author-bio-en'],
    ['author-location-zh', 'author-location-en'],
    ['author-employer-zh', 'author-employer-en']
  ];

  mappings.forEach(function(pair) {
    var zh = document.getElementById(pair[0]);
    var en = document.getElementById(pair[1]);
    if (!zh || !en) return;

    if (lang === 'zh') {
      zh.style.display = 'inline';
      en.style.display = 'none';
    } else {
      zh.style.display = 'none';
      en.style.display = 'inline';
    }
  });

  var contactBtn = document.getElementById('author-contact-toggle');
  if (contactBtn) {
    contactBtn.textContent = lang === 'zh' ? '联系方式' : 'Contact';
  }
}

function toggleLanguage() {
  var zh = document.getElementById('zh-content');
  var en = document.getElementById('en-content');
  var label = document.getElementById('langLabel');

  if (zh.style.display === 'none') {
    zh.style.display = 'block';
    en.style.display = 'none';
    label.textContent = '中文';
    localStorage.setItem('preferredLang', 'zh');
    setSidebarLanguage('zh');
  } else {
    zh.style.display = 'none';
    en.style.display = 'block';
    label.textContent = 'English';
    localStorage.setItem('preferredLang', 'en');
    setSidebarLanguage('en');
  }
}

document.addEventListener('DOMContentLoaded', function() {
  var savedLang = localStorage.getItem('preferredLang');
  if (savedLang === 'zh') {
    document.getElementById('zh-content').style.display = 'block';
    document.getElementById('en-content').style.display = 'none';
    document.getElementById('langLabel').textContent = '中文';
    setSidebarLanguage('zh');
  } else {
    document.getElementById('zh-content').style.display = 'none';
    document.getElementById('en-content').style.display = 'block';
    document.getElementById('langLabel').textContent = 'English';
    setSidebarLanguage('en');
  }
});
</script>
