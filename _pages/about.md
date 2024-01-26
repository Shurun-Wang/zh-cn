---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

合肥工业大学电气与自动化工程学院博士在读，顺天堂大学医学院联合培养博士研究生。 以第一作者（含导师一作）发表SCI期刊论文4篇，引用 
 <a href='https://scholar.google.com/citations?user=Pb73FP8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。

研究领域包括: 
- 生理信号分析
- 人-外骨骼交互
- 大脑功能连接分析

<span class='anchor' id='-jyjl'></span>

# 🎓 教育经历 
- *2019.09 - 2024.06*&ensp;博士，电气与自动化工程学院，合肥工业大学，合肥，中国。 <a href="https://www.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 
- *2023.04 - 2024.04*&ensp;博士，医学院, 顺天堂大学，东京，日本。 (联合培养) <a href="https://en.juntendo.ac.jp/"><img class="svg" src="/images/juntendo.png" width="16pt"></a> 
- *2016.09 - 2019.06*&ensp;硕士, 电气与自动化工程学院，合肥工业大学，合肥，中国。 <a href="https://www.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 
- *2012.09 - 2016.06*&ensp;学士，电气与自动化工程学院，合肥工业大学，合肥，中国。 <a href="https://www.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 

<span class='anchor' id='-lwzl'></span>

# 📝 论文专利 
<h3 align="center">外审中</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div> 

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. Estimating Lower Extremity Multi-Joint Kinematics with One IMU Sensor via Attention-based Temporal Convolutional Neural Network.

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. A Robust Denoising Diffusion Architecture for Completing Missing Regions of Multiple Physiological Signals. 

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. Optimizing Graph Neural Network Architectures for Schizophrenia Spectrum Disorder Prediction Using Evolutionary Algorithms.

- __Shurun Wang__, Hao Tang*, Zhaowu Ping, et al. Improved Data-Driven Model-Free Adaptive Control Method for an Upper Extremity Power-Assist Exoskeleton.

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. ECGDenoiser: A Magnitude-Aware Deep Learning Framework for Electrocardiogram Signal Enhancement.


<h3 align="center">2024</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

- __Shurun Wang__, Hao Tang*, Feng Chen, et al. Integrated Block-Wise Neural Network with Auto-Learning Search Framework for Finger Gesture Recognition using sEMG Signals. Artificial Intelligence in Medicine. (已录用)
  

<h3 align="center">2023</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/tnnls23.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9609089">
            <papertitle> A Novel Approach to Detecting Muscle Fatigue Based on sEMG by Using Neural Architecture Search Framework </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Bin Wang, et al.
        <br>
        <em> IEEE Transactions on Neural Networks ＆ Learning Systems</em>, 2023 <a href="https://github.com/Shurun-Wang/NAS">[code]</a>
        <p></p>
        <p>提出了一种基于强化学习的分层探索机制，用于自动生成高性能的CNN模型，这些模型可用于检测肌肉疲劳。</p>
    </div>
</div>


<h3 align="center">2022</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/jbhl22.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9857571">
            <papertitle> Continuous estimation of human joint angles from sEMG using a multi-feature temporal convolutional attention-based network </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Lifu Gao, et al.
        <br>
        <em> IEEE Journal of Biomedical and Health Informatics </em>, 2022 <a href="https://github.com/Shurun-Wang/MFTCAN-KNR">[code]</a>
        <p></p>
        <p> 提出了一种多特征时序卷积注意力网络（MFTCAN），用于估计关节角度。 <br>
          开发了一种联合训练机制，将MFTCAN与KNR和SVR等传统统计算法相结合。
</p>
    </div>
</div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/tim22.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9762275">
            <papertitle> A Double Threshold Adaptive Method for Robust Detection of Muscle Activation Intervals from Surface Electromyographic Signals </papertitle>
        </a>
        <br>
        Hao Tang*, <strong>Shurun Wang</strong>, Qi Tan, et al.
        <br>
        <em> IEEE Transactions on Instrumentation and Measurement </em>, 2022 <a href="https://github.com/Shurun-Wang/sEMGDetection">[code]</a>
        <p></p>
        <p> 开发了一种基于样本熵的鲁棒算法，以克服运动伪迹和不规则强直性尖峰的影响。  <br> 设计了一个具有互锁结构的双阈值自适应检测框架，用于检测肌肉激活间隔的开始和结束。
</p>
    </div>
</div>

<h3 align="center">2021</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/bspc21.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/pii/S1746809421001075">
            <papertitle> Analysis of Fatigue in the Biceps Brachii by Using Rapid Refined Composite Multiscale Sample Entropy </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Bin Wang, et al.
        <br>
        <em> Biomedical Signal Processing and Control</em>, 2021 <a href="https://github.com/Shurun-Wang/R2CMSE">[code]</a>
        <p></p>
        <p> 提出了快速精细化的复合多尺度样本熵（R2CMSE）来提取sEMG信号特征，这种算法可以描述肌肉疲劳的变化过程。 </p>
    </div>
</div>

<h3 align="center">专利</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

- 唐昊，__王舒润__，王彬。一种基于网络架构搜索的人体运动意图识别方法。（审中-实审）

<span class='anchor' id='-ryjl'></span>

# 🏅 荣誉奖项
- *2023.04*&ensp;受到国家留学基金委员会的留学资助
- *2022.10*&ensp;博士研究生国家奖学金

<span class='anchor' id='-zyxx'></span>

# 💬 重要消息
- *现在* &ensp;&ensp;&ensp;&ensp;![Visitors](https://api.visitorbadge.io/api/visitors?path=https://shurun-wang.github.io/zh-cn/&label=visitors&countColor=%232ccce4&style=plastic)
- *2023.08*&ensp;参加理化学研究所的Brain/MINDS Data Portal Hackathon
- *2022.09*&ensp;刘琪女士与我步入婚姻殿堂



  
