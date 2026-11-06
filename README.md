## Universal ai chat! made by simetien123!

A lightweight, standalone Python desktop GUI built with tkinter that serves as a universal chat client for multiple AI providers (free and paid), an unrestricted cybersecurity research assistant (DarkGPT), and an automated multi-file code project generator.

### Key Features:

Multi-Provider Support: Built-in presets for Groq, Google Gemini, OpenRouter, OpenAI, Ollama (Local), and custom OpenAI-compatible endpoints.

Persistent API Key Vault: Saves API keys per provider in an obfuscated local JSON vault (~/.ai_chat_vault.json). Switching presets automatically retrieves and populates the appropriate key.

Cloudflare Bypass (curl_cffi): Uses curl_cffi with Chrome TLS impersonation for network requests, eliminating Cloudflare block issues.

File Attachments: Attach source code (.py, .js, .c, etc.), text, logs, configuration files, and .pdf documents directly to chat sessions for context-aware auditing.

Automatic Privilege & Dependency Management: Automatically requests Windows UAC Administrator rights on launch and installs missing packages (curl_cffi, pypdf) seamlessly in the background.

### Quick Start:

-Prerequisites
-Python 3.8 or higher installed on your system.
-Running the Application
##### Clone or download this repository:
<span style="color: #00ff00;">git clone https://github.com/simetien123/UNIVERSAL-AI-CHAT.git</span>

(The script automatically handles missing dependency installations like curl-cffi on the first run).

### How to Use:
-Select a Provider: Choose your preferred API provider from the Preset Provider dropdown at the top.

-Enter API Key: Paste your API key (e.g., from Groq Console, Google AI Studio, or OpenRouter) and click Connect / Apply API. Your key is automatically saved to the local vault.

### Switch Modes:

-AI Assistant: Standard, helpful AI persona for general queries.

-Attach Files: Use the 📎 Attach File button inside any chat tab to load scripts or PDFs for AI review.

-Security & Privacy Notice

-Local Credentials: API keys are stored locally on your device (~/.ai_chat_vault.json) and are never routed through third-party telemetry servers.

-Local Models: For complete privacy and offline operation, use the Ollama (Local - FREE) preset.

#### This project is open-source and available under the MIT License.
