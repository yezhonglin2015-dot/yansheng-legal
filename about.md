---
layout: default
title: 关于颜圣 — AI面部美学分析方法论 | YanSheng
description: 颜圣如何用AI分析面部比例？东亚美学标准是什么？了解颜圣的技术方法、评分逻辑和设计理念。
---

# 关于颜圣 YanSheng

## 为什么要做这款App

大多数颜值测试App给你一个数字，然后什么都没了。你不知道这个数字从哪里来，不知道你哪里好哪里差，更不知道接下来该怎么做。

颜圣想解决的问题是：**给亚洲人一个基于正确标准的、有深度的、真正可操作的面部分析。**

不是西方标准。不是模糊的安慰。不是算法黑箱。是一份你能看懂、能用上的报告。

## Why we built this app

Most face rating apps give you a number and nothing else. You don't know where the number comes from, which features are helping or hurting, or what to do next.

YanSheng was built to solve a specific problem: giving Asian users a deep, accurate, actionable facial analysis calibrated to the right standards — East Asian aesthetic benchmarks, not Western ones, not a generic global average, and not a vague compliment engine.

---

## 技术方法 / Technology

### AI视觉分析
颜圣的核心是Claude claude-sonnet-4-6视觉模型（Anthropic），这是目前在多模态图像理解任务上表现最强的大语言模型之一。扫描时，App通过iPhone摄像头捕捉面部图像帧，提取正面照传送至云端，由AI进行多维度测量和分析。

YanSheng's core is the Claude claude-sonnet-4-6 vision model from Anthropic, one of the strongest multimodal image understanding models available. During a scan, the app captures facial image frames through the iPhone camera, extracts the front-facing image, and transmits it to the cloud for multi-dimensional AI measurement and analysis.

### 23项测量维度
AI分析覆盖23个具体面部维度，不是印象式的整体评价，而是精确到每一项比例数值的结构化测量。这些维度包括三庭五眼比例、眼形分类、鼻宽比、唇比、颧骨位置、下颌线清晰度、面部对称性、肤色色调等。

The AI analysis covers 23 specific facial dimensions — not impressionistic overall assessments, but structured measurements precise to individual proportion ratios. These include three-zone vertical balance, five-section horizontal balance, eye shape classification, nose width ratio, lip ratio, cheekbone position, jawline definition, facial symmetry, skin undertone, and more.

### 东亚美学校准
评分标准不是通用的"美"的标准，而是明确基于东亚美学框架校准的：三庭五眼的比例理想值、东亚女性面部分析中苹果肌饱满度的权重、东亚男性面部分析中下颌线清晰度的权重、东亚色彩美学中对暖色调肤色和冷色调肤色的不同搭配逻辑。

The scoring standard is not a generic "universal beauty" metric — it is explicitly calibrated to East Asian aesthetic frameworks: the ideal values for three-zone and five-section proportions, the weight of cheek fullness in East Asian female facial analysis, the weight of jawline definition in East Asian male facial analysis, and the different color pairing logic for warm vs. cool undertones in East Asian color aesthetics.

### 男女差异化分析
男性和女性的评分维度权重完全不同。女性分析中，苹果肌饱满度、眼形柔和度、五官整体和谐度权重更高；男性分析中，下颌线清晰度、颧骨突出度、骨相整体锐利感权重更高。这不是偏见，而是对现实中东亚审美文化中男女颜值评价标准差异的准确反映。

Male and female scoring weights are entirely different. In female analysis, cheek fullness, eye shape softness, and overall feature harmony are weighted more heavily. In male analysis, jawline definition, cheekbone prominence, and overall bone sharpness are weighted more heavily. This reflects the real, documented differences in how male and female attractiveness is evaluated within East Asian aesthetic culture.

---

## 设计理念 / Design Philosophy

### 诚实，不是安慰
颜圣不会因为你付钱就给你高分，不会因为算法可能让你不开心就给你中性分。如果你的面部比例存在明显问题，报告会如实反映。如果你的骨相出色但有一个明显短板，报告会同时告诉你这两点。

YanSheng doesn't inflate scores because you paid, and doesn't give neutral scores because the algorithm might make you feel bad. If your facial proportions have a notable issue, the report reflects that. If your bone structure is strong but you have a specific weak point, the report tells you both.

### 可操作，不是评判
所有改善方向都指向你能做的事情，不是你没有的骨骼。发型、妆容、护肤、色彩搭配、面部训练——这些是你可以控制的变量。颜圣给你的是这些变量里效益最大的那一个，而不是一份让你沮丧的清单。

All improvement directions point to things you can actually do, not bones you don't have. Hairstyle, makeup, skincare, color choices, facial exercises — these are controllable variables. YanSheng gives you the single highest-leverage one, not a discouraging laundry list.

### 亚洲人的标准，不是西方标准的复制
用西方标准分析亚洲面孔会系统性地低估亚洲面部特征的美学价值——高鼻梁、深眼窝、强眉骨在西方标准下得分高，但这些特征在亚洲面孔上并不常见，也不应该成为评判亚洲面孔的基准。颜圣明确拒绝这种标准迁移。

Using Western standards to analyze Asian faces systematically undervalues Asian facial features — high nose bridges, deep-set eyes, and strong brow ridges score well in Western frameworks, but these aren't common in Asian faces and shouldn't be the benchmark for evaluating them. YanSheng explicitly rejects this standard transfer.

---

## 隐私承诺 / Privacy Commitment

颜圣从设计上就不收集身份信息。你的面部数据不与你的姓名、邮箱、手机号或Apple ID绑定。扫描结果只关联一个随机生成的匿名ID。你可以随时在App内删除全部数据。面部图像传输至Anthropic用于AI推理，根据Anthropic的API数据政策不会被用于模型训练。

YanSheng is designed from the ground up to not collect identity information. Your face is never linked to your name, email, phone number, or Apple ID. Scan results are associated only with a randomly generated anonymous ID. You can delete all data at any time from within the app. Facial images are transmitted to Anthropic for AI inference and are not used for model training per Anthropic's API data policy.

Full privacy policy: [Privacy Policy](privacy_policy)

---

## 联系 / Contact

Questions, feedback, or data deletion requests: byip803@gmail.com

We respond to all inquiries within 30 days.

---

[← Back to Home](index) | [Women's Analysis](women) | [Men's Analysis](men) | [FAQ](faq)
