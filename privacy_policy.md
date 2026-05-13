# Privacy Policy — YanSheng (颜圣)

**Last Updated: May 12, 2026**

---

## Introduction

YanSheng (颜圣) is an East Asian facial aesthetics diagnosis application for iOS, developed and operated by an individual developer ("we," "us," or "our"). This Privacy Policy explains what information we collect when you use YanSheng, how we use and protect that information, and what rights and choices you have.

**By downloading or using YanSheng, you confirm that you are at least 18 years of age and agree to the practices described in this Privacy Policy.** If you do not agree, please do not use the App.

---

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

## 2. How We Use Your Information

We use the information we collect exclusively to:

- Deliver the App's core feature: AI-based facial aesthetics analysis and reporting.
- Generate style preview images based on your facial features (via the "Copy Homework" feature).
- Validate and fulfill in-app purchase credits.
- Maintain app stability and fix technical errors.
- Improve the accuracy and quality of our analysis models over time (using aggregated, non-identifiable data only).

We do **not** use your information to serve advertisements, build marketing profiles, or contact you for promotional purposes.

---

## 3. Facial Image Data — Special Disclosures

Because facial images may constitute sensitive biometric or personal data under applicable law, we make the following specific disclosures:

| Topic | Our Practice |
|---|---|
| **Collection trigger** | Only when you explicitly tap "Start Scan" — never passively or in the background |
| **Storage location** | Firebase Cloud Storage (Google LLC), hosted on Google-operated servers |
| **Retention period** | Until you delete your scan results or uninstall the App, whichever comes first |
| **Third-party sharing** | Shared only with AI processing services (Anthropic, Replicate) under strict data processing terms — never sold or shared for advertising |
| **Identity linkage** | None — your face is never linked to your name, account, or contact details |
| **User control** | You may delete any scan result at any time from within the App |

---

## 4. Third-Party Services

We integrate the following third-party services. Each operates under its own privacy policy and may process your data on its infrastructure.

### 4.1 Anthropic (Claude API)

We send your facial image to Anthropic's API to perform AI-based aesthetic analysis, including facial proportion measurements, feature evaluations, and written narrative reports.

- **Data sent:** Facial photograph(s)
- **Purpose:** AI analysis and report generation
- **Anthropic Privacy Policy:** [https://www.anthropic.com/privacy](https://www.anthropic.com/privacy)

Anthropic processes your image to return analysis results. Images submitted via API are not used by Anthropic to train their models without separate consent.

### 4.2 Replicate (InstantID)

The "Copy Homework" (抄作业) feature sends your facial image to Replicate's API to generate style reference preview images showing how certain aesthetic styles might look applied to your features.

- **Data sent:** Facial photograph(s) and style reference prompts
- **Purpose:** AI image generation for style preview
- **Replicate Privacy Policy:** [https://replicate.com/privacy](https://replicate.com/privacy)

Use of this feature is entirely optional and user-initiated.

### 4.3 Firebase (Google LLC)

We use Firebase as our backend infrastructure for data storage, serverless functions, and session management.

- **Data stored:** Anonymous session ID, scan results (derived metrics and scores), facial images (temporarily), purchase receipts
- **Purpose:** App functionality, data persistence, and backend processing
- **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

Firebase servers may be located in the United States or other countries where Google operates data centers.

### 4.4 Apple App Store

All in-app purchases (scan credit packages) are processed exclusively by Apple Inc. through the App Store payment system.

- **Data handled by Apple:** Payment information, purchase history
- **Purpose:** Payment processing and transaction verification
- **Apple Privacy Policy:** [https://www.apple.com/legal/privacy](https://www.apple.com/legal/privacy)

We receive only a confirmation token from Apple; we never handle your payment card details.

---

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

## 6. Data Sharing and Disclosure

We do **not** sell, rent, license, or trade your personal information or facial data to any third party.

We share data only in the following limited circumstances:

- **With AI service providers** (Anthropic, Replicate) to perform analysis you explicitly requested, under contractual data processing agreements.
- **With Firebase/Google** as our infrastructure provider, under Google's data processing terms.
- **With Apple** to validate and fulfill in-app purchases.
- **If required by law:** We may disclose data if compelled by a valid legal process (e.g., court order or government demand), and will notify you to the extent permitted by law.
- **In a business transfer:** If our operations are transferred or acquired, your data would transfer subject to the same protections described in this Policy.

---

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

## 8. Age Restriction

**YanSheng is intended solely for users who are 18 years of age or older.** We do not knowingly collect data from anyone under 18. By using the App, you represent that you are at least 18 years old.

If we become aware that a user under 18 has submitted facial data through the App, we will promptly delete that data. If you believe a minor has used YanSheng, please contact us immediately at **byip803@gmail.com**.

---

## 9. Data Security

We implement appropriate technical and organizational measures to protect your data, including:

- Encryption of data in transit (TLS/HTTPS) and at rest (AES-256 via Firebase)
- Access controls limiting who can access backend data
- No storage of payment card data

However, no system is completely secure. We cannot guarantee absolute security of your data. In the event of a data breach that affects your rights, we will notify affected users as required by applicable law.

---

## 10. Automated Scoring and AI-Generated Decisions (GDPR Article 22)

YanSheng uses artificial intelligence to generate facial aesthetic scores, descriptive evaluations, and style recommendations based on your facial image. We make the following disclosures about this automated processing:

**Nature of the analysis.** All scores, ratings, descriptive labels, and recommendations produced by the App are generated solely by AI algorithms. They represent a subjective aesthetic assessment within an East Asian beauty framework and do not constitute an objective, medical, psychological, or professional evaluation of your appearance or personal worth.

**No legal or similarly significant effects.** The scores and descriptions generated by YanSheng are provided for personal reference and entertainment purposes only. They do not produce legal effects, affect your access to services, employment, insurance, credit, or any other consequential domain.

**Your right to contest automated decisions.** In accordance with GDPR Article 22, if you believe an AI-generated result is inaccurate or has affected you in a way you consider significant, you have the right to request human review of that output and to express your point of view. To exercise this right, contact us at byip803@gmail.com. We will respond within 30 days.

**Basis for processing.** We process your facial data for automated analysis on the basis of your explicit consent, which you provide before initiating any scan or image upload. You may withdraw this consent at any time by deleting your scan data within the App.

**Wellness notice.** Aesthetic scoring applications may affect how users feel about their appearance. If you find the results distressing, you are encouraged to discontinue use and, if needed, speak with a qualified mental health professional. The App's results are not intended to define your self-worth.

---

## 11. International Data Transfers

Your facial image and analysis data may be transferred to and processed in the United States, where our service providers (Anthropic, Google/Firebase, Replicate) operate. If you are located in the European Economic Area or other regions with data transfer restrictions, please be aware that these countries may have different data protection laws. We rely on our service providers' standard contractual clauses or other lawful transfer mechanisms.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. When we make material changes, we will notify you by displaying a notice within the App before the change takes effect. The "Last Updated" date at the top of this Policy will always reflect the most recent revision. Continued use of the App after the effective date of any changes constitutes your acceptance of the updated Policy.

---

## 13. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact:

**YanSheng (颜圣)**
Individual Developer
Email: **byip803@gmail.com**

We will respond to all inquiries within 30 days.

---

*By using YanSheng, you acknowledge that you have read and understood this Privacy Policy.*
