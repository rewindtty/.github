# rewindtty

<p align="center">
  <picture>
    <img style="max-width:400px;height:auto" src="https://www.rewindtty.dev/assets/logo-black.png" alt="rewindtty logo">
  </picture>
</p>

**Terminal session recording and replay tools for developers**

---

## 🎯 About

rewindtty is an open-source organization focused on building powerful terminal session recording, analysis, and replay tools. Our mission is to help developers capture, analyze, and share their terminal workflows with precision timing and comprehensive insights.

## 🚀 Featured Projects

### [rewindtty](https://github.com/rewindtty/rewindtty)
A lightweight terminal session recorder and replayer written in C that captures and replays terminal sessions with precise timing.

**Key Features:**
- 📹 Record terminal sessions with accurate timing
- ▶️ Replay sessions with original timing
- 📊 Session analysis with detailed statistics
- 🌐 JSON format for easy integration
- 🔧 Minimal dependencies, pure C implementation

### [browser_player](https://github.com/rewindtty/browser_player)
An advanced web-based player with enhanced features and a modern interface for viewing terminal sessions in your browser.

**Try it live:** [play.rewindtty.dev](https://play.rewindtty.dev)

## 🛠️ Technology Stack

- **Core Engine:** C (GNU99 standard)
- **Data Format:** JSON with precise timing information
- **Web Player:** Modern web technologies
- **Build System:** GNU Make
- **Dependencies:** Minimal (cJSON for JSON parsing)

## 📈 Use Cases

- **Development Workflows:** Record and share complex terminal sessions
- **Educational Content:** Create tutorials and demonstrations
- **Debugging:** Capture and analyze problematic command sequences
- **Performance Analysis:** Identify slow commands and optimization opportunities
- **Documentation:** Generate interactive terminal examples

## 🎮 Quick Start

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/rewindtty/rewindtty.git

# Build
make

# Record a session
./build/rewindtty record

# Replay the session
./build/rewindtty replay

# Analyze session statistics
./build/rewindtty analyze
```

## 🌟 Why rewindtty?

- **Precision:** Captures exact timing information for authentic replay
- **Lightweight:** Minimal resource usage and dependencies
- **Versatile:** Works with any terminal application
- **Standards-Based:** Uses standard POSIX system calls
- **Cross-Platform:** Compatible with modern Unix-like systems
- **Developer-Friendly:** JSON format enables easy integration

## 🤝 Contributing

We welcome contributions from the community! Whether you're interested in:

- 🐛 Reporting bugs
- 💡 Suggesting features
- 🔧 Contributing code
- 📚 Improving documentation
- 🎨 Enhancing the web player

Check out our [Contributing Guidelines](https://github.com/rewindtty/rewindtty/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/rewindtty/rewindtty/blob/main/CODE_OF_CONDUCT.md).

## 📜 License

All rewindtty projects are released under the MIT License, promoting open collaboration and reuse.

## 🔗 Links

- **Website:** [rewindtty.dev](https://rewindtty.dev)
- **Web Player:** [play.rewindtty.dev](https://play.rewindtty.dev)
- **Main Repository:** [github.com/rewindtty/rewindtty](https://github.com/rewindtty/rewindtty)
- **Browser Player:** [github.com/rewindtty/browser_player](https://github.com/rewindtty/browser_player)

---

<p align="center">
  <strong>Built with ❤️ for the developer community</strong>
</p>
