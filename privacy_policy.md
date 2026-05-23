# 隐私政策 — 颜圣（YanSheng）

# Privacy Policy — YanSheng (颜圣)

**最后更新：2026 年 5 月 12 日**

**Last Updated: May 12, 2026**

---

## 简介

颜圣（YanSheng）是一款面向 iOS 平台的东亚面部美学诊断应用，由个人开发者（以下简称"我们"）开发和运营。本隐私政策说明我们在您使用颜圣时收集哪些信息、如何使用和保护这些信息，以及您享有哪些权利和选择。

**下载或使用颜圣，即表示您确认您已年满 18 周岁，并同意本隐私政策中描述的做法。** 如您不同意，请勿使用本应用。

## Introduction

YanSheng (颜圣) is an East Asian facial aesthetics diagnosis application for iOS, developed and operated by an individual developer ("we," "us," or "our"). This Privacy Policy explains what information we collect when you use YanSheng, how we use and protect that information, and what rights and choices you have.

**By downloading or using YanSheng, you confirm that you are at least 18 years of age and agree to the practices described in this Privacy Policy.** If you do not agree, please do not use the App.

---

## 1. 我们收集的信息

### 1.1 面部图像数据（敏感信息）

颜圣的核心功能需要分析您的面部照片。当您发起面部扫描时，应用会通过您设备的摄像头拍摄一张或多张面部图像。这些图像将：

- 仅为进行 AI 美学分析的目的，传输至我们的后端基础设施（Firebase Cloud Storage）。
- 由第三方 AI 服务（详见第 4 条）处理，以生成测量数据、比例评分和风格建议。
- 临时存储，且仅与您设备上的匿名会话标识符关联。您的面部数据不与任何姓名、电子邮件地址或身份信息绑定。
- 您可随时要求删除（详见第 7 条）。

**我们不会将面部图像数据用于身份验证、生物特征认证或任何形式的用户识别。**

### 1.2 衍生分析数据

AI 处理完成后，我们会在 Firebase 中存储您的扫描结果，包括面部比例指标、美学评分、各部位评估及风格建议。分析完成后，衍生数据不包含原始图像像素，除非您尚未申请删除原始图像。

### 1.3 设备与技术信息

我们自动收集应用正常运行所需的有限技术数据，包括：

- 设备类型、iOS 版本及屏幕分辨率（用于显示优化）
- 匿名会话或安装标识符（随机生成，不与您的身份关联）
- 应用崩溃日志和错误报告（用于调试）

我们**不**收集您的姓名、电子邮件地址、电话号码、精确位置、通讯录或任何其他可识别个人身份的信息。

### 1.4 购买记录

如果您通过 Apple App Store 购买扫描积分套餐，Apple 将处理您的付款并向我们提供确认购买的交易凭证。我们不接收、存储或处理您的支付卡信息。购买凭证存储在 Firebase 中，用于为您的账户充入正确数量的扫描次数。

## 1. Information We Collect

### 1.1 Facial Image Data (Sensitive)

YanSheng's core functionality requires analyzing photographs of your face. When you initiate a facial scan, the App captures one or more images of your face from your device camera. These images are:

- Transmitted to our backend infrastructure (Firebase Cloud Storage) solely for the purpose of AI-powered aesthetic analysis.
- Processed by third-party AI services (described in Section 4) to generate measurement data, proportion scores, and style recommendations.
- Retained temporarily and linked only to an anonymous session identifier on your device. No name, email address, or identity is associated with your face data.
- Subject to deletion at any time at your request (see Section 7).

**We do not use facial image data for identity verification, biometric authentication, or user recognition of any kind.**

### 1.2 Derived Analysis Data

Following AI processing, we store the results of your scan — including facial proportion metrics, aesthetic scores, section-level evaluations, and style suggestions — in Firebase. This derived data does not contain raw image pixels after analysis is complete, unless you have not yet requested deletion of your original image.

### 1.3 Device and Technical Information

We automatically collect limited technical data necessary for the App to function, including:

- Device type, iOS version, and screen resolution (for display optimization)
- Anonymous session or installation identifier (randomly generated; not linked to your identity)
- App crash logs and error reports (for debugging purposes)

We do **not** collect your name, email address, phone number, precise location, contacts, or any other personally identifying information.

### 1.4 Purchase Records

