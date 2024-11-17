# 💻 MacMate

<div align="center">
    <img src="https://github.com/pathaksomesh06/MacMate/blob/main/Screenshots/MacMate_landing.png" alt="MacMate" width="200"/>
    <h3>A MDM Agnostic Self Service Agent for macOS</h3>

[![Swift](https://img.shields.io/badge/Swift-5.5-orange.svg)](https://swift.org)
[![Platform](https://img.shields.io/badge/Platform-macOS-blue.svg)](https://www.apple.com/macos)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
</div>

## 🚀 About

MacMate is a powerful and user-friendly system management tool for macOS, designed to provide essential system information and administrative capabilities regardless of your MDM solution. Whether your Mac is managed by Intune, Jamf, or not managed at all, MacMate offers a comprehensive suite of tools for both standard users and administrators.

## ✨ Features

### 🖥️ System Information
- 📊 Detailed system information display
- 🔄 Real-time hardware status monitoring
- 🔋 Battery status and health information
- 💾 Storage usage analytics
- 🌐 Network configuration details

### 🛡️ MDM Integration
- 🔍 Automatic detection of MDM enrollment status (Intune/Jamf)
- 🎯 MDM-specific features and information
- 📱 Profile management interface
- ✅ Enrollment status checking

### 🔒 Security Features
- 👤 Secure admin rights management
  - ⏱️ Time-boxed elevation to admin rights (30 minutes) (Feature to be released)
  - 🛑 Safe admin rights removal with system protection
  - 👥 Multiple admin verification for safety
- 🔐 Platform SSO status checking
- 🛡️ Security settings monitoring
- ✅ System integrity verification

### 👥 User Management
- 📝 User account information
- ⬆️ Admin rights elevation with safety checks
- ⏳ Temporary admin privileges with automatic expiration (Feature to be released)
- 🔑 User permission management

### 📦 Software Management
- 📱 Installed applications inventory
- 🔄 Software update checks
- 🎯 Application management capabilities
- 📋 System and application logs access

### 🛠️ System Tools
- 🌐 Network configuration management
- ♿ Accessibility settings
- 🔧 Self-service troubleshooting tools
- 📊 System report generation

### 🌍 Remote Management
- 🔗 Remote support integration
- 📱 Device management capabilities
- ⚙️ Remote configuration options
- 📊 Management status monitoring

## 💻 Requirements

- 🖥️ macOS 13.0 (Ventura) or later
- 🔑 Admin rights for certain features
- 🌐 Internet connection for updates

## 📥 Installation

1. ⬇️ Download the latest release from the [Releases](https://github.com/yourusername/MacMate/releases) page
2. 📁 Move MacMate.app to your Applications folder
3. 🚀 Launch MacMate
4. ✅ Grant necessary permissions when prompted

## 🔒 Security

MacMate takes security seriously:
- 🔐 All admin operations require authentication
- ✅ Multiple admin verification for critical operations
- ⏱️ Automatic privilege expiration
- 🛡️ Safe admin rights management
- ⚠️ No permanent system modifications without confirmation


## 📸 Screenshots

<div align="center">
    <img src="https://github.com/pathaksomesh06/MacMate/blob/main/Screenshots/MDM_detection_intune_managed.png" alt="MDM Detection" width="400"/>
    <img src="https://github.com/pathaksomesh06/MacMate/blob/main/Screenshots/Reports_jamf_managed.png.png" alt="Automatic detection of MDM enrollment status" width="400"/>
</div>

## 🛠️ Built With

- 📱 SwiftUI - Modern UI framework for macOS
- 🔵 Swift - Primary programming language
- 🖥️ macOS APIs - Core system integration

## ✍️ Authors

- **Somesh Pathak** - *Initial work* - [pathaksomesh06](https://github.com/pathaksomesh06)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- 🌟 Special thanks to the MacAdmins community
- 💡 Inspired by the need for better cross-MDM management tools

## 💬 Support

For support, please open an issue in the GitHub repository.

## 🗺️ Roadmap

- [ ] Additional MDM integrations
- [ ] Enhanced security features
- [ ] More self-service capabilities
- [ ] Improved reporting features
- [ ] Advanced user management

## 🔑 Key Features Breakdown

### Admin Rights Management
```
📊 Time-based Admin Elevation (Feature to be released)
├── ⏱️ 30-minute temporary elevation (Feature to be released)
├── 🔄 Automatic expiration
├── ⚠️ Safety checks
└── 📝 Activity logging
```

### MDM Integration
```
🛡️ MDM Support
├── 📱 Intune Management
├── 🔷 Jamf Management
├── 🔍 Auto-detection
└── 📊 Status reporting
```

### System Tools
```
🛠️ Utilities
├── 📊 System Reports
├── 🔍 Diagnostics
├── 🔧 Troubleshooting
└── 📱 App Management
