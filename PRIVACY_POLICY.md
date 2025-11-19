# Privacy Policy for Daily Spend

**Last Updated: November 18, 2025**

## Introduction

Daily Spend ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application Daily Spend (the "App") handles your information.

## Data We Collect

### Data Stored Locally

Daily Spend is a **local-first application**. All your financial data is stored locally on your device using IndexedDB and never leaves your device. This includes:

- Expense records (amount, date, category, store name, description)
- Custom categories you create
- Budget settings and preferences
- App settings and customizations

### Data Accessed by the App

The App requests access to the following device features:

- **Microphone**: To enable voice input for adding expenses
- **Speech Recognition**: To convert your voice into expense entries

## Third-Party Services

### AI Expense Parsing

When you use the AI Chat Assistant feature, your text input is sent to:
- **Supabase Edge Functions**: Processes your request
- **Google Gemini AI**: Parses natural language to extract expense information

**Important**: Only the text of your message is sent. Your message is processed temporarily and is not stored by these services. No other personal or financial data is shared with third parties.

### What We Don't Collect

We do NOT collect, store, or transmit:
- Your financial data or expense history
- Personal identifying information
- Device identifiers
- Location data
- Analytics or usage data
- Any data for advertising purposes

## Data Storage and Security

- All expense data is stored locally on your device using encrypted IndexedDB
- Your data never leaves your device except for temporary AI message processing
- We have no access to your expense data
- We cannot recover your data if you delete the app or lose your device

## Data Sharing

We do not share your data with any third parties, except:
- **AI Message Processing**: Your text messages to the AI assistant are temporarily sent to Google Gemini for processing only

We do not sell, rent, or trade your personal information.

## Your Rights and Choices

You have complete control over your data:

### Data Access
- All your data is accessible within the app
- You can export your data as CSV or JSON at any time from the Settings page

### Data Deletion
- Delete individual expenses within the app
- Clear all data from the Settings page
- Uninstalling the app will permanently delete all local data

### Revoking Permissions
You can revoke app permissions at any time through your device settings:
- iOS: Settings > Daily Spend > Permissions

## Children's Privacy

Our App does not knowingly collect information from children under 13 years of age. If we become aware that a child under 13 has provided us with personal information, we will delete it immediately.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date
- Posting the new Privacy Policy in the app
- Showing an in-app notification for material changes

## Data Retention

Since all data is stored locally on your device:
- Data persists until you delete it or uninstall the app
- We do not retain any of your data on our servers
- AI message text is not retained after processing

## Contact Us

If you have questions about this Privacy Policy, please contact us:

- Email: [YOUR_EMAIL_HERE]
- GitHub: https://github.com/alamashir/expense-journal-app/issues

## Legal Compliance

This Privacy Policy complies with:
- Apple App Store Guidelines
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)

## Consent

By using Daily Spend, you consent to this Privacy Policy and agree to its terms.

---

## For App Store Submission

### Privacy Nutrition Labels

**Data Collection Summary for App Store Connect:**

**Data Not Collected:**
- No data is collected, stored, or shared with the developer or third parties
- All expense data remains on your device only

**Data Used for Tracking:**
- None

**Data Linked to You:**
- None

**Data Not Linked to You:**
- None

**Third-Party AI Disclosure:**
- AI Chat Assistant uses Google Gemini 2.0 Flash
- Only your chat message text is sent for expense parsing
- Messages are processed temporarily and not stored
- No personal financial data is shared with the AI service

**Permissions Requested:**
- Microphone: "To enable voice input for adding expenses"
- Speech Recognition: "To convert voice to text for expense entries"

