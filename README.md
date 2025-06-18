# 🎓 Bunkers - Smart Attendance Tracker & Bunk Planner

<div align="center">
  <img src="assets/launcher_icon.png" alt="Bunkers Logo" width="120" height="120">
  
  **Your Intelligent Bunk Manager for Academic Success**
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.2.3+-blue.svg)](https://flutter.dev/)
  [![Dart](https://img.shields.io/badge/Dart-3.2.3+-blue.svg)](https://dart.dev/)
  [![License](https://img.shields.io/badge/License-Private-red.svg)](LICENSE)
  [![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com/)
  [![APK](https://img.shields.io/badge/APK-Download-orange.svg)](https://github.com/yourusername/bunkers/releases)
</div>

---

## 📱 Overview

**Bunkers** is a sophisticated Flutter-based mobile application designed to help students manage their academic attendance intelligently. The app combines attendance tracking with strategic bunk planning, ensuring students maintain optimal attendance percentages while maximizing their study efficiency.

### 🎯 Key Features

- **📊 Smart Attendance Tracking** - Monitor attendance percentages across all subjects
- **📅 Intelligent Bunk Planning** - Plan strategic absences with calendar integration
- **🏫 Multi-University Support** - Customized schedules for different universities
- **📋 Timetable Management** - Visual class schedules with location tracking
- **📈 Analytics Dashboard** - Comprehensive attendance insights and trends
- **⚙️ Customizable Settings** - Flexible attendance targets and preferences
- **🔄 Remote Configuration** - Force updates and app control without Play Store
- **🌙 Dark Theme** - Eye-friendly interface for extended use

---

## 📥 Download & Installation

### **Latest Release**
- **Version**: 1.0.0-beta.1
- **File Size**: ~15 MB
- **Minimum Android**: API Level 21 (Android 5.0+)

### **Download Options**

#### **📱 Direct APK Download**
[![Download APK](https://img.shields.io/badge/Download-APK-orange?style=for-the-badge&logo=android)](https://github.com/yourusername/bunkers/releases/latest/download/bunkers.apk)

#### **📦 GitHub Releases**
Visit our [Releases Page](https://github.com/yourusername/bunkers/releases) for:
- Latest stable version
- Previous versions
- Release notes and changelog
- Beta and alpha releases

### **Installation Instructions**

#### **For New Users**
1. **Download APK** - Click the download button above or visit releases page
2. **Enable Unknown Sources** - Go to Settings → Security → Unknown Sources
3. **Install APK** - Open the downloaded file and tap "Install"
4. **Launch App** - Find "Bunkers" in your app drawer and open it

#### **For Updates**
1. **Download New APK** - Get the latest version from releases
2. **Install Over Existing** - The new version will replace the old one
3. **Data Preservation** - Your attendance data will be automatically preserved

#### **Troubleshooting**
- **Installation Blocked**: Enable "Install from Unknown Sources" in settings
- **App Not Found**: Clear launcher cache or restart device
- **Permission Issues**: Grant necessary permissions when prompted
- **Corrupted Download**: Re-download the APK file

---

## 🚀 Features in Detail

### 📚 Subject Management
- Add, edit, and delete subjects with custom names
- Track total lectures vs attended lectures
- Automatic attendance percentage calculation
- Class schedule management with day and time slots
- Location tracking for each class

### 🗓️ Bunk Planner
- Interactive calendar interface for bunk planning
- University-specific scheduling (Indus, GLS, Others)
- Saturday availability based on university selection
- Visual indicators for planned bunks
- Conflict detection and warnings

### 📊 Dashboard Analytics
- Overall attendance percentage overview
- Subject-wise attendance breakdown
- Progress towards target attendance
- Visual charts and statistics
- Quick action buttons for common tasks

### ⏰ Timetable View
- Weekly class schedule display
- Color-coded subjects for easy identification
- Time slot management
- Location information for each class
- Quick navigation between days

### ⚙️ Settings & Configuration
- Customizable target attendance percentage
- University selection with preset schedules
- Data management and backup options
- App preferences and customization
- Remote configuration support

---

## 🏗️ Technical Architecture

### **Frontend Framework**
- **Flutter 3.2.3+** - Cross-platform mobile development
- **Dart 3.2.3+** - Modern programming language
- **Material Design 3** - Latest UI/UX standards

### **State Management**
- **InheritedWidget** - Efficient state propagation
- **Provider Pattern** - Clean architecture implementation
- **SharedPreferences** - Local data persistence

### **Key Dependencies**
- `table_calendar: ^3.0.9` - Calendar functionality
- `shared_preferences: ^2.2.2` - Local storage
- `http: ^1.1.0` - Remote configuration
- `url_launcher: ^6.2.4` - External link handling
- `flutter_svg: ^2.0.7` - SVG asset support
- `intl: ^0.18.1` - Internationalization

### **Data Storage**
- **Local Storage** - Offline-first approach
- **SharedPreferences** - Settings and user data
- **JSON Serialization** - Subject and schedule data
- **No Cloud Dependencies** - Complete privacy

---

## 🎨 User Interface

### **Design Philosophy**
- **Dark Theme** - Reduced eye strain and battery consumption
- **Minimalist Design** - Clean, distraction-free interface
- **Intuitive Navigation** - Bottom navigation with 5 main sections
- **Consistent Branding** - Custom "B" logo and color scheme

### **Color Scheme**
- **Primary Background**: `#050505` (Deep Black)
- **Surface Color**: `#121212` (Dark Grey)
- **Accent Color**: `#2196F3` (Material Blue)
- **Text Colors**: White and light grey variants

### **Navigation Structure**
1. **Subjects** - Subject management and attendance tracking
2. **Bunk Planner** - Calendar-based bunk planning
3. **Dashboard** - Analytics and overview
4. **Timetable** - Weekly schedule view
5. **Settings** - App configuration and preferences

---

## 🔧 Remote Configuration

The app includes a sophisticated remote configuration system that allows:

- **Force Updates** - Compel users to update without Play Store
- **App Shutdown** - Temporarily disable app functionality
- **Dynamic Control** - Real-time app behavior modification
- **Update URLs** - Direct download links for new versions
- **Non-dismissible Dialogs** - Ensure user compliance

### **Configuration Features**
- JSON-based remote configuration
- GitHub-hosted configuration files
- Automatic configuration checks
- Graceful fallback mechanisms
- User-friendly update prompts

---

## 🏫 University Support

### **Supported Universities**
1. **Indus University**
   - 9 time slots (9:00 AM - 4:20 PM)
   - No Saturday classes
   - Specific schedule format

2. **GLS University**
   - 5 time slots (12:30 PM - 4:30 PM)
   - Saturday classes available
   - Custom schedule structure

3. **Other Universities**
   - 8 time slots (9:00 AM - 4:00 PM)
   - Saturday classes available
   - Standard schedule format

### **University-Specific Features**
- Automatic time slot population
- Day availability rules
- Schedule format adaptation
- Location field customization

---

## 📱 Platform Support

### **Current Platform**
- **Android** - Primary target platform
- **API Level 21+** - Wide device compatibility
- **Material Design** - Native Android experience

### **Future Platforms**
- **iOS** - Planned for future releases
- **Web** - Potential web application
- **Desktop** - Windows, macOS, Linux support

---

## 🔒 Privacy & Security

### **Data Privacy**
- **100% Offline** - No internet connection required
- **Local Storage Only** - Data never leaves your device
- **No Analytics** - No tracking or data collection
- **No Cloud Sync** - Complete data ownership

### **Security Features**
- **No Authentication** - Simplified user experience
- **Local Encryption** - Device-level data protection
- **No External APIs** - Reduced attack surface
- **Privacy-First Design** - User data protection by default

---

## 📊 App Statistics

- **Version**: 1.0.0-beta.1
- **Build Number**: 1
- **Target SDK**: 21+
- **Compile SDK**: Latest
- **Dependencies**: 8 core packages
- **Assets**: SVG icons and custom graphics
- **Distribution**: APK via GitHub Releases

---

## 🔄 Update Policy

### **Update Schedule**
- **Stable Releases**: Monthly or as needed
- **Beta Releases**: Weekly for testing
- **Hotfixes**: As soon as critical issues are resolved

### **Update Process**
1. **Automatic Check** - App checks for updates on startup
2. **User Notification** - Non-dismissible update dialog
3. **Direct Download** - Links to latest APK on GitHub
4. **Manual Installation** - User installs new version
5. **Data Preservation** - All user data is maintained

### **Version History**
- **v1.0.0-beta.1** - Initial beta release with core features
- **Future versions** - See [Releases Page](https://github.com/yourusername/bunkers/releases)

---

## 🤝 Contributing

This project distributes APK files via GitHub Releases. We welcome:

- **Feature Requests** - Suggest new functionality via Issues
- **Bug Reports** - Report issues with detailed descriptions
- **UI/UX Feedback** - Design and usability suggestions
- **Testing Feedback** - Help improve app stability

### **How to Contribute**
1. **Test the App** - Download and use the latest APK
2. **Report Issues** - Create detailed bug reports
3. **Suggest Features** - Propose new functionality
4. **Share Feedback** - Provide user experience insights

### **Contact Information**
- **Email**: [Your Email]
- **GitHub**: [Your GitHub Profile]
- **Issues**: [GitHub Issues Page](https://github.com/yourusername/bunkers/issues)
- **Releases**: [GitHub Releases Page](https://github.com/yourusername/bunkers/releases)

---

## 📄 License

This project is **private** and proprietary. All rights reserved.

- **License Type**: Private/Proprietary
- **Source Code**: Not publicly available
- **Distribution**: APK files via GitHub Releases
- **Commercial Use**: Restricted
- **APK Usage**: Free for personal use

---

## 🙏 Acknowledgments

- **Flutter Team** - Amazing cross-platform framework
- **Material Design** - Beautiful UI components
- **Open Source Community** - Dependencies and tools
- **Beta Testers** - Valuable feedback and testing
- **GitHub** - Reliable APK distribution platform

---

## 📈 Roadmap

### **Version 1.1.0** (Planned)
- [ ] iOS support
- [ ] Data export functionality
- [ ] Advanced analytics
- [ ] Custom themes

### **Version 1.2.0** (Future)
- [ ] Web application
- [ ] Cloud sync (optional)
- [ ] Multi-language support
- [ ] Advanced scheduling

### **Version 2.0.0** (Long-term)
- [ ] AI-powered attendance optimization
- [ ] Social features
- [ ] Integration with learning management systems
- [ ] Advanced reporting

---

## ❓ Frequently Asked Questions

### **Installation**
**Q: Why can't I install the APK?**
A: Enable "Install from Unknown Sources" in your Android settings.

**Q: The app doesn't appear in my app drawer?**
A: Try clearing your launcher cache or restarting your device.

### **Usage**
**Q: Is my data safe?**
A: Yes, all data is stored locally on your device and never shared.

**Q: Can I use this offline?**
A: Absolutely! The app works completely offline.

**Q: How do I update the app?**
A: Download the latest APK from GitHub Releases and install it.

### **Features**
**Q: Which universities are supported?**
A: Indus University, GLS University, and a generic option for other universities.

**Q: Can I backup my data?**
A: Currently, data is stored locally. Backup features are planned for future versions.

---

<div align="center">
  
  **Made with ❤️ for Students**
  
  *"Smart attendance management for academic success"*
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.2.3+-blue.svg)](https://flutter.dev/)
  [![Dart](https://img.shields.io/badge/Dart-3.2.3+-blue.svg)](https://dart.dev/)
  [![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com/)
  [![APK](https://img.shields.io/badge/APK-Download-orange.svg)](https://github.com/yourusername/bunkers/releases)
  
</div>
