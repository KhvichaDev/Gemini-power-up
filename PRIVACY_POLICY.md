# Privacy Policy for Power-Up for Gemini

**Last Updated:** September 6, 2026  
**Effective Date:** September 6, 2026

Thank you for choosing **Power-Up for Gemini** ("the Extension", "we", "us", or "our"). We are committed to protecting your personal information and your right to privacy. This Privacy Policy explains how your data is collected, handled, stored, used, and shared when you use our Chrome Extension.

Please read this policy carefully. If you have any questions or concerns about this privacy policy, you can contact us at the contact details provided at the bottom of this page.

---

## 1. Summary (Privacy by Design)
- **Zero Remote Data Collection:** We do not collect, monitor, track, store, or sell any personal data, browsing history, or conversation content to any external or developer-owned servers.
- **100% Local Storage:** All user configuration, custom prompts, task manager items, notes, project files, and debate history are stored strictly locally on your own device via `chrome.storage.local` and local browser storage.
- **Direct Endpoints Only:** Any third-party integrations (such as direct connections to Gemini, Telegram Bot, WordPress, GitHub Enterprise, or DeepL) communicate directly from your browser to the designated endpoint with no intermediary server or analytics proxy.

---

## 2. Information We Handle and Collect

The Extension operates purely as a client-side productivity tool. We do not maintain any central servers or databases.

### A. Information Handled Locally on Your Device
- **User Preferences & Settings:** Interface configurations, theme selections, active feature toggles, shortcuts, and custom layout settings.
- **Prompts, Notes & Tasks:** User-created prompt libraries, task manager items, reminders, conversation bookmarks, and local note archives.
- **Local Project Files & Code:** Code snippets, scripts, and local project artifacts managed within the Project Manager.
- **API Keys and Authentication Tokens (Optional):** If you choose to configure optional third-party integrations (e.g., Telegram Bot Token, DeepL API Key, GitHub Token, WordPress Application Passwords), these tokens are stored exclusively in your browser's local encrypted/isolated storage (`chrome.storage.local`).

### B. Information We DO NOT Collect
- We **do not** collect personal identification details (names, email addresses, phone numbers, IP addresses, physical locations).
- We **do not** monitor or collect your browsing history or data on web pages outside of explicitly supported host domains (`gemini.google.com`, `notebooklm.google.com`).
- We **do not** collect, store, or read your Gemini conversation text for analytical, commercial, or profiling purposes.
- We **do not** use analytics trackers, telemetry packages, third-party advertising SDKs, or session-recording tools (e.g., Google Analytics, Mixpanel, Hotjar).

---

## 3. How We Use and Handle Your Data

The Extension handles data solely to deliver the core functionalities requested by you:
- **Feature Customization:** Loading your saved preferences, custom UI styles, and feature states.
- **Local Task & Schedule Alerts:** Triggering local browser notifications for reminders, deadlines, and schedule alerts configured by you.
- **Workflow Automation:** Populating your custom prompts into Gemini or NotebookLM upon your direct click or shortcut activation.
- **Image & Code Export:** Copying formatted code blocks, conversation exports, or canvas edits to your local clipboard upon your request.
- **User-Initiated Integrations:** Transmitting data directly between your browser and your configured target service (e.g., publishing a note directly to your personal WordPress site or sending a notification to your own Telegram chat) when triggered by you.

---

## 4. Data Storage, Retention, and Security

### Where Is Data Stored?
All persistent extension data is stored strictly within your browser's local storage sandbox using Google Chrome's standard `chrome.storage.local` and client-side database APIs.

### Data Retention
- Data remains stored locally on your device for as long as the Extension is installed or until you choose to delete it.
- Session-based temporary data (such as temporary debate storage) is automatically cleared when the session or browser window is closed, depending on your selected privacy settings.

### How to Delete Your Data
You have complete control over your data at all times:
- **In-Extension Clear:** You can clear prompts, history, notes, or reset settings to default at any time via the Extension's Settings panel.
- **Chrome Storage Clear:** You can clear extension data at any time via Chrome's Settings (`chrome://settings/clearBrowserData`).
- **Uninstalling the Extension:** Removing/uninstalling the Extension immediately deletes all associated local data and storage from your computer.

### Security
Because no data is transferred to external developer servers, the security of your stored data relies on the robust sandboxing and security features built into the Google Chrome browser and your operating system.

---

## 5. Third-Party Sharing and Disclosure

We have a strict **No Data Sharing / No Sale of Data** policy:
- **No Sale or Commercial Transfer:** We never sell, rent, monetize, trade, or transfer your data to data brokers, advertisers, or third-party marketing firms.
- **No Third-Party Intermediaries:** When using external integrations (e.g., Gemini, Telegram, GitHub, WordPress), network requests originate directly from your local browser client to the destination API. No traffic or payloads pass through any developer proxy or relay server.
- **No Tracking Across the Web:** We do not track user activity across different websites or services.

---

## 6. Permissions and Justifications

The Extension requests specific Chrome permissions strictly to enable user-facing capabilities:
- `storage` & `unlimitedStorage`: To store user settings, prompt libraries, and project archives locally on your device.
- `notifications`: To display local alerts for scheduled tasks and reminders configured by the user.
- `alarms`: To trigger periodic local background checks and scheduled task timers.
- `scripting`: To inject productivity overlays, toolbars, and features into `gemini.google.com` and `notebooklm.google.com`.
- `clipboardWrite`: To allow one-click copying of code, images, and formatted exports to your clipboard.
- `host_permissions` (`*://*/*`): Required exclusively for direct user-configured integrations (e.g., custom self-hosted WordPress endpoints, GitHub Enterprise, direct CDN asset handling). No tracking is performed.

---

## 7. Children's Privacy
The Extension does not knowingly collect or solicit any personal information from children under the age of 13 (or under the applicable age of consent in your jurisdiction). Since no personal data is collected from any user, no children's data is gathered or processed.

---

## 8. Changes to This Privacy Policy
We may periodically update this Privacy Policy to reflect changes in our features, practices, or regulatory requirements. When updated, the "Last Updated" date at the top of this document will be revised. Any changes will become effective immediately upon posting.

---

## 9. Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy or your privacy while using **Power-Up for Gemini**, please contact:

- **Developer:** KhvichaDev
- **Email:** contact@khvichadev.com
- **GitHub Repository:** https://github.com/KhvichaDev/Gemini-Power-Up
- **GitHub Issues:** https://github.com/KhvichaDev/Gemini-Power-Up/issues
