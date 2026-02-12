# Amex Platinum Benefit Tracker 💳

A simple, elegant web application to help American Express Platinum cardholders track and maximize their card benefits. Never leave money on the table again!

![Platinum Benefit Tracker](https://img.shields.io/badge/Amex-Platinum-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 📋 Overview

The American Express Platinum Card comes with numerous valuable benefits and credits that reset monthly, quarterly, semi-annually, or annually. This tracker helps you keep track of which benefits you've used and which are still available, ensuring you maximize the value of your card.

## ✨ Features

- **Benefit Categorization**: Filter benefits by frequency (Monthly, Quarterly, Semi-Annual, Annual)
- **Visual Progress Tracking**: See at a glance which benefits have been redeemed
- **Interactive UI**: Mark benefits as used with a single click
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **No Installation Required**: Run directly in any modern web browser
- **Local Storage**: Your tracking data stays in your browser (no server required)

## 🎯 Benefits Tracked

### Monthly Benefits
- **Digital Entertainment** - $25/month (Disney+, Hulu, NYT, Peacock, WSJ, YouTube)
- **Uber Cash** - $15/month (Rides or Uber Eats in the U.S.)
- **Walmart+** - $15.01/month (Monthly membership credit)

### Quarterly Benefits
- **Resy Credit** - $100/quarter (Dining at U.S. Resy restaurants)
- **lululemon Credit** - $75/quarter (In-store or online U.S. purchases)

### Semi-Annual Benefits
- **Hotel Credit** - $300 every 6 months (Prepaid FHR or Hotel Collection bookings)
- **Saks Fifth Avenue** - $50 every 6 months (Shop at Saks or saks.com)

### Annual Benefits
- **Airline Fee Credit** - $200/year (Incidental fees on your selected airline)
- **Equinox Credit** - $300/year (Club membership or Equinox+ app)

**Total Potential Value**: Over $1,800 in annual benefits!

## 🚀 How to Use

### Quick Start

1. **Open the application**:
   - Download or clone this repository
   - Open `index.html` in your web browser
   - Or visit the hosted version (if available)

2. **Track your benefits**:
   - Click on the frequency tabs (Monthly, Quarterly, Semi-Annual, Annual) to view benefits in each category
   - Click the "Mark Used" button when you redeem a benefit
   - The progress bar will fill and the button will change to "✓ Redeemed"
   - Click again to unmark if needed

3. **Reset tracking**:
   - Refresh the page to reset all benefits (useful when a new period starts)
   - Or click individual benefits to toggle their status

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

- **HTML5**: Semantic markup
- **Tailwind CSS**: Modern, utility-first CSS framework (via CDN)
- **Alpine.js**: Lightweight JavaScript framework for interactivity (via CDN)

### Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (90+)
- Firefox (88+)
- Safari (14+)
- Opera (76+)

### No Build Process Required

This is a single-file application with no dependencies to install. All libraries are loaded via CDN, making it instantly runnable without any build tools or package managers.

## 📝 Customization

The benefit list can be easily customized by editing the `benefits` array in the JavaScript section of `index.html`:

```javascript
benefits: [
    { 
        id: 1, 
        name: 'Benefit Name', 
        value: 25, 
        freq: 'Monthly', 
        description: 'Benefit description', 
        used: false 
    },
    // Add more benefits as needed
]
```

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

- Set calendar reminders for when benefits reset
- Keep track of which credits you've used each period
- Some benefits require enrollment - check your Amex account
- Certain benefits may be exclusive to specific Platinum card variants
- Credits are typically use-it-or-lose-it and don't roll over

## 🔗 Useful Links

- [American Express Platinum Card Benefits](https://www.americanexpress.com/us/credit-cards/card/platinum/)
- [Amex Offers Portal](https://www.americanexpress.com/us/credit-cards/features-benefits/offers/)

---

Made with ❤️ for Amex Platinum cardholders who want to maximize their benefits.