If you purchase a scan credit package via the Apple App Store, Apple processes your payment and provides us with a transaction receipt confirming the purchase. We do not receive, store, or process your payment card details. Purchase receipts are stored in Firebase to credit your account with the correct number of scans.

---

## 2. 我们如何使用您的信息

我们仅将所收集的信息用于以下目的：

- 提供应用的核心功能：基于 AI 的面部美学分析与报告。
- 根据您的面部特征生成风格预览图（通过"抄作业"功能）。
- 验证并履行应用内购买积分。
- 维护应用稳定性并修复技术错误。
- 随时间推移提升分析模型的准确性和质量（仅使用汇总的、不可识别个人身份的数据）。

我们**不**将您的信息用于投放广告、建立营销档案或以促销为目的联系您。

## 2. How We Use Your Information

We use the information we collect exclusively to:

- Deliver the App's core feature: AI-based facial aesthetics analysis and reporting.
- Generate style preview images based on your facial features (via the "Copy Homework" feature).
- Validate and fulfill in-app purchase credits.
- Maintain app stability and fix technical errors.
- Improve the accuracy and quality of our analysis models over time (using aggregated, non-identifiable data only).

We do **not** use your information to serve advertisements, build marketing profiles, or contact you for promotional purposes.

---

## 3. 面部图像数据——特别披露

由于面部图像在适用法律下可能构成敏感生物特征或个人数据，我们作出以下具体披露：

| 事项 | 我们的做法 |
|---|---|
| **收集触发条件** | 仅在您明确点击"开始扫描"时触发——绝不被动收集或在后台收集 |
| **存储位置** | Firebase Cloud Storage（Google LLC），托管于 Google 运营的服务器 |
| **保留期限** | 直至您删除扫描结果或卸载应用（以先发生者为准） |
| **第三方共享** | 仅在严格数据处理条款下与 AI 处理服务（Anthropic）共享——绝不出售或用于广告目的共享 |
| **身份关联** | 无——您的面部数据绝不与您的姓名、账户或联系方式关联 |
| **用户控制** | 您可随时在应用内删除任何扫描结果 |

## 3. Facial Image Data — Special Disclosures

Because facial images may constitute sensitive biometric or personal data under applicable law, we make the following specific disclosures:

| Topic | Our Practice |
|---|---|
| **Collection trigger** | Only when you explicitly tap "Start Scan" — never passively or in the background |
| **Storage location** | Firebase Cloud Storage (Google LLC), hosted on Google-operated servers |
| **Retention period** | Until you delete your scan results or uninstall the App, whichever comes first |
| **Third-party sharing** | Shared only with the AI processing service (Anthropic) under strict data processing terms — never sold or shared for advertising |
| **Identity linkage** | None — your face is never linked to your name, account, or contact details |
| **User control** | You may delete any scan result at any time from within the App |

---

## 4. 第三方服务

我们接入了以下第三方服务。各服务依据其自身隐私政策运营，可能在其基础设施上处理您的数据。

### 4.1 Anthropic（Claude API）

我们将您的面部图像发送至 Anthropic 的 API，以执行基于 AI 的美学分析，包括面部比例测量、五官评估及文字叙述报告。

