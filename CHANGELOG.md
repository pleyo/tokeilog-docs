---
layout: default
title: Changelog
description: Version history and updates for TokeiLog
---

# Changelog

All notable changes to TokeiLog will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-06-XX

### Initial Release 🎉

#### Added
- Time entry creation with start and end time pickers
- Calendar view for visualizing logged hours by date
- Main screen displaying all time entries sorted by most recent
- Selection mode for choosing multiple entries
- Share functionality to generate and send time reports
- Edit and delete functionality for time entries
- Support for work shifts that span across midnight
- Dark mode support with automatic theme switching
- Beautiful splash screen with light/dark variants
- Comprehensive time duration calculations and display
- Local data storage (no cloud sync)
- Privacy-first approach with no data collection

#### Features
- **Time Tracking**: Easy-to-use date/time pickers for precise time entry
- **Calendar Integration**: Visual calendar showing marked dates with time entries
- **Time Reports**: Professional-looking reports with total hours calculation
- **Cross-Midnight Support**: Handle shifts that start on one day and end on the next
- **Selection Interface**: Long-press to enter selection mode, tap to select multiple entries
- **Edit Capabilities**: Modify existing entries with the same interface as creation
- **Modern UI**: Clean, native iOS design with proper dark mode support
- **Performance**: Optimized with React.memo and efficient state management
- **Accessibility**: Proper color schemes and readable text in both light and dark modes

#### Technical
- Built with React Native and Expo
- Uses Zustand for state management
- Local storage with AsyncStorage
- Bottom sheet modals for enhanced UX
- Action sheets for contextual actions
- Native calendar component integration
- Reanimated for smooth animations
- Safe area handling for modern iOS devices

### Architecture
- Modular component structure
- Theme-aware color system
- Type-safe TypeScript implementation
- Efficient rendering with memoization
- Clean separation of concerns

---

## Future Releases

### Planned Features (Future Versions)
- Export to CSV functionality
- Backup and restore options
- Recurring time entry templates
- Time tracking statistics and insights
- Widget support for quick time entry
- Apple Watch companion app
- Multiple project support
- Custom categories and tags

---

## Support

For bug reports, feature requests, or support, please contact us through the App Store. 