### Privacy Policy for Chat with Page
 
**Last updated:** April 2026
 
**Chat with Page** is a Chrome extension that allows users to chat with PDF and webpage content using the Anthropic Claude API.
 
#### Data Collection and Usage
 
This extension does **not** collect, store, or transmit any personal data to the extension developer or any third party.
 
The following data is processed **locally on your device only**:
 
- **API Key:** Your Anthropic API key is stored in Chrome's local storage on your device. It is only used to authenticate requests to the Anthropic API (api.anthropic.com) and is never sent anywhere else.
- **Page Content:** When you use the extension, it reads the content of the active browser tab (PDF or webpage) to provide it as context for your conversation. This content is sent to the Anthropic API to generate responses and is handled according to [Anthropic's privacy policy](https://www.anthropic.com/privacy).
- **Chat History:** Conversation sessions are stored in Chrome's local storage on your device. Sessions are automatically cleared when Chrome restarts.
 
#### Third-Party Services
 
This extension sends data to the following third-party service:
 
- **Anthropic API** (api.anthropic.com): Page content and your messages are sent to generate AI responses. Anthropic's usage of this data is governed by their own [privacy policy](https://www.anthropic.com/privacy) and [terms of service](https://www.anthropic.com/terms).
 
#### Permissions
 
- **activeTab / tabs / scripting:** Required to read the content of the current page or PDF you want to chat about.
- **storage / unlimitedStorage:** Required to store your API key and chat sessions locally.
- **host_permissions (all_urls):** Required because PDFs and webpages can be hosted on any domain. The extension only accesses a page when you explicitly activate it.
 
#### Data Retention
 
All data is stored locally and is cleared automatically when Chrome restarts. You can also manually clear data at any time through Chrome's extension storage settings.
