---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- 中文内容 -->
<div id="zh-content" style="display: none;" markdown="1">

我目前就读于广州大学计算机科学与网络工程学院，专业为计算机科学与技术。作为 **2023级本科生**，目前专业排名 **1/130**，平均分 **93.16/100**，加权绩点 **93.08/100**，绩点 **3.89/4**。

我的主要研究方向是**多模态情感识别**，关注语音、人脸、生理信号等多源信息的融合建模，也持续关注图神经网络、自监督学习和多模态大模型等相关方法。当前已有一篇论文被 *Multimedia Systems* 录用（第一作者，**待正式见刊**），另有一篇相关工作在投（第二作者）；同时主持省级大创项目一项，参与国家级大创项目一项，并拥有授权软著一项和发明专利公布成果一项。

除科研之外，我也积极参与学术交流与教材建设工作，曾参加 ICRCV-Hongkong 分会场会议，并参与人工智能领域相关教材内容的编写。

## 教育背景与能力

- **英语水平**：CET-4 524，CET-6 513
- **核心课程**：机器学习与数据挖掘（98）、人工智能原理（95）、离散数学（96）、高等数学（98）、概率论与数理统计（99）
- **技术能力**：熟练使用 Python，能够基于 PyTorch、TensorFlow 开展深度学习开发；熟悉 OpenCV、Transformers、Scikit-learn、Pandas 等工具；具备 Linux 环境配置、服务器部署、实验设计、算法落地和论文撰写能力。

## 代表性研究成果

- **GraphDREAM** (*Multimedia Systems*, 第一作者，已录用待见刊)：提出“净化-拓扑-校准”渐进学习框架，在 IEMOCAP、MELD、CH-SIMSv2 和 MOSEI 四个数据集上取得了有竞争力的性能。
- **CRM-Net** (在投，第二作者)：借鉴认知精细化感知机理，在 CMU-MOSI 和 CMU-MOSEI 上取得显著性能提升。
- **MoodLens** (软件著作权)：基于多模态情感识别技术的网页系统，融合人脸、语音、文本实时分析情感状态并提供 emoji 反馈。

## 论文简介

GraphDREAM 面向对话与独白情感分类任务，主要处理多模态情感识别里常见的三个难点：不同模态之间的信息冲突、对话过程中说话人关系与时序依赖的建模，以及情绪预测在边界样本上的漂移问题。整套方法沿着“净化 - 拓扑 - 校准”的思路展开，先通过 DCR 模块拆分共享特征与私有特征，尽量滤掉噪声模态带来的干扰；再用 SEHG 时空异构图把说话人交互关系、上下文演化和模态联系一起建起来；最后借助 MCC 多任务一致性校准，让情绪表示和最终分类结果更加稳定。

从图里可以比较直观地看到这条主线：左侧是文本、语音、视觉等输入特征，中间经过解耦与图结构建模后完成跨模态信息融合，右侧再通过一致性校准得到情绪预测结果。这个结构也是我在论文中重点解决问题的核心思路。

<img src="/images/model.png" alt="GraphDREAM 方法示意图" style="width: 100%; max-width: 900px;">

在实验结果上，GraphDREAM 的多项指标刷新了对比基线：例如 IEMOCAP 六分类加权 F1 提升至 **72.52%**，CH-SIMSv2 五分类准确率达到 **57.74%**，MOSEI 二分类准确率达到 **86.43%**。

除了整体结构设计，论文里也对具体样本做了可视化分析。下面这组案例主要对应模型在复杂情绪样本上的判断过程，可以看到它在多模态信息不完全一致时，仍然能够利用上下文关系和模态互补信息去修正预测，这也是 GraphDREAM 相比部分基线方法更稳定的原因之一。

<img src="/images/generated/graphdream-case.png" alt="GraphDREAM 案例展示" style="width: 100%; max-width: 900px;">

## 科研项目经历

### 省级大创

**《协同感知与语义锚定：基于跨模态注意力机制的多模态情感计算研究》 负责人**

针对真实场景中的模态缺失与噪声干扰问题，提出基于跨模态注意力的鲁棒情感识别方法。我主导设计局部-全局图神经网络架构与主导模态校正模块，负责模型训练调优与算法探索，提升了不完整数据场景下的识别准确率与鲁棒性。

### 国家级大创

**《骨康智链——针对骨科术后康复的多模态融合个性化方案生成》 核心团队成员**

