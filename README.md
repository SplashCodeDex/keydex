![KeyDeX](previews/banner.svg)

# KeyDeX - Advanced Key & Mouse Visualizer

**KeyDeX** is a powerful, open-source keyboard and mouse visualization tool that I built to help content creators, developers, and presenters showcase their keystrokes and mouse actions in real-time. Perfect for tutorials, live coding sessions, presentations, and screencasts.

**English** | [简体中文](./README_zh_CN.md)

## ✨ Features

### ⌨️ Advanced Keystroke Visualization
Display your keystrokes with style! Show individual keys, modifiers, and complex key combinations with smooth animations and customizable appearances.

### 🖱️ Mouse Action Tracking
Visualize mouse clicks, drags, scrolls, and modifier combinations like <kbd>Ctrl</kbd> + <kbd>Click</kbd> or <kbd>Alt</kbd> + <kbd>Drag</kbd> in real-time.

![key-visualizer](previews/visualizer-bar.svg)

### 🎨 Complete Customization
Make it your own with extensive styling options:

- **Colors**: Customize modifier keys, regular keys, backgrounds, and borders
- **Size & Position**: Adjust visualization size and screen position
- **Animations**: Choose from multiple animation presets
- **Icons**: Customizable key icons and visual elements
- **Filters**: Show all keys or filter to display only shortcuts

![settings-window](previews/settings.svg)

### 🚀 Performance Optimized
Built with Flutter for smooth, efficient performance across all platforms with minimal system resource usage.

## 📥 Installation

Download KeyDeX from the [GitHub Releases](https://github.com/SplashCodeDex/keydex/releases) page.

### 🪟 Windows

**System Requirements**: Windows 10 or later, Visual C++ Redistributables

```bash
# Using Winget (recommended)
winget install SplashCodeDex.KeyDeX

# Using Scoop
scoop bucket add extras
scoop install keydex
```

**Note**: If you encounter any `.dll` errors, install [Visual C++ Redistributables](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) from Microsoft.

### 🍎 macOS

**Permission Requirements**:
- Enable **Input Monitoring** in System Settings > Privacy & Security
- Enable **Accessibility** permissions for proper functionality

### 🐧 Linux

**Dependencies**:
```bash
sudo apt-get install libayatana-appindicator3-dev
# or
sudo apt-get install appindicator3-0.1 libappindicator3-dev
```

**Installation**:
```bash
# Debian/Ubuntu
sudo apt install ./keydex.deb

# RPM-based distributions
sudo rpm -i keydex.rpm
```

## 🛠️ Development & Building

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.0.5 or later)
- Git

### Building from Source

```bash
# Clone the repository
git clone https://github.com/SplashCodeDex/keydex.git
cd keydex

# Install dependencies
flutter pub get

# Build for your platform
flutter build windows    # Windows
flutter build macos      # macOS
flutter build linux      # Linux

# Run in development mode
flutter run
```

### Project Structure
- `lib/` - Main Flutter application code
- `assets/` - Icons, fonts, and visual assets
- `linux/`, `macos/`, `windows/` - Platform-specific configurations

## 🤝 Contributing

Contributions are welcome! This project represents my vision for the perfect key visualization tool, but I'm always open to improvements and new ideas.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-enhancement`)
3. Make your changes
4. Test thoroughly across platforms
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

Built with ❤️ using Flutter and Dart. Special thanks to the open-source community for the amazing tools and libraries that made this possible.

---

**Made by [CodeDeX](https://github.com/SplashCodeDex) - Because every keystroke tells a story.**
