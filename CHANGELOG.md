# Changelog

All notable changes to Google URL Scraper will be documented in this file.

**Powered by SAYDI**

---

## [3.0.7] - 2026-05-07

### 🎨 UI/UX Improvements
- White background for "Scraping in progress" notification
- Bold black text for all notifications (maximum readability)
- Improved text contrast on all notification types
- Extra bold title (weight 900) and bold message (weight 700)

### 🔧 Fixed
- Notification text visibility on all background colors
- Progress notification now uses white background with black text
- All notification types have proper text contrast

---

## [3.0.6] - 2026-05-07

### 🎨 UI Changes
- All notification text changed to pure black (#000000)
- Consistent text color across all notification types

---

## [3.0.5] - 2026-05-07

### 🎨 UI Changes
- Notification title and message text set to black
- Removed text shadows for cleaner look

---

## [3.0.4] - 2026-05-07

### 🎨 UI Improvements
- Purple notification with white text and shadow
- Improved text visibility on dark purple background
- Added text shadow for better readability

---

## [3.0.3] - 2026-05-07

### 🎨 UI Improvements
- Improved notification text readability
- Dark text on light backgrounds (yellow, red, green)
- Light text on dark backgrounds (purple)
- WCAG AA compliant contrast ratios

---

## [3.0.2] - 2026-05-07

### 🔧 Fixed
- Notification color changed from blue to purple
- Fixed inline style override issue in JavaScript

---

## [3.0.1] - 2026-05-07

### 🔧 Fixed
- Version bump to force Chrome reload

---

## [3.0.0] - 2026-05-06

### 🎨 Major UI/UX Redesign - Glassmorphism
- Modern glassmorphism design with dark theme
- Glass cards with backdrop blur effects
- Compact 340px width for better screen usage
- 3-column stats grid with icons
- Smooth animations (0.15s transitions)
- Pure CSS (no external dependencies)

### 🎯 Button Improvements
- Both scraping buttons now have same green gradient design
- Stop button with red gradient when active
- Scraping indicator shows "🔄 Scraping..." on active button
- Hover effects and smooth transitions

### 🔔 Browser Notifications
- Chrome notification center integration
- Badge number on extension icon
- Completion notifications with URL count
- CAPTCHA alerts that stay until dismissed

### 🎨 Color Palette
- Background: #09090b (deep black)
- Cards: #121214 (dark gray)
- Primary: #6366f1 (indigo)
- Success: #10b981 (green)
- Warning: #f59e0b (orange)
- Error: #ef4444 (red)

---

## [2.4.0] - 2026-05-06

### 🎯 DA Filter Feature
- Filter by minimum DA before export
- Works with both Download CSV and Copy URLs
- Automatic filename with DA filter (e.g., `keyword_DA30+.csv`)
- Shows filtered count in notifications

### ✅ Added
- DA filter input field in popup
- Filter logic in downloadCSV()
- Filter logic in copy button handler
- Smart filename generation with DA filter

---

## [2.3.2] - 2026-05-06

### 🎯 Major Changes
- DA is now MANDATORY in "With DA" mode
- Scraping stops if DA cannot be extracted
- Added "Powered by SAYDI" branding

### ❌ Removed
- All N/A logic from code
- N/A values in CSV export
- Fallback to N/A when DA not found

### 🔧 Changed
- Without DA mode now uses `da: 0` instead of N/A

---

## [2.3.1] - 2026-05-06

### ⚡ Ultra Fast & Smooth
- Optimized for Mozbar fast reload
- Reduced all wait times by 20-60%
- Smooth page transitions
- Fast polling (100ms intervals)

---

## [2.3.0] - 2026-05-06

### 🎯 Fast Mode - Background Mozbar
- Mozbar now works in background (no focus needed)
- Removed all focus management
- 40-50% faster overall

---

## [2.2.6] - 2026-05-06

### 🎨 New Mozbar Design Support
- Support for new Mozbar design (rounded box with "DA XX")
- Backward compatible with old SVG overlay design

---

## [2.2.5] - 2026-05-06

### 🧹 Code Cleanup
- Removed all PiP (Picture-in-Picture) code
- Cleaned up content.js

---

## [2.2.4] - 2026-05-06

### 🪟 Normal Window Implementation
- Changed from popup window to normal window
- Mozbar now works properly

---

## [2.1.0] - 2026-05-05

### 🪟 Window ID Tracking
- Implemented proper window ID tracking
- Window close detection

---

## [2.0.0] - 2026-05-03

### 🎉 Major Release
- Dual scraping modes (With DA / Without DA)
- Session persistence
- CAPTCHA detection
- Floating window
- Modern UI

---

## [1.0.0] - 2026-04-01

### 🎉 Initial Release
- Basic URL scraping
- DA extraction from Mozbar
- Simple CSV export

---

**Powered by SAYDI** | **License: MIT**