面向骨科术后康复方案个性化制定问题，设计多模态融合生成模型。我负责核心算法研发，参与特征划分、模态编码器和多任务解码器设计，用于解决模态缺失与康复预测问题。

## 专业实习

**基于大模型的知识库技术服务**

在这段专业实习中，我作为组长牵头校企合作项目，对接企业完成需求梳理与方案落地；依托 OCR 与 Qwen3-VL 接口实现多格式文档解析和结构化处理，搭建智能报价系统，完成设备智能匹配与报价单自动生成，并协助将智能模块集成至 LIMS 系统。

## 软著与专利

- **《MoodLens 多模态情感识别分析网页系统结构说明 v1.0》**：第一作者授权软著，检索号 **2026SR0527316**
- **《一种基于自监督微调的工业缺陷检测方法》**：发明公布 **CN120526218A**

## 竞赛与荣誉

- 2025 亚太地区大学生数学建模竞赛 (APMCM) — **国家级一等奖**
- 2025 微维杯大学生数学建模挑战赛 — **国家级一等奖**
- 2025 全球人工智能算法精英大赛 — **省级二等奖 / 国家优秀奖**
- 2024 全国大学生英语作文大赛 — **省级一等奖**
- 校一等奖学金、国家励志奖学金、校优秀学生、院优秀学生干部、院优秀团员

下面列出部分竞赛证书与能力证明，可左右滑动查看：

<div style="display: flex; gap: 16px; overflow-x: auto; padding: 8px 0 16px; scroll-snap-type: x mandatory;">
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/亚太杯.png" alt="APMCM 证书" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">APMCM 国家级一等奖证书</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/数维杯.png" alt="微维杯证书" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">微维杯国家级一等奖证书</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/英语作文大赛.jpg" alt="英语能力证明" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">英语能力与竞赛证明</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/AIC.png" alt="AIC 国家优秀奖证书" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">AIC 全国总决赛优秀奖证书</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/AIC2.png" alt="AIC 省级二等奖证书" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">AIC 省级二等奖证书</figcaption>
  </figure>
</div>

## 学术活动

<img src="/images/学术会议.jpg" alt="学术会议" style="width: 100%; max-width: 520px;">

参与 ICRCV-Hongkong 分会场等学术交流活动，持续关注多模态智能、情感计算与相关前沿研究。

## 教材编写

<img src="/images/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%80%9A%E8%AF%86_ISBN%20978-7-115-67650-4.png" alt="人工智能通识" style="width: 100%; max-width: 720px;">

<img src="/images/AI大模型开发实战_ISBN%20978-7-111-79703-6.png" alt="AI大模型开发实战" style="width: 100%; max-width: 720px; margin-top: 16px;">

课外跟随导师彭凌西参与人工智能领域教材建设工作，参与编写《人工智能通识》（ISBN：978-7-115-67650-4）项目 2，以及《AI大模型开发实战》（唐春明、彭凌西、黄永健等主编，ISBN：978-7-111-79703-6）第六章“多模态应用开发”。我主要负责相关内容撰写、案例设计、代码实现与技术资料整理工作。

欢迎对多模态 AI、情感计算、智能交互感兴趣的同学和朋友交流合作！

## 资料与证明

- [个人简历 PDF](/files/%E5%B9%BF%E5%B7%9E%E5%A4%A7%E5%AD%A6%E5%90%B4%E8%B6%8A_%E4%B8%AA%E4%BA%BA%E7%AE%80%E5%8E%86.pdf)
- [成绩单及排名](/files/%E6%88%90%E7%BB%A9%E5%8D%95%E5%8F%8A%E6%8E%92%E5%90%8D.pdf)

---

© 2026 吴越。本站基于 Jekyll 与 AcademicPages 构建。
最后更新：2026-08-02

</div>

<!-- 英文内容 -->
<div id="en-content" style="display: block;" markdown="1">

I am currently an undergraduate student in Computer Science and Technology at Guangzhou University. As a **2023-entry student**, I am ranked **1/130** in my major, with an average score of **93.16/100**, a weighted GPA score of **93.08/100**, and a GPA of **3.89/4**.

