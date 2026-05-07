# Google URL Scraper with Mozbar DA

**Version 3.0.7** | Automatically scrape and collect URLs from Google search results with Domain Authority (DA) extraction.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-3.0.7-green.svg)
![Chrome](https://img.shields.io/badge/chrome-extension-orange.svg)

---

## ✨ Features

### 🎯 Dual Scraping Modes
- **With DA**: Extract URLs with Domain Authority from Mozbar
- **Without DA**: Fast URL collection without DA extraction

### 💾 Session Persistence
- Auto-save after each page
- Resume from where you left off
- Data survives browser restart

### 🚫 CAPTCHA Detection
- Automatic detection and pause
- One-click resume after solving
- Session data preserved

### 🎨 Modern Glassmorphism UI
- Dark theme with glass effects
- Compact 340px width
- Real-time stats display
- Smooth animations

### 📊 DA Filter
- Set minimum DA threshold
- Filter on export (CSV or Copy)
- Smart filename generation

### 🔔 Browser Notifications
- Chrome notification center integration
- Badge number on extension icon
- Completion alerts with URL count

### 📥 Export Options
- **CSV**: `URL, Google index` format
- **Copy**: Tab-separated clipboard format
- Automatic filename with keyword and DA filter

### 🪟 Background Scraping
- Scrape in a separate window
- Work in other tabs while scraping
- Mozbar works in the background

---

## 🚀 Quick Start

### Installation

1. **Download Extension**
   ```bash
   git clone https://github.com/saimulhaquesaydi/google-url-scraper-with-moz-DA.git
   ```

2. **Load in Chrome**
   - Open `chrome://extensions/.`
   - Enable "Developer mode."
   - Click "Load unpacked."
   - Select the extension folder

3. **Install Mozbar** (Required for DA extraction)
   - Install [Mozbar Chrome Extension](https://moz.com/products/pro/seo-toolbar)
   - Log in to your Moz account

### Usage

1. **Go to Google Search**
   - Search for your keyword
   - Open extension popup

2. **Start Scraping**
   - Click "Start Scraping" (with DA)
   - Or "Scrape Without DA" (fast mode)

3. **Monitor Progress**
   - See real-time stats (Page, URLs, Status)
   - Badge shows current page number
   - Work in other tabs while scraping

4. **Handle CAPTCHA** (if detected)
   - Solve CAPTCHA in the scraping window
   - Click "Resume Scraping"

5. **Export Data**
   - Set minimum DA filter (optional)
   - Click "Export CSV" or "Copy URLs"
   - Automatic filename with keyword

---

## 📖 User Guide

### Scraping Modes

#### With DA Mode
- Extracts Domain Authority from Mozbar
- Requires Mozbar extension and login
- ~2-3 seconds per page
- DA is mandatory (stops if not found)

#### Without DA Mode
- Fast URL collection only
- No Mozbar required
- ~2 seconds per page
- DA value set to 0

### DA Filter

Set minimum DA threshold before export:

```
Example: Enter "30" in the DA filter
Result: Only URLs with DA ≥ 30 exported
Filename: keyword_DA30+.csv
```

### CSV Format

**With DA Mode:**
```csv
Url, Google index
example.com,45
website.org,52
```

**Without DA Mode:**
```csv
Url
example.com
website.org
```

### Session Management

- **Auto-save**: After each page
- **Resume**: Click "Start Scraping" to resume
- **Clear**: Remove all saved data
- **Stop**: Pause scraping (can resume later)

---

## 🎨 UI Overview

### Stats Display
- **Page**: Current page number
- **Saved**: Total URLs collected
- **Status**: Scraping status (Ready, Scraping, Complete, CAPTCHA)

### Buttons
- **Start Scraping**: Begin with DA extraction
- **Scrape Without DA**: Fast mode without DA
- **Resume Scraping**: Continue after CAPTCHA/pause
- **Export CSV**: Download as CSV file
- **Copy URLs**: Copy to clipboard
- **Clear Data**: Remove all saved data
- **Stop Scraping**: Pause current session

### Notifications
- **Progress** (White): Scraping in progress
- **Stopped** (Yellow): Scraping paused
- **CAPTCHA** (Red): CAPTCHA detected
- **Complete** (Green): Scraping finished
- **Error** (Red): Error occurred

---

## ⚙️ Configuration

### Extension Settings
- No configuration needed
- Works out of the box

### Mozbar Requirements
- Active Moz account
- Logged in to Mozbar
- Mozbar enabled on Google search pages

---

## 🐛 Troubleshooting

### DA Not Found
**Problem**: "DA not found" error
**Solution**:
- Check Mozbar is installed and enabled
- Verify you're logged in to your Moz account
- Refresh the Google search page
- Wait for Mozbar to load completely

### CAPTCHA Detected
**Problem**: Scraping paused with CAPTCHA
**Solution**:
- Solve CAPTCHA in the scraping window
- Click the "Resume Scraping" button
- Session data is preserved

### Extension Not Loading
**Problem**: Extension doesn't appear
**Solution**:
- Check Developer mode is enabled
- Reload extension in `chrome://extensions/.
- Check for errors in the extension console

### URLs Not Saving
**Problem**: URL count not increasing
**Solution**:
- Check you're on the Google search page
- Verify search results are visible
- Check browser console for errors

---

## 📊 Performance

| Metric | With DA | Without DA |
|--------|---------|------------|
| Speed | 2-3s/page | 2s/page |
| Accuracy | 100% | 100% |
| Max URLs | 10,000 | 10,000 |
| Session Persistence | ✅ Yes | ✅ Yes |

---

## 🔒 Privacy & Security

- **No Data Collection**: All data stays local
- **No External Requests**: Except to Google and Moz
- **No Tracking**: No analytics or tracking
- **Open Source**: Full code transparency

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup

1. Clone the repository
2. Make changes
3. Test in Chrome
4. Submit PR

### Code Style
- Use ES6+ JavaScript
- Follow existing code structure
- Add comments for complex logic
- Test all changes thoroughly

---

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details.

Copyright (c) 2026 SAYDI

---

## 🙏 Credits

**Developed by**: SAYDI  
**Mozbar**: Moz, Inc.  
**Icons**: Feather Icons

---

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/saimulhaquesaydi/google-url-scraper-with-moz-DA/issues)
- **Email**: saimulhaquesaydi@gmail.com
- **Documentation**: [Release Notes](RELEASE_NOTES.md)

---

## 🗺️ Roadmap

### Planned Features
- [ ] Support for Bing, DuckDuckGo
- [ ] Batch processing multiple keywords
- [ ] Export to JSON, Excel
- [ ] Advanced filtering options
- [ ] Scheduled scraping
- [ ] API integration

---

**Powered by SAYDI** | **Version 3.0.7** | **License: MIT**

⭐ Star on GitHub | 💬 Report Issues | 💡 Suggest Features
