# Open University Classification Calculator 🎓

An interactive calculator for predicting your Open University honours degree classification. Built for students completing 360-credit bachelor's degrees awarded after 1 March 2023.

![OU Calculator](https://img.shields.io/badge/OU-Classification%20Calculator-002855?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## ✨ Features

- **📊 Real-time Classification Calculation** - See your current classification as you input modules
- **🎯 Smart Projections** - Discover what grades you need to achieve higher classifications
- **🔄 Borderline Range Detection** - Automatically checks if you meet borderline test requirements
- **💾 Dynamic Module Management** - Add and remove modules easily for Level 2 and Level 3
- **📱 Responsive Design** - Works beautifully on desktop, tablet, and mobile devices
- **🎨 Academic Aesthetic** - Clean, professional interface inspired by OU's academic heritage
- **⚡ Zero Dependencies** - Pure HTML, CSS, and JavaScript - no frameworks required

## 📖 How It Works

### Classification Calculation

The Open University calculates degree classifications using a **weighted grade credit score**:

1. **Level 2 modules** (120 credits) - Single weighted
2. **Level 3 modules** (120 credits) - Double weighted

#### Formula

```
Total Score = Level 2 Score + (Level 3 Score × 2)

Where:
- Level 2 Score = Σ(credits × grade)
- Level 3 Score = Σ(credits × grade) × 2
```

#### Grade Values

- **Grade 1** - Distinction (85%+)
- **Grade 2** - Pass 2 (70-84%)
- **Grade 3** - Pass 3 (55-69%)
- **Grade 4** - Pass 4 (40-54%)

### Classification Bands

| Score Range | Classification | Borderline Test |
|-------------|----------------|-----------------|
| ≤ 630 | First-class (1st) | - |
| 631 - 690 | First-class or Upper Second (2:1)* | Need 60+ L3 credits at Grade 1 for 1st |
| 691 - 900 | Upper Second (2:1) | - |
| 901 - 960 | Upper Second or Lower Second (2:2)* | Need 60+ L3 credits at Grade 1-2 for 2:1 |
| 961 - 1170 | Lower Second (2:2) | - |
| 1171 - 1230 | Lower Second or Third (3rd)* | Need 60+ L3 credits at Grade 1-3 for 2:2 |
| 1231 - 1440 | Third (3rd) | - |

*Borderline ranges - higher classification awarded if borderline test is met

## 🎯 Usage Guide

### Adding Modules

1. Click "**+ Add Level 2 Module**" or "**+ Add Level 3 Module**"
2. Enter module name (optional, for your reference)
3. Enter credits (typically 15, 30, or 60)
4. Select the grade achieved or projected

### Understanding Results

The calculator displays:

- **Weighted Grade Credit Score** - Your total calculated score
- **Current Classification** - Based on your entered modules
- **Score Breakdown** - Showing Level 2 and Level 3 contributions
- **Borderline Status** - If applicable, with test requirements
- **Projections** - What grades you need for higher classifications

### Projections Feature

If you haven't completed all 240 credits (120 at each level), the calculator shows:

- Target scores for each classification band
- Average grades needed across remaining modules
- Specific credit requirements

### Tips for Best Results

✅ **Include all completed modules** with actual grades  
✅ **Add projected modules** with realistic grade estimates  
✅ **Update regularly** as you complete assignments  
✅ **Consider borderline ranges** - they can make a big difference!

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## ⚠️ Important Disclaimer

This calculator is for **illustrative purposes only**. 

- Official degree classifications are awarded by The Open University
- Calculation rules may vary for specific degree programs
- Always verify your status with your official student record
- This tool is designed for 360-credit bachelor's honours degrees awarded after 1 March 2023

For official information, visit [The Open University website](https://help.open.ac.uk/documents/policies/working-out-your-class-of-honours).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Areas for enhancement:

- Additional degree types (foundation, graduate, etc.)
- Export/import functionality for module data
- Data persistence (localStorage)
- Print-friendly format
- Dark mode toggle
- Multiple language support

## 📄 License

MIT License - feel free to use, modify, and distribute as you wish.

**Made for OU Students | Not affiliated with The Open University**

⭐ If this helped you, consider starring the repository!