My research mainly focuses on **multimodal emotion recognition**, especially the fusion and modeling of speech, facial expressions, and physiological signals. I also continue to explore related methods such as graph neural networks, self-supervised learning, and multimodal large models. At present, one of my papers has been accepted by *Multimedia Systems* as first author and is **awaiting formal publication**, while another related work is under review with me as second author. I have also led one provincial-level innovation project, participated in one national-level innovation project, and obtained one authorized software copyright and one invention patent publication.

Beyond research, I actively take part in academic exchange and textbook development. I have attended the ICRCV-Hongkong session and participated in the writing of AI-related teaching materials.

## Education and Skills

- **English proficiency**: CET-4 524, CET-6 513
- **Core courses**: Machine Learning and Data Mining (98), Principles of Artificial Intelligence (95), Discrete Mathematics (96), Advanced Mathematics (98), Probability and Statistics (99)
- **Technical skills**: Proficient in Python and deep learning development with PyTorch and TensorFlow; familiar with OpenCV, Transformers, Scikit-learn, and Pandas; capable of Linux deployment, experiment design, algorithm implementation, and academic writing.

## Selected Research Highlights

- **GraphDREAM** (*Multimedia Systems*, first author, accepted and awaiting publication): a progressive framework featuring purification, topology modeling, and calibration for multimodal emotion recognition.
- **CRM-Net** (under review, second author): a cognition-inspired method for improving performance on CMU-MOSI and CMU-MOSEI.
- **MoodLens** (software copyright): a web-based multimodal emotion recognition system integrating face, voice, and text analysis.

## Paper Overview

GraphDREAM is designed for dialogue and monologue emotion classification. The work focuses on three recurring challenges in multimodal emotion recognition: conflicting signals across modalities, the difficulty of modeling speaker interaction and temporal dependency, and unstable predictions on hard emotional samples. The framework follows a progressive path of purification, topology modeling, and calibration. It first uses a decoupled representation module to separate shared and private information while suppressing noisy modalities, then builds a spatio-temporal heterogeneous graph to model speaker relations and contextual evolution, and finally applies multi-task consistency calibration to make emotion prediction more stable.

The figure below reflects this main idea clearly: multimodal inputs enter from the left, pass through decoupling and graph-based interaction modeling in the middle, and are further refined on the right before the final emotion output is produced. This is also the central line of the method design in the paper.

<img src="/images/model.png" alt="GraphDREAM Framework Illustration" style="width: 100%; max-width: 900px;">

In experiments, GraphDREAM achieved strong results across multiple benchmarks. For example, the weighted F1 on IEMOCAP 6-class reached **72.52%**, the 5-class accuracy on CH-SIMSv2 reached **57.74%**, and the binary accuracy on MOSEI reached **86.43%**.

The paper also includes case-level visualization on difficult samples. In these examples, the model can still make more reliable predictions when different modalities are not fully aligned, because it makes use of contextual dependency and complementary cues across modalities. That is one of the main reasons why GraphDREAM remains relatively stable compared with several baselines.

<img src="/images/generated/graphdream-case.png" alt="GraphDREAM Case Visualization" style="width: 100%; max-width: 900px;">

## Research Project Experience

### Provincial Innovation Project

**Collaborative Perception and Semantic Anchoring: Multimodal Emotion Computing Based on Cross-modal Attention - Principal Investigator**

This project targets missing modalities and noisy inputs in real-world settings. I led the design of a local-global graph neural architecture and a dominant-modality correction module, and was responsible for training, tuning, and algorithm exploration.

### National Innovation Project

**BoneRehab Intelligence Chain: Personalized Multimodal Plan Generation for Orthopedic Postoperative Rehabilitation - Core Team Member**

This project focuses on personalized rehabilitation planning. I contributed to the core algorithm design, including feature partitioning, modality encoders, and a multitask decoder for multimodal generation and prediction.

## Professional Internship

**Knowledge Base Technical Service Based on Large Models**

During this internship, I served as the team lead in a university-enterprise collaboration project. I coordinated requirement analysis and solution implementation with the company, used OCR and Qwen3-VL APIs to support multi-format document parsing and structured processing, built an intelligent quotation system for equipment matching and automatic quotation generation, and helped integrate the intelligent module into the LIMS system.

## Software Copyright and Patent

- **MoodLens Multimodal Emotion Recognition Web System Structure Specification v1.0**: authorized software copyright, registration no. **2026SR0527316**
- **An Industrial Defect Detection Method Based on Self-supervised Fine-tuning**: invention publication **CN120526218A**

## Awards & Honors

