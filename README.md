# 🌟 Kaiden's World 🌟

A comprehensive communication and learning app designed specifically for non-verbal autistic children, built with autism-friendly design principles.

## 📱 What is Kaiden's World?

Kaiden's World is a web-based communication app that provides three core tools to support daily communication and learning:

- **💬 Choice Board** - AAC (Augmentative and Alternative Communication) with 72 choices across 7 categories
- **🎵 Sound Explorer** - Interactive sound learning and games (coming soon)
- **📅 Visual Schedule** - Daily routine builder with drag-and-drop activities (coming soon)

## 🎯 Features

### Choice Board (Fully Functional)
- **72 communication choices** organized in 7 intuitive categories:
  - **I Need** (12 choices) - Basic needs like food, water, bathroom, rest
  - **I Feel** (14 choices) - Emotions from happy to worried to confused
  - **I Want To** (14 choices) - Activities like play, read, swim, dance
  - **Talk** (12 choices) - Essential communication like yes/no, please/thank you
  - **People** (10 choices) - Family members, teachers, friends, doctors
  - **Places** (10 choices) - Home, school, park, playground, library
  - **How I Like It** (12 choices) - Sensory preferences like loud/quiet, soft/firm

### Autism-Friendly Design
- **Large, clear touch targets** - Easy for small fingers to tap accurately
- **High contrast visuals** - Clear visual boundaries and readable text
- **Consistent navigation** - Same buttons in same places, predictable interactions
- **Immediate feedback** - Visual celebrations and text-to-speech for every choice
- **No time pressure** - Completely self-paced interaction
- **Minimal, clean interface** - Reduces sensory overload

### Technical Features
- **Text-to-speech** - Speaks every selection aloud
- **Visual celebrations** - Animated stars and color changes reward interaction
- **Session tracking** - Counts daily usage for progress monitoring
- **Mobile responsive** - Works on tablets, phones, and computers
- **No internet required** - Once loaded, works offline
- **No data collection** - Completely private and secure

## 🚀 How to Use

### For Kaiden:
1. **Choose an app** from the home screen
2. **Tap any choice** to communicate your needs
3. **Switch categories** using the buttons at the top
4. **Use the Home button** to return to the main menu anytime

### For Family/Caregivers:
- The app tracks daily sessions to show engagement
- All choices use clear, simple language
- Text-to-speech helps with pronunciation and clarity
- Visual feedback confirms selections were made

## 💻 Technical Setup

### Quick Setup (5 minutes):
1. Save the HTML code as `index.html`
2. Upload to [Netlify.com](https://netlify.com) (drag and drop)
3. Share the generated URL with family

### Alternative Hosting Options:
- **GitHub Pages** - Free, permanent hosting
- **Vercel** - Fast, modern hosting platform
- **Any web host** - Upload to public_html folder

### Local Usage:
- Double-click the `index.html` file to open in any browser
- Works offline once loaded
- No installation required

## 🛠️ Customization

### Adding New Choices:
1. Find the `choiceCategories` object in the code
2. Add new choices following this format:
```javascript
{ id: 'unique_id', icon: '🎯', text: 'Display Text', subtext: 'Description' }
```

### Changing Colors:
- **Choice Board**: Look for `#1976d2` (blue theme)
- **Sound Explorer**: Look for `#7b1fa2` (purple theme)  
- **Visual Schedule**: Look for `#2e7d32` (green theme)

### Adding Family Photos:
Replace emoji icons with image URLs:
```javascript
icon: 'path/to/family-photo.jpg'
```

## 📈 Future Enhancements

### Sound Explorer (Planned)
- 46 interactive sounds across 6 categories
- Animals, vehicles, musical instruments, nature sounds
- Sound matching games and exploration activities
- Synthetic sound generation with unique characteristics

### Visual Schedule (Planned)
- Drag-and-drop daily activity planning
- 20+ common daily activities with icons
- Progress tracking and completion celebrations
- Customizable time slots and routines

### Advanced Features (Ideas)
- Custom photo/voice recording
- Progress reports for therapists
- Multiple user profiles
- Backup/sync capabilities

## 🎨 Design Philosophy

This app follows evidence-based autism-friendly design principles:

- **Predictability** - Consistent layouts and interactions
- **Clarity** - High contrast, large targets, clear icons
- **Feedback** - Immediate response to all interactions
- **Choice** - Multiple ways to express the same concepts
- **Celebration** - Positive reinforcement for all attempts
- **Simplicity** - Minimal cognitive load, focused functionality

## 🔧 Browser Compatibility

- ✅ **Chrome** (recommended) - Full text-to-speech support
- ✅ **Safari** - Full functionality on iOS devices
- ✅ **Firefox** - Good performance and accessibility
- ✅ **Edge** - Modern features supported
- ⚠️ **Internet Explorer** - Not recommended (outdated)

## 📱 Device Recommendations

- **Best**: iPad or Android tablet (large touch targets)
- **Good**: Smartphone (portable, always available)
- **Okay**: Desktop/laptop (larger screen but less touch-friendly)

## 🤝 Contributing

This is a personal project for Kaiden, but ideas and suggestions are welcome:

- Report bugs or issues
- Suggest new communication choices
- Share autism-friendly design improvements
- Contribute accessibility enhancements

## 📄 License

This project is created with love for Kaiden and the autism community. Feel free to use, modify, and share for non-commercial purposes.

## 💝 Acknowledgments

- Designed specifically for **Kaiden** - an amazing 6-year-old who inspires innovation in communication
- Built with guidance from autism research and AAC best practices
- Inspired by the resilience and creativity of the autism community

## 📞 Support

For questions about customization or technical issues:
- Check browser console for error messages
- Ensure text-to-speech permissions are enabled
- Test on different devices/browsers
- Verify internet connection for initial load

---

**Made with ❤️ for Kaiden and all the amazing kids who communicate in their own special ways.**
