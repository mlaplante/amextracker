# Amex Platinum Benefit Tracker

A simple, elegant single-page application to track your American Express Platinum Card benefits and ensure you maximize their value.

## Features

- **Benefit Tracking**: Mark benefits as redeemed with automatic date tracking
- **Local Storage**: Your data persists across browser sessions
- **Statistics Dashboard**: View total value, redeemed amount, and progress percentage
- **Smart Filtering**: Filter benefits by frequency (All, Monthly, Quarterly, Semi-Annual, Annual)
- **Period Reset**: Easily reset benefits for new periods
- **Data Export/Import**: Backup and restore your tracking data
- **Mobile Responsive**: Works seamlessly on all devices
- **Accessibility**: ARIA labels and keyboard navigation support

## Included Benefits

### Monthly Credits
- **Digital Entertainment** ($25): Disney+, Hulu, NYT, Peacock, WSJ, YouTube
- **Uber Cash** ($15): Rides or Uber Eats in the U.S.
- **Walmart+** ($15.01): Monthly membership credit

### Quarterly Credits
- **Resy Credit** ($100): Dining at U.S. Resy restaurants
- **lululemon Credit** ($75): In-store or online U.S. purchases

### Semi-Annual Credits
- **Hotel Credit** ($300): Prepaid FHR or Hotel Collection bookings
- **Saks Fifth Avenue** ($50): Shop at Saks or saks.com

### Annual Credits
- **Airline Fee Credit** ($200): Incidental fees on your selected airline
- **Equinox Credit** ($300): Club membership or Equinox+ app

## Usage

1. Open `index.html` in your web browser
2. Click the frequency filter buttons to view benefits by period
3. Mark benefits as used by clicking "Mark Used" button
4. View your progress in the statistics dashboard
5. Export your data for backup or import to restore

## Technical Details

- **Framework**: Alpine.js 3.x for reactive state management
- **Styling**: Tailwind CSS 3.x for modern, responsive design
- **Storage**: Browser localStorage for data persistence
- **No Build Required**: Pure HTML/CSS/JavaScript - just open and use

## Data Management

### Export Data
Click the "Export Data" button to download your tracking data as a JSON file. This creates a timestamped backup you can save.

### Import Data
Click the "Import Data" button to restore tracking data from a previously exported JSON file.

### Reset Period
Use the "Reset Current Period" button to clear all redemption status for benefits matching your current filter. Useful for starting a new tracking period.

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- LocalStorage API
- Alpine.js 3.x
- Tailwind CSS 3.x

## Privacy

All data is stored locally in your browser. No data is sent to external servers.

## License

MIT License - Feel free to use and modify as needed.
