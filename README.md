# 🤖 Swift AI Agent Demo

[![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-18.0+-blue.svg)](https://developer.apple.com/ios/)
[![Xcode](https://img.shields.io/badge/Xcode-16.0+-blue.svg)](https://developer.apple.com/xcode/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> 🚀 **A powerful iOS implementation of the ReAct (Reasoning + Acting) Agent pattern, bringing intelligent AI reasoning directly to your mobile device!**

## 📱 Screenshots

<div align="center">
  <img src="screenshots/1.png" width="250" alt="Agent Interface">
  <img src="screenshots/2.png" width="250" alt="Reasoning Process">
  <img src="screenshots/3.png" width="250" alt="Action Results">
</div>

## ✨ Features

🧠 **Intelligent Reasoning**: Watch the AI agent think through problems step-by-step
🔧 **Dynamic Tool Usage**: File operations, data processing, and more
📱 **Native iOS UI**: Beautiful, responsive interface optimized for mobile
⚡ **Real-time Updates**: Live visualization of the agent's thought process
🔄 **ReAct Pattern**: Implementation of the cutting-edge Reasoning + Acting paradigm
🎯 **User-Friendly**: Clear visual hierarchy showing each step of the reasoning process

## 🏗️ Architecture

This project implements the **ReAct (Reasoning + Acting)** pattern, where the AI agent:

1. **🤔 Thinks** - Analyzes the problem and plans the next step
2. **🎯 Acts** - Uses available tools to gather information or perform actions
3. **👀 Observes** - Processes the results from the action
4. **🔄 Repeats** - Continues until the task is complete

### 📦 Core Components

- **🌐 ChatGPTService**: OpenAI API integration for intelligent responses
- **🤖 AgentService**: Core ReAct logic and tool execution engine
- **🎨 ContentView**: Beautiful UI displaying the reasoning process
- **📱 ContentViewModel**: State management and UI coordination
- **🔧 Tool System**: Extensible tool framework for agent capabilities

## 🚀 Quick Start

### Prerequisites

- 📱 iOS 18.0+ / macOS 14.0+
- 🛠️ Xcode 16.0+
- 🔑 OpenAI API Key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/banghuazhao/swift-ai-agent-demo.git
   cd swift-ai-agent-demo
   ```

2. **Open in Xcode**
   ```bash
   open ReActAgent.xcodeproj
   ```

3. **Configure API Key**
   - Open `ChatGPTService.swift`
   - Replace the API key with your OpenAI API key
   ```swift
   private let apiKey = "your-api-key-here"
   ```

4. **Build and Run** 🏃‍♂️
   - Select your target device/simulator
   - Press `Cmd + R` to build and run

## 🎮 How to Use

1. **📝 Enter Your Query**: Type any question or task in the input field
2. **🚀 Start the Agent**: Tap "Start Agent" to begin the reasoning process
3. **👀 Watch the Magic**: Observe as the agent thinks, acts, and learns
4. **✅ Get Results**: Receive intelligent, step-by-step solutions

### 💡 Example Queries

- "Create a shopping list and save it to a file"
- "Analyze the current weather data"
- "Help me organize my daily tasks"
- "Write a summary of today's activities"

## 🛠️ Available Tools

| Tool | Description | Usage |
|------|-------------|-------|
| 📄 **read_file** | Read contents from files | `read_file("filename.txt")` |
| ✍️ **write_to_file** | Write content to files | `write_to_file("output.txt", "content")` |
| 📅 **get_current_time** | Get current date and time | `get_current_time` |

## 🔧 Technical Details

### 🏛️ Architecture Pattern
- **MVVM**: Clean separation of concerns
- **Observable**: Reactive UI updates
- **Async/Await**: Modern concurrency handling
- **Service Layer**: Modular, testable components

### 🎨 UI Components
- **SwiftUI**: Declarative, modern UI framework
- **Custom Views**: Tailored components for agent visualization
- **Responsive Design**: Optimized for all iOS devices
- **Accessibility**: Full VoiceOver support

### 🔐 Security & Privacy
- **Local Processing**: Agent reasoning happens on-device
- **Secure API**: Encrypted communication with OpenAI
- **No Data Storage**: Conversations are not persisted
- **Privacy First**: Your data stays private

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🍴 Fork** the repository
2. **🌟 Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **💾 Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **🚀 Push** to the branch (`git push origin feature/amazing-feature`)
5. **📥 Open** a Pull Request

### 🐛 Bug Reports

Found a bug? Please create an issue with:
- 📱 Device/iOS version
- 🔍 Steps to reproduce
- 📸 Screenshots (if applicable)
- 📋 Expected vs actual behavior

## 📚 Learn More

### 🔗 Related Resources
- [ReAct Paper](https://arxiv.org/abs/2210.03629) - Original research paper
- [OpenAI API Documentation](https://platform.openai.com/docs) - API reference
- [SwiftUI Documentation](https://developer.apple.com/documentation/swiftui/) - UI framework

### 🎓 Educational Value
This project serves as an excellent learning resource for:
- 🤖 AI Agent development
- 📱 iOS/SwiftUI development
- 🔄 Reactive programming patterns
- 🏗️ Clean architecture principles

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- 🧠 Inspired by the [MarkTechStation](https://github.com/MarkTechStation/VideoCode)
- 🔧 Built with OpenAI's powerful GPT models
- 🎨 Designed with Apple's Human Interface Guidelines
- ❤️ Made with passion for AI and mobile development

## 📞 Contact

**Banghua Zhao** 
- 🐙 GitHub: [@banghuazhao](https://github.com/banghuazhao)
- 📧 LinkedIn: https://www.linkedin.com/in/banghuazhao/

---

<div align="center">
  
**⭐ Star this repository if you found it helpful!**

*Building the future of mobile AI, one agent at a time* 🚀

</div> 