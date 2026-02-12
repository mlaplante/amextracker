# Platinum Elite 💳

A modern, mobile-first web application to help American Express Platinum cardholders track and maximize their 2026 card benefits. Track your YTD savings and never leave money on the table again!

![Platinum Benefit Tracker](https://img.shields.io/badge/Amex-Platinum-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Year](https://img.shields.io/badge/Year-2026-brightgreen)

## 📋 Overview

The American Express Platinum Card comes with numerous valuable benefits and credits that reset monthly, quarterly, semi-annually, or annually. This tracker helps you keep track of which benefits you've used and which are still available, ensuring you maximize the value of your card.

## ✨ Features

- **YTD Savings Tracker**: Real-time display of year-to-date savings with visual progress bar toward ROI goal ($895)
- **Modern Glassmorphism UI**: Beautiful dark theme with glass-effect cards optimized for mobile
- **Benefit Categorization**: Filter benefits by frequency (Monthly, Quarterly, Semi-Annual, Annual)
- **Visual Progress Tracking**: See at a glance which benefits have been redeemed with checkmarks and reduced opacity
- **Note-Taking**: Add tracking notes for each benefit (confirmation numbers, dates, details)
- **Stackable Benefits**: Visual indicator for benefits that can be stacked with Rakuten cashback
- **Share Functionality**: Share your ROI progress via native mobile sharing
- **Haptic Feedback**: Touch vibration feedback on mobile devices for better UX
- **Interactive UI**: Mark benefits as used with a single tap/click
- **Mobile-First Design**: Optimized for iOS and Android with touch interactions
- **No Installation Required**: Run directly in any modern web browser
- **Local Storage**: Your tracking data stays in your browser (no server required)

## 🎯 Benefits Tracked (2026)

### Monthly Benefits
- **Entertainment** - $25/month (Disney+, Hulu, YouTube Premium, NYT)
- **Uber Cash** - $15/month ($35 in December - bonus month!)
- **Walmart+** - $15.50/month (Plus Paramount+ Essential)

**Monthly Total**: $55.50/month ($75.50 in December)

### Quarterly Benefits
- **Resy Credits** - $100/quarter (Use at participating Resy restaurants)

**Quarterly Total**: $100/quarter

### Semi-Annual Benefits
- **Hotel Credit** - $300 every 6 months (Jan-Jun / Jul-Dec - PREPAID bookings only)
- **Saks Fifth Avenue** - $50 every 6 months (Stackable with Rakuten)

**Semi-Annual Total**: $350 per 6-month period

### Annual Benefits
- **Oura Ring** - $200/year (Hardware purchase credit)
- **CLEAR+ Credit** - $209/year (Biometric security renewal)

**Annual Total**: $409/year

**Total Annual Value**: $1,475 in benefits (Card annual fee: $895)
**Net Value**: $580/year profit potential!

## 🚀 How to Use

### Quick Start

1. **Open the application**:
   - Download or clone this repository
   - Open `index.html` in your web browser
   - Or visit the hosted version (if available)

2. **Track your benefits**:
   - Click on the frequency tabs (Monthly, Quarterly, Semi-Annual, Annual) to view benefits in each category
   - Tap the "+" button to mark a benefit as used
   - The benefit card will become greyed out with a checkmark
   - Your YTD savings total will automatically update
   - Add notes to track confirmation numbers, dates, or details
   - Tap again to unmark if needed

3. **Monitor your progress**:
   - View your total YTD savings at the top of the screen
   - Progress bar shows percentage toward breaking even with the annual fee ($895)
   - Use the share button to export your ROI stats

4. **Data persistence**:
   - All data is saved automatically to your browser's local storage
   - Your tracking persists across sessions
   - Data stays private on your device

### Running Locally

```bash
# Clone the repository
git clone https://github.com/mlaplante/amextracker.git

# Navigate to the directory
cd amextracker

# Open in your default browser
# On macOS:
open index.html

# On Linux:
xdg-open index.html

# On Windows:
start index.html
```

### Hosting

You can host this application anywhere that serves static files:

- **GitHub Pages**: Enable GitHub Pages in your repository settings
- **Netlify**: Drag and drop the folder into Netlify
- **Vercel**: Deploy with a single command
- **Any Web Server**: Upload `index.html` to any web hosting service

## 🛠️ Technical Details

### Built With

- **HTML5**: Semantic markup with mobile-optimized meta tags
- **Tailwind CSS**: Modern, utility-first CSS framework (via CDN)
- **Alpine.js**: Lightweight JavaScript framework for interactivity (via CDN)
- **Custom CSS**: Glassmorphism effects with backdrop-filter

### Design Features

- **Glassmorphism UI**: Modern glass-effect cards with blur and transparency
- **Dark Theme**: Eye-friendly dark background (#020408) with high-contrast text
- **Mobile-Optimized**: Touch-friendly 14px buttons, no elastic scroll on iOS
- **PWA-Ready**: Apple mobile web app capable with custom status bar styling
- **Haptic Feedback**: Native device vibration on touch interactions
- **Smooth Animations**: CSS transitions for all state changes

### Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (90+)
- Firefox (88+)
- Safari (14+) - Full iOS support
- Opera (76+)

### No Build Process Required

This is a single-file application with no dependencies to install. All libraries are loaded via CDN, making it instantly runnable without any build tools or package managers.

## 📝 Customization

The benefit list can be easily customized by editing the `defaultBenefits` array in the JavaScript section of `index.html`:

```javascript
const defaultBenefits = [
    { 
        id: 'unique_id',
        name: 'Benefit Name',
        value: 25,
        freq: 'Monthly', // or 'Quarterly', 'Semi-Annual', 'Annual'
        stackable: false, // true to show "Stack Rakuten" badge
        desc: 'Brief benefit description',
        url: 'https://link-to-benefit-details',
        used: false,
        note: ''
    },
    // Add more benefits as needed
];
```

### Storage Keys

The app uses localStorage with these keys:
- `plat_elite_v3`: Stores the benefits array with usage status and notes
- `plat_elite_savings`: Stores the total YTD savings amount

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This is an unofficial tool created to help Amex Platinum cardholders track their benefits. It is not affiliated with, endorsed by, or sponsored by American Express. Always refer to your official Amex account and terms & conditions for accurate benefit information.

Benefit details may change over time. Please verify current benefits and terms with American Express.

## 💡 Tips for Maximizing Benefits

- **Set calendar reminders** for when benefits reset (monthly, quarterly, semi-annual)
- **Use the notes field** to track confirmation numbers and dates for each redemption
- **Stack with Rakuten** where indicated (currently: Saks Fifth Avenue)
- **Remember December bonus**: Uber Cash is $35 instead of $15 in December
- **Hotel Credit requires prepaid bookings**: Can't be used for pay-at-property stays
- **Some benefits require enrollment**: Check your Amex account dashboard
- **Credits don't roll over**: Use-it-or-lose-it each period
- **Track your ROI**: Aim to use at least $895 in benefits to break even with the annual fee
- **Screenshot your progress**: Use the share button to export your savings stats

## 🔗 Useful Links

- [American Express Platinum Card Benefits](https://www.americanexpress.com/us/credit-cards/card/platinum/)
- [Amex Offers Portal](https://www.americanexpress.com/us/credit-cards/features-benefits/offers/)

---

Made with ❤️ for Amex Platinum cardholders who want to maximize their benefits.
