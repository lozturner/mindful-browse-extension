# 🌟 Mindful Browse Extension

> **A Supportive Approach to Digital Wellbeing**

[![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?logo=google-chrome&logoColor=white)](https://github.com/lozturner/mindful-browse-extension)
[![Edge Compatible](https://img.shields.io/badge/Edge-Compatible-0078D7?logo=microsoft-edge&logoColor=white)](https://github.com/lozturner/mindful-browse-extension)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 💡 What Makes This Different?

Instead of **blocking** or **shaming** you when visiting distracting sites like YouTube, Mindful Browse takes a compassionate, supportive approach:

- 🧘 **Gentle Awareness** - Mindful prompts about your time and intentions
- 🤖 **AI Conversation Partner** - Chat with multiple AI models for support
- ✅ **Your Choice** - Customizable site lists, you're in control
- 💬 **Supportive Dialogue** - Productive conversations instead of guilt
- ⚡ **Zero-Shot Deployable** - Works immediately after installation

## 🎯 The Philosophy

This project is built on the belief that **shame and restriction don't work** for behavior change. Instead, we offer:

- 💚 Self-awareness without judgment
- 🤝 Supportive AI conversations
- 🎯 Goal-oriented redirection
- 📊 Progress tracking (not time-wasting shaming)

## ✨ Features

### 🛡️ Core Intervention System
- URL detection for distracting sites (YouTube, social media, etc.)
- Non-blocking popup overlay with supportive messaging
- Customizable intervention frequency
- Site whitelist/blacklist management

### 🤖 AI Integration
Chat with multiple AI models for productivity support:
- **Google Gemini** - Advanced reasoning and code assistance
- **OpenAI GPT** - Conversational support and ideation
- **Claude** - Long-context understanding and analysis

### 🎨 User Experience
- Clean, modern, professional UI
- Shadow DOM injection (no style conflicts)
- Fully accessible keyboard navigation
- Privacy-first design (API keys stored locally)

## 🛠️ Technical Architecture

### Built With:
- **Manifest V3** - Latest Chrome extension standard
- **Service Workers** - Efficient background monitoring
- **Shadow DOM** - Isolated styling
- **Secure API Integration** - Multiple AI providers

### File Structure:
```
mindful-browse-extension/
├── manifest.json          # Extension configuration
├── background.js          # Service worker for URL monitoring
├── content.js             # Popup injection logic
├── popup.html             # Intervention UI
├── popup.css              # Supportive styling
├── popup.js               # AI integration handler
├── options.html           # Settings page
├── options.js             # Settings logic
└── icons/                 # Extension icons
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

## 🚀 Installation

### Option 1: From Source (Recommended for Development)
```bash
# Clone the repository
git clone https://github.com/lozturner/mindful-browse-extension.git
cd mindful-browse-extension

# Load in Chrome/Edge
# 1. Navigate to chrome://extensions/
# 2. Enable "Developer mode"
# 3. Click "Load unpacked"
# 4. Select the extension directory
```

### Option 2: Manual Installation
1. Download the [latest release](https://github.com/lozturner/mindful-browse-extension/releases)
2. Extract the ZIP file
3. Follow the steps above to load the unpacked extension

## ⚙️ Configuration

1. Click the extension icon and select **Options**
2. Add your API keys (stored securely in local storage):
   - Gemini API Key (from [Google AI Studio](https://aistudio.google.com/apikey))
   - OpenAI API Key (from [OpenAI Platform](https://platform.openai.com/api-keys))
   - Claude API Key (from [Anthropic Console](https://console.anthropic.com/))
3. Customize your site lists
4. Set intervention preferences

## 📚 Development Process

This project was created through a unique **collaborative AI development process**, querying multiple AI models simultaneously for diverse perspectives:

### 🤖 AI Collaborators

1. **🟢 Google Colab** - Initial project scaffolding
   - [View Notebook](YOUR_COLAB_LINK_HERE)

2. **🔵 Google AI Studio** - Manifest V3 architecture
   - [View Chat](PLACEHOLDER_AI_STUDIO_LINK)

3. **🟠 ChatGPT** - Complete extension code generation
   - [View Conversation](PLACEHOLDER_CHATGPT_LINK)

4. **🔵 Gemini Pro Mode** - Advanced code generation
   - [View Chat](https://gemini.google.com/app/778bc151ea72be76)

5. **🟼 Perplexity AI** - Technical architecture guidance
   - [View Search](https://www.perplexity.ai/search/i-m-going-to-make-a-new-really-oHXhq.CXTeC6PWvpd7rgAw)

6. **🤖 Manus AI** - Full project structure automation
   - [View Task](https://manus.im/app/BivppT6ml99LK212pcvOHd)

### 🎨 Development Philosophy

By consulting multiple AI models, we achieved:
- 🎯 **Diverse perspectives** on UX design
- 🛡️ **Best practices** for security and privacy
- ⚡ **Optimized code** from different approaches
- 💡 **Creative solutions** to technical challenges

## 📝 Code Examples

All complete code is available in the repository. Key highlights:

- **Manifest V3 Configuration** with service worker
- **Shadow DOM Injection** for style isolation
- **Multi-AI Provider Integration** with fallback handling
- **Secure API Key Storage** using chrome.storage
- **URL Pattern Matching** for site detection

## 🔒 Security & Privacy

- 🔐 API keys stored **locally only** (chrome.storage.local)
- 🚫 No data collection or analytics
- 🔒 All AI conversations are **direct** (no proxy)
- 👁️ Minimal permissions requested
- ✅ Open source - audit the code yourself

## 🤝 Contributing

We welcome contributions! This project is about supporting people, not restricting them.

Areas for improvement:
- Additional AI model integrations
- Enhanced UX/UI designs
- Localization/internationalization
- Mobile browser support
- Advanced analytics (privacy-preserving)

## 💬 Philosophy & Approach

Read our [Design Philosophy](PHILOSOPHY.md) document to understand:
- Why shame-based blocking fails
- The psychology of supportive interventions
- How AI can be a productivity partner
- Evidence-based behavior change strategies

## 💖 Acknowledgments

This project wouldn't exist without:
- The amazing teams at Google, OpenAI, Anthropic, and Perplexity
- The open-source community
- Everyone who believes in compassionate technology

## 📧 Contact

Created by [@lozturner](https://github.com/lozturner)

Questions? Ideas? Open an [issue](https://github.com/lozturner/mindful-browse-extension/issues) or start a [discussion](https://github.com/lozturner/mindful-browse-extension/discussions)!

## 📜 License

MIT License - feel free to use, modify, and distribute!

---

<div align="center">

---

# 💻 VERSION 2: Windows Desktop Application

> **NEW!** Standalone desktop app for Windows 10/11 - No browser required!

## 🆕 What's New in V2?

Version 2 takes Mindful Browse beyond the browser with a **system-level productivity companion**:

- 📍 **System Tray App** - Runs quietly in background
- 👁️ **Window Monitoring** - Tracks ANY application (YouTube, social media apps, games)
- 🔔 **Windows Notifications** - Native toast notifications
- 💬 **AI Chat Window** - PyQt6 interface for conversations
- ⚙️ **Fully Customizable** - config.yaml for your workflow
- 🚀 **Auto-start** - Launch with Windows
- 🧱 **Minimal Resources** - ~20MB RAM, <1% CPU

## 📦 Desktop App Features

### 📊 Core Monitoring
- Monitors active window titles using Win32 API
- Detects distracting apps across ALL windows:
  - Browser: YouTube, Twitter, Reddit, etc.
  - Desktop Apps: Steam, Discord, games
  - Custom keywords you define

### 🔔 Smart Notifications
- Windows 10/11 native toast notifications
- Cooldown system (10min default) prevents spam
- Click notification to open AI chat

### 🤖 AI Integration
- Same multi-model support (Gemini, OpenAI, Claude)
- Professional PyQt6 chat interface
- Always-on-top option for focus
- Conversation history

## 🛐️ Technical Stack

```
Python 3.10+
├── pywin32          # Windows API access
├── pystray          # System tray integration
├── PyQt6            # Modern UI framework
├── win11toast       # Native notifications
├── PyYAML           # Configuration
└── PyInstaller      # .exe packaging
```

## 📝 File Structure

```
desktop-app/
├── main.py                  # Entry point & system tray
├── window_monitor.py        # Active window detection
├── notification_system.py   # Toast notifications
├── ai_chat_window.py        # PyQt6 chat UI
├── ai_service.py            # Multi-AI provider handler
├── config.yaml              # User settings
├── requirements.txt         # Python dependencies
├── build_exe.py             # PyInstaller configuration
├── icons/
│   └── tray_icon.ico
└── README_DESKTOP.md        # Desktop-specific docs
```

## 🚀 Installation (Desktop Version)

### Option 1: Download .exe (Coming Soon)
```bash
# Download from releases
# Run MindfulBrowse.exe
# Configure in system tray
```

### Option 2: From Source
```bash
# Clone repository
git clone https://github.com/lozturner/mindful-browse-extension.git
cd mindful-browse-extension/desktop-app

# Install dependencies
pip install -r requirements.txt

# Run app
python main.py
```

### Option 3: Build Your Own .exe
```bash
python build_exe.py
# Executable will be in dist/ folder
```

## ⚙️ Configuration

Edit `config.yaml` to customize:

```yaml
app_settings:
  check_interval_seconds: 5
  notification_cooldown_minutes: 10
  autostart: true

distractions:
  keywords:
    - "YouTube"
    - "Netflix"
    - "Facebook"
    - "Twitter"
    - "Reddit"
    - "Instagram"
    - "Steam"
    - "Discord"
    # Add your own!

ai_config:
  provider: "openai"  # or "gemini" or "claude"
  api_key: "YOUR_API_KEY_HERE"
  system_prompt: "You are a supportive productivity coach."
```

## 🔄 Version Comparison

| Feature | Version 1 (Browser) | Version 2 (Desktop) |
|---------|-------------------|--------------------|
| **Platform** | Chrome/Edge Extension | Windows App |
| **Monitoring** | Browser tabs only | All applications |
| **Installation** | Load unpacked | .exe installer |
| **Resources** | Per-tab | ~20MB total |
| **Scope** | Web browsing | System-wide |
| **Auto-start** | With browser | With Windows |

## 🔗 AI Development Process (V2)

Version 2 was also created through **collaborative AI development**:

### 🤖 AI Contributors (Version 2):

1. **🟢 Google AI Studio** - Complete Python desktop architecture
   - [View V2 Chat](https://aistudio.google.com/prompts/1et2dLzyxsQv9ytOJ4XOvUY8M8IlC06Ii)

2. **🔵 Gemini Pro Mode** - Advanced PyQt6 implementation  
   - [View V2 Chat](https://gemini.google.com/app/778bc151ea72be76)

3. **🟼 Perplexity AI** - Windows API best practices
   - [View V2 Research](https://www.perplexity.ai/search/i-m-going-to-make-a-new-really-oHXhq.CXTeC6PWvpd7rgAw)

## 📚 Learn More

- [Desktop App Documentation](./desktop-app/README_DESKTOP.md)
- [Complete Source Code](./desktop-app/)
- [Building from Source Guide](./desktop-app/BUILD.md)

## 🔐 Security Notes (Desktop Version)

- Runs with standard user permissions (no admin required)
- API keys stored in local config.yaml (never transmitted except to AI providers)
- Window title monitoring only (no screenshots or keylogging)
- Open source - audit the code yourself
- No telemetry or data collection

## 🤝 Which Version Should I Use?

**Choose Version 1 (Browser Extension) if:**
- You only need browser intervention
- You want zero installation hassle
- You use multiple browsers

**Choose Version 2 (Desktop App) if:**
- You want system-wide monitoring
- You use desktop apps (Steam, Discord, etc.)
- You want one tool for everything
- You're on Windows 10/11

**Use Both!** They complement each other perfectly! 🚀

---

## 💬 Version History

### Version 2.0 (January 2026)
- ✨ Windows desktop application
- System-wide window monitoring
- Native Windows notifications  
- PyQt6 chat interface
- PyInstaller packaging

### Version 1.0 (January 2026)
- 🎉 Initial browser extension release
- Chrome/Edge Manifest V3
- Multi-AI provider support
- Supportive intervention UI

**Built with 💚 by humans and AI, for humans**

*Because productivity isn't about restriction—it's about support*

[⭐ Star this repo](https://github.com/lozturner/mindful-browse-extension) if you believe in compassionate technology!

</div>
