# AI Guard: PII Defender & FinOps Dashboard

## Overview
AI Guard is a privacy-focused browser extension that protects sensitive personal information (PII) while monitoring AI spending across major AI chat platforms including ChatGPT, Claude, Gemini, Copilot, and DeepSeek.

## Key Features

### Real-Time PII Protection
- **Email Protection**: Masks email addresses before submission
- **Financial Data**: Protects credit card numbers, IBAN, and bank identifiers
- **Identity Documents**: Masks SSN, CNIC, Aadhaar, and date-of-birth labels
- **Contact Info**: Protects phone numbers in various formats

### FinOps Dashboard
- **Real-Time Cost Tracking**: Monitor your AI platform spending
- **Usage Analytics**: Word count and cost breakdown per platform
- **Leak Detection**: Track blocked PII exposure attempts
- **PDF Audit Reports**: Generate tamper-detection audit reports with SHA-256 fingerprints

## Supported Platforms
- ChatGPT (chat.openai.com, chatgpt.com)
- Claude (claude.ai)
- Google Gemini (gemini.google.com)
- Microsoft Copilot (copilot.microsoft.com)
- DeepSeek (chat.deepseek.com, deepseek.com)
- Perplexity (www.perplexity.ai)
- Poe (poe.com)
- Mistral Chat (chat.mistral.ai)
- Grok on X (x.com/i/grok*)

## How It Works

1. **Detection**: Extension monitors prompt inputs on supported AI platforms
2. **Masking**: Sensitive data is replaced with `[PROTECTED_TYPE]` before submission
3. **Logging**: Usage metrics and leak blocks are recorded locally
4. **Reporting**: Generate PDF audit reports with integrity verification

## Privacy & Data
- **Local-Only Storage**: All data is stored locally in browser extension storage
- **No Cloud Upload**: No data is sent to external servers
- **No Tracking**: No user tracking or analytics
- **Full Control**: Users can clear all data anytime

## Data Stored Locally

- Total spending calculation
- Per-platform word counts
- Blocked leak attempts count
- Report generation timestamps
- Integrity hashes for report verification

## Permissions Used

- `storage`: Required to maintain local usage statistics and audit data

## Report Integrity
Generated PDF reports include:
- Generation timestamp (UTC)
- Per-platform breakdown
- SHA-256 integrity fingerprint to detect modifications
- Protected PII type list

## Installation

1. Download the extension from Chrome Web Store
2. Click "Add to Chrome"
3. Visit any supported AI chat platform to start protection
4. Click the extension icon to view dashboard and generate reports

## Support

For issues or feature requests, contact at: saq215321@gmail.com

## Version History
## Version 1.0.0
- Initial release with core PII protection and FinOps dashboard features.
- PII masking for 8 sensitive data types
- Real-time cost tracking
- PDF audit report generation