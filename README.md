# 📋 Daily Habits Tracker

A beautiful, multilingual daily habit tracking app that helps you build and maintain healthy routines. Track your daily goals, see your progress, and stay motivated with a clean, modern interface.

![App Preview](https://img.shields.io/badge/Status-Ready%20to%20Use-brightgreen) ![Languages](https://img.shields.io/badge/Languages-6%20Supported-blue) ![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-orange)

## ✨ Features

### 🎯 **Core Functionality**
- ✅ **Daily Habit Tracking** - Check off completed habits with satisfying animations
- 🔄 **Auto Reset** - Habits automatically reset every day at midnight
- 📊 **Progress Visualization** - Beautiful progress bar shows daily completion
- 💾 **Persistent Storage** - Never lose your data, everything is saved locally

### 🌍 **Multi-Language Support**
- 🇵🇹 Português (Portuguese)
- 🇺🇸 English
- 🇪🇸 Español (Spanish)
- 🇫🇷 Français (French)
- 🇩🇪 Deutsch (German)
- 🇷🇺 Русский (Russian)

### ⚙️ **Customization**
- 👤 **Personal Greeting** - Set how the app addresses you
- 📝 **Custom Habits** - Add, edit, or remove habits as needed
- 🎨 **Clean UI** - Modern, responsive design that works on any device
- 🌙 **Mobile Optimized** - Perfect for phone screens and touch interaction

## 🚀 Getting Started

### Option 1: Direct Use (Recommended)
1. Save the HTML file to your device
2. Open it in any modern web browser
3. Add to home screen for app-like experience (mobile)
4. Start tracking your habits!

### Option 2: Convert to Native Android App

#### Using Cordova/PhoneGap
```bash
# Install Cordova
npm install -g cordova

# Create new project
cordova create HabitTracker com.yourname.habittracker "Daily Habits Tracker"

# Add Android platform
cd HabitTracker
cordova platform add android

# Copy the HTML file to www/index.html
# Build the APK
cordova build android
```

#### Using Capacitor
```bash
# Install Capacitor
npm install -g @capacitor/cli @capacitor/core

# Initialize project
npx cap init "Daily Habits Tracker" "com.yourname.habittracker"

# Add Android platform
npx cap add android

# Copy HTML file to src/index.html
# Build and sync
npx cap build
npx cap sync android
npx cap open android
```

#### Using PWA (Progressive Web App)
1. Open the app in Chrome/Edge on Android
2. Tap the menu (⋮) → "Add to Home screen"
3. The app will behave like a native app

## 📱 How to Use

### First Time Setup
1. **Open Settings** - Tap the ⚙️ button
2. **Set Your Name** - Choose how the app greets you
3. **Select Language** - Pick from 6 available languages
4. **Customize Habits** - Add your personal daily goals

### Daily Usage
1. **Check Off Habits** - Tap the circle to mark habits complete
2. **Watch Progress** - See your completion percentage grow
3. **Stay Motivated** - Enjoy the visual feedback and animations

### Managing Habits
- **Add New Habit**: Settings → "+" button → Enter habit name
- **Edit Habit**: Settings → Change text in habit field
- **Remove Habit**: Settings → Tap 🗑️ next to habit
- **Reorder**: Currently manual (future feature)

## 🎨 Default Habits by Language

| Language | Default Habits |
|----------|----------------|
| 🇵🇹 Português | Estudar Russo, Exercício físico, Aprender Algo |
| 🇺🇸 English | Study Russian, Physical Exercise, Learn Something |
| 🇪🇸 Español | Estudiar Ruso, Ejercicio Físico, Aprender Algo |
| 🇫🇷 Français | Étudier le Russe, Exercice Physique, Apprendre Quelque Chose |
| 🇩🇪 Deutsch | Russisch Lernen, Körperliche Übung, Etwas Lernen |
| 🇷🇺 Русский | Изучать Русский, Физические Упражнения, Изучать Что-то |

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Structure and content
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - Core functionality and interactivity
- **LocalStorage API** - Data persistence
- **Responsive Design** - Mobile-first approach

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Data Storage
- All data stored locally in browser's localStorage
- No external dependencies or internet required
- Data persists across browser sessions
- Automatic daily reset functionality

## 📂 Project Structure

```
daily-habits-tracker/
├── index.html              # Main app file (single file app)
├── README.md              # This file
└── screenshots/           # App screenshots (optional)
    ├── main-screen.png
    ├── settings-modal.png
    └── mobile-view.png
```

## 🎯 Roadmap

### Planned Features
- [ ] **Habit Streaks** - Track consecutive days
- [ ] **Statistics** - Weekly/monthly completion charts
- [ ] **Themes** - Dark mode and custom colors
- [ ] **Backup/Restore** - Import/export settings
- [ ] **Habit Categories** - Group related habits
- [ ] **Notifications** - Daily reminders (PWA)
- [ ] **Habit Templates** - Pre-made habit collections

### Version History
- **v1.0** - Basic habit tracking
- **v1.1** - Added persistent storage
- **v1.2** - Multi-language support (current)

## 🤝 Contributing

Want to improve the app? Here's how you can help:

1. **Report Bugs** - Open an issue with details
2. **Suggest Features** - Share your ideas
3. **Add Languages** - Contribute translations
4. **Improve Design** - CSS/UI enhancements
5. **Code Improvements** - Performance optimizations

### Adding a New Language
1. Add translation object to `translations` in the code
2. Add option to language selector
3. Include default habits for that language
4. Test all interface elements

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💡 Tips for Success

### Building Better Habits
- **Start Small** - Begin with 1-3 habits
- **Be Specific** - "Exercise 20 minutes" vs "Exercise"
- **Stack Habits** - Link new habits to existing routines
- **Track Consistently** - Check the app daily
- **Celebrate Progress** - Acknowledge your wins!

### App Usage Tips
- **Add to Home Screen** - For easy daily access
- **Set Phone Reminder** - Daily notification to check habits
- **Review Weekly** - Adjust habits that aren't working
- **Keep It Simple** - Don't overwhelm yourself with too many habits

## 📞 Support

Need help or have questions?
- Check the [Issues](https://github.com/J0ny01/habit-tracker/issues) page
- Create a new issue for bugs or feature requests
- For general questions, use the Discussions tab

---

**Made with ❤️ for building better daily habits**

*Remember: Progress, not perfection. Every day is a new opportunity to grow!*