- 2025 Asia and Pacific Mathematical Contest in Modeling (APMCM) — **National First Prize**
- 2025 Weiwei Cup Mathematical Contest in Modeling — **National First Prize**
- 2025 Global AI Algorithm Elite Competition — **Provincial Second Prize / National Excellence Award**
- 2024 National College English Writing Contest — **Provincial First Prize**
- University First-Class Scholarship, National Encouragement Scholarship, Outstanding Student, Outstanding Student Leader, Outstanding League Member

Selected certificates and supporting documents are shown below. You can scroll horizontally to view them:

<div style="display: flex; gap: 16px; overflow-x: auto; padding: 8px 0 16px; scroll-snap-type: x mandatory;">
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/亚太杯.png" alt="APMCM Certificate" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">APMCM National First Prize Certificate</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/数维杯.png" alt="Mathematical Modeling Certificate" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">Weiwei Cup National First Prize Certificate</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/英语作文大赛.jpg" alt="English Ability Certificate" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">English Ability and Competition Certificate</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/AIC.png" alt="AIC National Final Certificate" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">AIC National Final Excellence Award</figcaption>
  </figure>
  <figure style="min-width: 320px; max-width: 420px; margin: 0; scroll-snap-align: start;">
    <div style="height: 260px; display: flex; align-items: center; justify-content: center; background: #fff;">
      <img src="/images/AIC2.png" alt="AIC Provincial Certificate" style="max-width: 100%; max-height: 260px; width: auto; height: auto; border-radius: 8px;">
    </div>
    <figcaption style="margin-top: 8px; font-size: 0.95em;">AIC Provincial Second Prize</figcaption>
  </figure>
</div>

## Academic Activity

<img src="/images/学术会议.jpg" alt="Academic Activity" style="width: 100%; max-width: 520px;">

## Textbook Participation

<img src="/images/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%80%9A%E8%AF%86_ISBN%20978-7-115-67650-4.png" alt="AI Textbook" style="width: 100%; max-width: 720px;">

<img src="/images/AI大模型开发实战_ISBN%20978-7-111-79703-6.png" alt="Hands-on Development of AI Large Models" style="width: 100%; max-width: 720px; margin-top: 16px;">

Outside the classroom, I joined Prof. Peng Lingxi in textbook development work in artificial intelligence. I participated in Project 2 of *Introduction to Artificial Intelligence* (ISBN: 978-7-115-67650-4) and Chapter 6, "Multimodal Application Development," of *Hands-on Development of AI Large Models* (chief editors: Tang Chunming, Peng Lingxi, Huang Yongjian, etc.; ISBN: 978-7-111-79703-6). My work mainly covered content writing, case design, code implementation, and technical material organization.

I am always open to communication and collaboration on multimodal AI, affective computing, and intelligent interaction.

## Materials

- [CV PDF](/files/%E5%B9%BF%E5%B7%9E%E5%A4%A7%E5%AD%A6%E5%90%B4%E8%B6%8A_%E4%B8%AA%E4%BA%BA%E7%AE%80%E5%8E%86.pdf)
- [Transcript and Ranking](/files/%E6%88%90%E7%BB%A9%E5%8D%95%E5%8F%8A%E6%8E%92%E5%90%8D.pdf)

---

© 2026 Yue Wu. Built with Jekyll and AcademicPages.
Last updated: 2026-08-02

</div>

<script>
function setSidebarLanguage(lang) {
  var mappings = [
    ['author-name-zh', 'author-name-en'],
    ['author-bio-zh', 'author-bio-en'],
    ['author-location-zh', 'author-location-en'],
    ['author-employer-zh', 'author-employer-en'],
    ['site-pv-display-zh-wrapper', 'site-pv-display-en-wrapper']
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

  function updateVisitorCount() {
    var rawCounter = document.getElementById('busuanzi_value_site_pv');
    if (!rawCounter) return;
    var rawValue = parseInt(rawCounter.textContent, 10);
    if (isNaN(rawValue)) return;

    var displayValue = rawValue + 100;
    var zhCounter = document.getElementById('site-pv-display-zh');
    var enCounter = document.getElementById('site-pv-display-en');

    if (zhCounter) zhCounter.textContent = displayValue;
    if (enCounter) enCounter.textContent = displayValue;
  }

  updateVisitorCount();
  setInterval(updateVisitorCount, 1000);
});
</script>
