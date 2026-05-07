# Google URL Scraper with Mozbar DA - Complete Setup Guide

**Version 3.0.7** | Auto-extract URLs from Google search with Domain Authority

---

## 🚀 Quick Start - Installation

### Step 1: Enable Developer Mode
1. Open: `chrome://extensions/`
2. Toggle **"Developer mode" ON** (top-right corner)

### Step 2: Download Extension
Download the extension files:
- Clone from GitHub: `https://github.com/saimulhaquesaydi/google-url-scraper-with-moz-DA`
- Or download ZIP and extract

### Step 3: Install Extension
1. Open Chrome → `chrome://extensions/`
2. Click **"Load unpacked"**
3. Select the extension folder
4. Wait until installed
5. You will see **"Google URL Scraper"** appear in the list

### Step 4: Install Mozbar (Required for DA)
1. Install [Mozbar Extension](https://moz.com/products/pro/seo-toolbar)
2. Log in to your Moz account
3. Enable Mozbar on Google search pages

---

## 📖 How to Use

### Basic Usage

**Step 1: Go to Google Search**
- Open: `https://google.com`
- Type your search query, for example: `CBD "write for us"`
- Press Enter to see search results

**Step 2: Open Extension**
- Click the extension icon in Chrome toolbar
- Or use keyboard shortcut (if set)

**Step 3: Start Scraping**
- Click **🚀 Start Scraping** (with DA extraction)
- Or click **⚡ Scrape Without DA** (fast mode)

**Step 4: Monitor Progress**
You will see real-time stats:
- **Page**: Current page number
- **Saved**: Total URLs found
- **Status**: Scraping status

**Step 5: Handle CAPTCHA (if appears)**
- Solve CAPTCHA in the scraping window
- Click **▶️ Resume Scraping** button

**Step 6: Export Data**
- **Optional**: Set minimum DA filter (e.g., 30)
- Click **📥 Export CSV** to download
- Or click **📋 Copy URLs** to clipboard

---

## 🎯 Features

### Dual Scraping Modes
- **With DA**: Extract URLs with Domain Authority (requires Mozbar)
- **Without DA**: Fast URL collection only

### Real-Time Progress
- See URLs collected in real-time
- Page number updates automatically
- Status indicator shows current state

### Session Management
- **Auto-save**: Data saved after each page
- **Resume**: Continue from where you left off
- **Pause/Stop**: Stop anytime and resume later

### DA Filter
- Set minimum DA threshold (e.g., 30)
- Only export URLs with DA ≥ threshold
- Smart filename: `keyword_DA30+.csv`

### Export Options
- **CSV Download**: Automatic filename with keyword
- **Copy to Clipboard**: Tab-separated format
- **Batch Export**: Export all collected URLs at once

---

## 🎨 Interface Overview

### Stats Display
```
┌─────────────────────────────────┐
│  Page: 5                        │
│  Saved: 127 URLs                │
│  Status: ✅ Ready               │
└─────────────────────────────────┘
```

### Buttons
- **🚀 Start Scraping** - Begin with DA extraction
- **⚡ Scrape Without DA** - Fast mode without DA
- **▶️ Resume Scraping** - Continue after pause/CAPTCHA
- **📥 Export CSV** - Download as CSV file
- **📋 Copy URLs** - Copy to clipboard
- **🗑️ Clear Data** - Remove all saved data
- **⏹️ Stop Scraping** - Pause current session

### Notifications
- **White**: Scraping in progress
- **Yellow**: Scraping stopped/paused
- **Red**: CAPTCHA detected or error
- **Green**: Scraping complete

---

## ⚙️ Settings

### DA Filter (Optional)
```
Minimum DA: [30]
```
- Enter minimum DA value (0-100)
- Leave empty to export all URLs
- Filter applies to both CSV and Copy

### Example Filenames
- Without filter: `cbd_write_for_us.csv`
- With DA 30+: `cbd_write_for_us_DA30+.csv`

---

## 🔧 Troubleshooting

### Issue: DA Not Found
**Problem**: "DA not found" error appears

**Solution**:
1. Check Mozbar is installed and enabled
2. Verify you're logged in to Moz account
3. Refresh Google search page
4. Wait for Mozbar to load (green icon appears)

### Issue: CAPTCHA Detected
**Problem**: Scraping paused with CAPTCHA message

**Solution**:
1. Solve CAPTCHA in the scraping window
2. Click **▶️ Resume Scraping** button
3. Your data is safe and saved

### Issue: Extension Not Working
**Problem**: Extension doesn't start

**Solution**:
1. Check you're on Google search page
2. Reload extension: `chrome://extensions/` → Reload
3. Check Developer mode is enabled
4. Try removing and reinstalling

### Issue: URLs Not Saving
**Problem**: URL count stays at 0

**Solution**:
1. Verify search results are visible on page
2. Check browser console for errors (F12)
3. Try "Scrape Without DA" mode first
4. Reload Google search page

---

## 📊 Performance

| Feature | With DA | Without DA |
|---------|---------|------------|
| Speed | 2-3 sec/page | 2 sec/page |
| Accuracy | 100% | 100% |
| Max URLs | 10,000 | 10,000 |
| Background | ✅ Yes | ✅ Yes |

---

## 💡 Tips & Tricks

### Tip 1: Use DA Filter
Set minimum DA to get only high-quality sites:
```
DA Filter: 30
Result: Only sites with DA ≥ 30
```

### Tip 2: Work While Scraping
Extension scrapes in background window:
- Continue working in other tabs
- Check progress anytime by opening popup
- Badge shows current page number

### Tip 3: Resume Anytime
Session data is auto-saved:
- Close browser and come back later
- Click "Start Scraping" to resume
- All collected URLs are preserved

### Tip 4: Batch Processing
Scrape multiple keywords:
1. Scrape first keyword
2. Export CSV
3. Clear data
4. Search next keyword
5. Repeat

---

## 🎓 Example Workflow

### Example: Find Guest Post Sites

**Step 1**: Search on Google
```
Search: "digital marketing" "write for us"
```

**Step 2**: Start Scraping
- Click "Start Scraping"
- Wait for pages to scrape
- Monitor progress in popup

**Step 3**: Set DA Filter
```
Minimum DA: 30
```

**Step 4**: Export
- Click "Export CSV"
- File saved: `digital_marketing_write_for_us_DA30+.csv`

**Step 5**: Result
```csv
Url,Google index
example.com,45
website.org,52
blog.net,38
```

---

## 📋 CSV Format

### With DA Mode
```csv
Url,Google index
example.com,45
website.org,52
blog.net,38
```

### Without DA Mode
```csv
Url
example.com
website.org
blog.net
```

---

## 🔒 Privacy & Security

- ✅ **No data collection** - All data stays local
- ✅ **No tracking** - No analytics or tracking
- ✅ **No external requests** - Except to Google and Moz
- ✅ **Open source** - Full code transparency

---

## 📞 Support

### Need Help?
- **GitHub Issues**: [Report Bug](https://github.com/saimulhaquesaydi/google-url-scraper-with-moz-DA/issues)
- **Email**: support@saydi.com
- **Documentation**: README.md

### Found a Bug?
Please report with:
1. Chrome version
2. Extension version (3.0.7)
3. Steps to reproduce
4. Screenshot (if possible)

---

## 📝 Version History

### v3.0.7 (Current)
- Modern glassmorphism UI
- White notification for scraping progress
- Bold black text for all notifications
- Browser notifications with badge
- Both scraping buttons same design

### v2.4.0
- DA filter feature
- Smart filename generation

### v2.3.2
- DA mandatory in "With DA" mode
- "Powered by SAYDI" branding

### v2.0.0
- Dual scraping modes
- Session persistence
- CAPTCHA detection

---

## 🙏 Credits

**Developed by**: SAYDI  
**Mozbar**: Moz, Inc.  
**License**: MIT

---

**Powered by SAYDI** | **Version 3.0.7** | **License: MIT**

⭐ Star on GitHub | 💬 Report Issues | 💡 Suggest Features