- **发送数据：** 面部照片
- **目的：** AI 分析与报告生成
- **Anthropic 隐私政策：** [https://www.anthropic.com/privacy](https://www.anthropic.com/privacy)

Anthropic 处理您的图像以返回分析结果。通过 API 提交的图像未经单独授权，不会被 Anthropic 用于训练其模型。

### 4.2 Firebase（Google LLC）

我们使用 Firebase 作为后端基础设施，用于数据存储、无服务器函数及会话管理。

- **存储数据：** 匿名会话 ID、扫描结果（衍生指标和评分）、面部图像（临时）、购买凭证
- **目的：** 应用功能、数据持久化及后端处理
- **Google 隐私政策：** [https://policies.google.com/privacy](https://policies.google.com/privacy)

Firebase 服务器可能位于美国或 Google 运营数据中心的其他国家。

### 4.3 Apple App Store

所有应用内购买（扫描积分套餐）均由 Apple Inc. 通过 App Store 支付系统独家处理。

- **Apple 处理的数据：** 支付信息、购买历史
- **目的：** 支付处理与交易验证
- **Apple 隐私政策：** [https://www.apple.com/legal/privacy](https://www.apple.com/legal/privacy)

我们仅从 Apple 接收确认令牌，从不处理您的支付卡信息。

## 4. Third-Party Services

We integrate the following third-party services. Each operates under its own privacy policy and may process your data on its infrastructure.

### 4.1 Anthropic (Claude API)

We send your facial image to Anthropic's API to perform AI-based aesthetic analysis, including facial proportion measurements, feature evaluations, and written narrative reports.

- **Data sent:** Facial photograph(s)
- **Purpose:** AI analysis and report generation
- **Anthropic Privacy Policy:** [https://www.anthropic.com/privacy](https://www.anthropic.com/privacy)

Anthropic processes your image to return analysis results. Images submitted via API are not used by Anthropic to train their models without separate consent.

### 4.2 Firebase (Google LLC)

We use Firebase as our backend infrastructure for data storage, serverless functions, and session management.

- **Data stored:** Anonymous session ID, scan results (derived metrics and scores), facial images (temporarily), purchase receipts
- **Purpose:** App functionality, data persistence, and backend processing
- **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

Firebase servers may be located in the United States or other countries where Google operates data centers.

### 4.3 Apple App Store

All in-app purchases (scan credit packages) are processed exclusively by Apple Inc. through the App Store payment system.

- **Data handled by Apple:** Payment information, purchase history
- **Purpose:** Payment processing and transaction verification
- **Apple Privacy Policy:** [https://www.apple.com/legal/privacy](https://www.apple.com/legal/privacy)

We receive only a confirmation token from Apple; we never handle your payment card details.

---

## 5. 数据存储、保留与删除

### 存储

所有应用数据存储于 Firebase（Google Cloud 基础设施）。面部图像和衍生分析数据采用 Google 的安全控制措施存储，包括静态加密和传输加密。

### 保留期限

| 数据类型 | 保留期限 |
|---|---|
| 面部照片 | 直至您删除该扫描记录，或卸载应用 |
| 分析结果（评分、指标） | 直至您删除该扫描记录，或卸载应用 |
| 购买凭证 | 为防欺诈及法律合规，保留最长 2 年 |
| 设备/会话标识符 | 卸载应用时删除 |

### 删除

您可随时直接在应用内删除面部扫描数据。删除后，对应图像及衍生指标将从 Firebase 中永久移除。由于我们的系统完全匿名且无账户体系，不存在"注销账户"流程——卸载应用将删除所有本地存储的数据。

如您希望申请删除我们后端保留的任何数据，请通过第 10 条中的联系方式与我们联系。

## 5. Data Storage, Retention, and Deletion

### Storage

All App data is stored in Firebase (Google Cloud infrastructure). Facial images and derived analysis data are stored using Google's security controls, including encryption at rest and in transit.

### Retention

| Data Type | Retention Period |
|---|---|
| Facial photographs | Until you delete the scan, or until you uninstall the App |
| Analysis results (scores, metrics) | Until you delete the scan, or until you uninstall the App |
| Purchase receipts | Retained for up to 2 years for fraud prevention and legal compliance |
| Device/session identifiers | Deleted when you uninstall the App |

### Deletion

You can delete your facial scan data at any time directly within the App. Upon deletion, the corresponding image and derived metrics are permanently removed from Firebase. Because our system is fully anonymous with no account, there is no "account deletion" process — uninstalling the App removes all locally stored data.

If you wish to request deletion of any data retained in our backend, please contact us at the address in Section 10.

---

## 6. 数据共享与披露

我们**不**向任何第三方出售、出租、授权或交易您的个人信息或面部数据。

我们仅在以下有限情形下共享数据：

- **与 AI 服务提供商**（Anthropic）共享，以执行您明确请求的分析，依据合同数据处理协议进行。
- **与 Firebase/Google** 共享，作为我们的基础设施提供商，依据 Google 数据处理条款进行。
- **与 Apple** 共享，用于验证和履行应用内购买。
- **法律要求时：** 如受到有效法律程序（如法院命令或政府要求）强制要求，我们可能披露数据，并在法律允许的范围内通知您。
- **业务转让时：** 如我们的业务被转让或收购，您的数据将随之转让，但仍受本政策所述相同保护措施约束。

## 6. Data Sharing and Disclosure

We do **not** sell, rent, license, or trade your personal information or facial data to any third party.

We share data only in the following limited circumstances:

- **With the AI service provider** (Anthropic) to perform analysis you explicitly requested, under a contractual data processing agreement.
- **With Firebase/Google** as our infrastructure provider, under Google's data processing terms.
- **With Apple** to validate and fulfill in-app purchases.
- **If required by law:** We may disclose data if compelled by a valid legal process (e.g., court order or government demand), and will notify you to the extent permitted by law.
- **In a business transfer:** If our operations are transferred or acquired, your data would transfer subject to the same protections described in this Policy.

---

## 7. 您的隐私权利

根据您所在地区，您可能对自己的数据享有以下权利：

### 所有用户
- **删除权：** 随时在应用内删除您的扫描数据，或联系我们申请删除我们持有的任何数据。
- **知情权：** 申请了解我们持有您的哪些数据。

### 欧洲经济区、英国及瑞士（GDPR）
除上述权利外，您还享有以下权利：
- **访问权** — 获取您个人数据的副本。
- **更正权** — 更正不准确的数据。
- **限制权或反对权** — 限制或反对对您数据的处理。
- **数据可携权** — 以结构化、机器可读的格式接收您的数据。
- **投诉权** — 向您所在地的数据保护机构提出投诉。

我们处理面部数据的法律依据是您的**明确同意**，即您发起扫描时所给予的同意。您可随时通过在应用内删除扫描数据来撤回此同意。

### 加利福尼亚州居民（CCPA/CPRA）
您有权了解我们收集哪些个人信息、申请删除，以及选择退出个人信息的"出售"。**我们不出售个人信息。**

如需行使上述任何权利，请联系：**byip803@gmail.com**

我们将在 30 天内回复可核实的请求。

## 7. Your Privacy Rights

Depending on where you reside, you may have the following rights regarding your data:

### All Users
- **Right to delete:** Delete your scan data at any time within the App, or contact us to request deletion of any data we hold.
- **Right to know:** Request information about what data we hold about you.

### European Economic Area, UK, and Switzerland (GDPR)
In addition to the above, you have the right to:
- **Access** a copy of your personal data.
- **Rectify** inaccurate data.
- **Restrict** or **object** to processing of your data.
- **Data portability** — receive your data in a structured, machine-readable format.
- **Lodge a complaint** with your local data protection authority.

The legal basis for our processing of facial data is your **explicit consent**, given when you initiate a scan. You may withdraw this consent at any time by deleting your scan data.

### California Residents (CCPA/CPRA)
You have the right to know what personal information we collect, request deletion, and opt out of the "sale" of personal information. **We do not sell personal information.**

To exercise any of these rights, contact us at: **byip803@gmail.com**

We will respond to verifiable requests within 30 days.

---

## 8. 年龄限制

**颜圣仅面向 18 周岁及以上的用户。** 我们不会在知情情况下收集 18 岁以下人员的数据。使用本应用，即表示您声明您已年满 18 周岁。

如我们发现有未满 18 周岁的用户通过应用提交了面部数据，我们将立即删除该数据。如您认为有未成年人使用了颜圣，请立即通过 **byip803@gmail.com** 联系我们。

## 8. Age Restriction

**YanSheng is intended solely for users who are 18 years of age or older.** We do not knowingly collect data from anyone under 18. By using the App, you represent that you are at least 18 years old.

If we become aware that a user under 18 has submitted facial data through the App, we will promptly delete that data. If you believe a minor has used YanSheng, please contact us immediately at **byip803@gmail.com**.

---

## 9. 数据安全

我们采取适当的技术和组织措施保护您的数据，包括：

- 传输中的数据加密（TLS/HTTPS）及静态数据加密（通过 Firebase 的 AES-256）
- 限制后端数据访问权限的访问控制
- 不存储支付卡数据

然而，没有任何系统是完全安全的。我们无法保证您数据的绝对安全。如发生影响您权利的数据泄露事件，我们将依据适用法律的要求通知受影响用户。

## 9. Data Security

We implement appropriate technical and organizational measures to protect your data, including:

- Encryption of data in transit (TLS/HTTPS) and at rest (AES-256 via Firebase)
- Access controls limiting who can access backend data
- No storage of payment card data

However, no system is completely secure. We cannot guarantee absolute security of your data. In the event of a data breach that affects your rights, we will notify affected users as required by applicable law.

---

## 10. 自动评分与 AI 生成决策（GDPR 第 22 条）

颜圣使用人工智能，根据您的面部图像生成面部美学评分、描述性评估和风格建议。我们就此自动化处理作出以下披露：

**分析的性质。** 应用生成的所有评分、评级、描述性标签和建议均完全由 AI 算法生成。它们代表在东亚美学框架下的主观美学评估，不构成对您外貌或个人价值的客观、医学、心理或专业评估。

**无法律或类似重大影响。** 颜圣生成的评分和描述仅供个人参考和娱乐之用。它们不产生法律效力，不影响您获取服务、就业、保险、信贷或任何其他重要领域的机会。

**对自动决策提出异议的权利。** 根据 GDPR 第 22 条，如您认为某项 AI 生成结果不准确，或以您认为重大的方式影响了您，您有权要求对该结果进行人工审核并表达您的观点。如需行使此权利，请联系 byip803@gmail.com。我们将在 30 天内回复。

**处理依据。** 我们基于您的明确同意处理您的面部数据进行自动分析，此同意在您发起任何扫描或图像上传之前由您提供。您可随时通过在应用内删除扫描数据来撤回此同意。

**健康提示。** 美学评分应用可能影响用户对自身外貌的感受。如果您对结果感到困扰，建议您停止使用，并在必要时寻求专业心理健康人士的帮助。应用的结果无意定义您的自我价值。

## 10. Automated Scoring and AI-Generated Decisions (GDPR Article 22)

YanSheng uses artificial intelligence to generate facial aesthetic scores, descriptive evaluations, and style recommendations based on your facial image. We make the following disclosures about this automated processing:

**Nature of the analysis.** All scores, ratings, descriptive labels, and recommendations produced by the App are generated solely by AI algorithms. They represent a subjective aesthetic assessment within an East Asian beauty framework and do not constitute an objective, medical, psychological, or professional evaluation of your appearance or personal worth.

**No legal or similarly significant effects.** The scores and descriptions generated by YanSheng are provided for personal reference and entertainment purposes only. They do not produce legal effects, affect your access to services, employment, insurance, credit, or any other consequential domain.

**Your right to contest automated decisions.** In accordance with GDPR Article 22, if you believe an AI-generated result is inaccurate or has affected you in a way you consider significant, you have the right to request human review of that output and to express your point of view. To exercise this right, contact us at byip803@gmail.com. We will respond within 30 days.

**Basis for processing.** We process your facial data for automated analysis on the basis of your explicit consent, which you provide before initiating any scan or image upload. You may withdraw this consent at any time by deleting your scan data within the App.

**Wellness notice.** Aesthetic scoring applications may affect how users feel about their appearance. If you find the results distressing, you are encouraged to discontinue use and, if needed, speak with a qualified mental health professional. The App's results are not intended to define your self-worth.

---

## 11. 国际数据传输

您的面部图像和分析数据可能被传输至美国并在美国进行处理，我们的服务提供商（Anthropic、Google/Firebase）在该国运营。如果您位于欧洲经济区或其他有数据传输限制的地区，请注意这些国家可能拥有不同的数据保护法律。我们依赖服务提供商的标准合同条款或其他合法传输机制。

## 11. International Data Transfers

Your facial image and analysis data may be transferred to and processed in the United States, where our service providers (Anthropic, Google/Firebase) operate. If you are located in the European Economic Area or other regions with data transfer restrictions, please be aware that these countries may have different data protection laws. We rely on our service providers' standard contractual clauses or other lawful transfer mechanisms.

---

## 12. 本隐私政策的变更

我们可能会不时更新本隐私政策，以反映我们做法或法律要求的变化。当我们作出重大变更时，我们将在变更生效前通过应用内通知告知您。本政策顶部的"最后更新"日期将始终反映最新修订版本。在任何变更生效日期后继续使用本应用，即表示您接受更新后的政策。

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. When we make material changes, we will notify you by displaying a notice within the App before the change takes effect. The "Last Updated" date at the top of this Policy will always reflect the most recent revision. Continued use of the App after the effective date of any changes constitutes your acceptance of the updated Policy.

---

## 13. 联系我们

如您对本隐私政策或您的数据有任何疑问、顾虑或请求，请联系：

**颜圣（YanSheng）**
个人开发者
电子邮件：**byip803@gmail.com**

我们将在 30 天内回复所有询问。

## 13. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact:

**YanSheng (颜圣)**
Individual Developer
Email: **byip803@gmail.com**

We will respond to all inquiries within 30 days.

---

*使用颜圣，即表示您已阅读并理解本隐私政策。*

*By using YanSheng, you acknowledge that you have read and understood this Privacy Policy.*
