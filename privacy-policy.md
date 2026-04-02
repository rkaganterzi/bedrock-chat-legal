# Privacy Policy — Bedrock Chat

**Last Updated:** April 2, 2026

## Overview

Bedrock Chat ("the App") is an iOS application that allows users to interact with AI models through their own AWS Bedrock credentials. This privacy policy explains how the App handles user data.

## Data Collection

### What We Do NOT Collect
- We do **not** collect, store, or transmit your personal information to our servers
- We do **not** have any backend servers or cloud infrastructure
- We do **not** use analytics, tracking, or advertising frameworks
- We do **not** collect your AWS credentials — they are stored locally on your device

### What Is Stored Locally on Your Device
- **AWS Credentials:** Stored in the iOS Keychain (encrypted, device-only)
- **Conversation History:** Stored in SwiftData (local database on your device)
- **Usage Statistics:** Token usage data stored locally for cost estimation (Pro feature)
- **App Preferences:** Onboarding status and daily message count stored in UserDefaults

### iCloud Sync (Pro Feature)
If you enable iCloud sync (Pro subscription), your conversation data is synced via Apple's CloudKit service. This data is:
- Encrypted in transit and at rest by Apple
- Stored in your personal iCloud account
- Subject to Apple's iCloud privacy policy
- Deletable by you at any time through Settings > iCloud

## Third-Party Services

### AWS Bedrock
The App communicates directly with Amazon Web Services (AWS) Bedrock API using **your own credentials**. Your messages and AI responses are processed by AWS according to their privacy policy. We have no access to your AWS account or data.

### Apple StoreKit
In-app purchases are processed by Apple. We do not receive or store your payment information.

### Apple CloudKit (Pro)
iCloud sync uses Apple's CloudKit infrastructure. Data is managed under Apple's privacy policy.

## Data Security
- AWS credentials are stored using iOS Keychain Services with `kSecAttrAccessibleWhenUnlockedThisDeviceOnly` protection
- All network communication uses HTTPS (TLS 1.2+)
- No data leaves your device except to AWS (using your credentials) and Apple (iCloud sync, if enabled)

## Children's Privacy
The App is not directed at children under 13. We do not knowingly collect information from children.

## Your Rights
Since all data is stored locally on your device:
- **Access:** You can view all your data within the App
- **Deletion:** Delete the App to remove all local data, or use in-app options to clear conversations
- **Portability:** Use the export feature (Pro) to download your data

## GDPR & KVKK Compliance
As we do not collect or process personal data on our servers, GDPR and KVKK data processing requirements do not apply to our operations. Your data remains under your control on your device and in your AWS/iCloud accounts.

## Changes to This Policy
We may update this privacy policy from time to time. Changes will be posted here with an updated date.

## Contact
If you have questions about this privacy policy, contact us at:
**Email:** kaganterzi@gmail.com

---

*Note: This privacy policy is provided as a template. Consult a legal professional for compliance with applicable laws in your jurisdiction.*
