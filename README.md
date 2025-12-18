# Voice Task Manager

<p>
  <img src="https://img.shields.io/badge/6%20Platforms-Android%20%7C%20iOS%20%7C%20Web%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux-0891b2" alt="Platforms">
  <img src="https://img.shields.io/badge/Flutter-3.24+-02569B?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase" alt="Supabase">
  <img src="https://img.shields.io/badge/Gemini%20AI-Voice%20Parsing-4285F4?logo=google" alt="Gemini AI">
  <img src="https://img.shields.io/badge/Tests-418%20Passing-22C55E" alt="Tests">
</p>

<p>
  <b>A voice-powered task management app with AI-driven natural language processing, built with Clean Architecture.</b>
</p>

<p>
  <a href="https://voice-task-manager.pages.dev">🌐 Live Demo</a> •
  <a href="https://github.com/shahinwahab/voice-task-manager/releases/latest/download/voice-task-manager.apk">📥 Download APK</a>
</p>

---

## 📱 App Preview

<!-- CLAUDE: Recommend 3 best screenshots for thumbnail collage (portfolio showcase). -->
<p align="center">
  <a href="https://youtube.com/watch?v=demo">
    <img src="docs/ui/voice-task-manager-thumbnail.webp" alt="Watch Demo" width="600">
  </a>
</p>

## ✨ Features

- Voice-powered task creation with Google Gemini AI
- Smart parsing of title, due date, priority, and category from natural language
- Full CRUD operations with offline support
- Subtasks with progress tracking
- Recurring tasks (daily, weekly, monthly, yearly)
- Calendar view (month/week/day)
- Pomodoro timer with customizable intervals
- Statistics dashboard with completion trends
- Push notifications for reminders
- Export to JSON/CSV
- Dark/Light theme with custom colors
- Biometric authentication
- Home screen widget (Android)

## 🏗️ Architecture

Clean Architecture with BLoC pattern:

```
┌─────────────────────────────────────────────────────────┐
│                    Presentation Layer                   │
│           (Screens, Widgets, BLoC Controllers)          │
├─────────────────────────────────────────────────────────┤
│                      Domain Layer                       │
│          (Entities, Use Cases, Repositories)            │
├─────────────────────────────────────────────────────────┤
│                       Data Layer                        │
│       (Models, Data Sources, Repository Impls)          │
└─────────────────────────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────┐
│                    External Services                    │
│        Supabase Auth │ Supabase DB │ Gemini AI          │
└─────────────────────────────────────────────────────────┘
```

## 👨‍💻 Built by

**Shahin Wahab** - Software Engineer

[![Portfolio](https://img.shields.io/badge/Portfolio-shahinwahab.com-0891b2?style=for-the-badge)](https://shahinwahab.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/shahinwahab)

---
> **Repository created on:** 2025-12-16, 20:16 (UTC+3)
