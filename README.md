# TimeTracker Pro - Chrome Extension & Analytics Dashboard

A comprehensive time tracking Chrome extension with beautiful analytics dashboard for productivity insights.

## Features

### Chrome Extension
- **Real-time Time Tracking**: Automatically tracks time spent on different websites
- **Smart Categorization**: Automatically categorizes websites as productive, unproductive, or neutral
- **Idle Detection**: Pauses tracking when you're away from your computer
- **Beautiful Popup**: Quick access to daily stats and productivity score
- **Privacy-Focused**: All data stored locally on your device

### Web Dashboard
- **Interactive Analytics**: Beautiful charts and visualizations of your productivity data
- **Weekly Reports**: Comprehensive weekly productivity reports with insights
- **Activity Heatmap**: Visual representation of your daily activity patterns
- **Productivity Scoring**: Intelligent scoring system to track your progress
- **Customizable Settings**: Adjust tracking preferences and productivity goals

## Installation

### Chrome Extension
1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" in the top right corner
3. Click "Load unpacked" and select the `public` folder
4. The extension will be installed and ready to use

### Web Dashboard
1. Make sure you have Node.js installed
2. Run `npm install` to install dependencies
3. Run `npm run dev` to start the development server
4. Open `http://localhost:5173` in your browser

## Usage

1. **Install the Extension**: Follow the installation instructions above
2. **Start Browsing**: The extension will automatically start tracking your time
3. **View Quick Stats**: Click the extension icon to see your daily productivity stats
4. **Open Dashboard**: Click "View Dashboard" in the popup to see detailed analytics
5. **Customize Settings**: Click the settings icon to adjust your preferences

## Website Categories

### Productive Sites
- **Coding**: GitHub, Stack Overflow, CodePen, LeetCode, etc.
- **Learning**: Coursera, Udemy, Khan Academy, Medium, etc.
- **Work**: Google Docs, Gmail, Slack, Notion, Trello, etc.

### Unproductive Sites
- **Social Media**: Facebook, Twitter, Instagram, TikTok, etc.
- **Entertainment**: YouTube, Netflix, Twitch, Reddit, etc.

### Neutral Sites
- All other websites that don't fall into the above categories

## Privacy & Data

- All tracking data is stored locally in your browser
- No data is sent to external servers
- You can export your data at any time
- You can clear all data from the settings page

## Development

### Project Structure
```
/public/               # Chrome extension files
  manifest.json        # Extension manifest
  background.js        # Background service worker
  content.js          # Content script
  popup.html/js       # Extension popup
  options.html        # Settings page

/src/                  # React dashboard source
  components/         # React components
  App.tsx            # Main app component
  main.tsx           # Entry point
```

### Technologies Used
- **Chrome Extension**: Vanilla JavaScript, Chrome APIs
- **Dashboard**: React, TypeScript, Tailwind CSS, Vite
- **Icons**: Lucide React
- **Styling**: Tailwind CSS with custom gradients

## License

MIT License - see LICENSE file for details.