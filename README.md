# 🌟 Kaiden's World 🌟

**A comprehensive AAC (Augmentative and Alternative Communication) web application designed for non-verbal children with developmental communication needs.**

**Live Application:** https://benwah81.github.io/Kaidens-World/

---

## 📱 About This Project

Kaiden's World is a personal project created with love to support communication and learning for a non-verbal child. Built with evidence-based AAC research and professional therapeutic practices in mind, this application provides tools and exercises used by speech-language pathologists and therapists, all accessible through any modern web browser on tablets, phones, or computers.

**Key Design Principles:**
- ✅ **Tablet-optimized** - Touch-friendly, no mouse or stylus required
- ✅ **Evidence-based** - Features backed by AAC research and therapeutic best practices
- ✅ **Personalized** - Custom voice recordings in familiar voices for comfort
- ✅ **Accessible** - Works on any device with a modern browser
- ✅ **Free & Open** - No downloads, no accounts, no cost, no tracking
- ✅ **Modular** - Each feature is standalone for easy maintenance and expansion

---

## 🎯 Complete Feature Set (17 Total)

### **Core Communication Tools (6 features)**
1. **💬 Choice Board** - 72 communication choices across 7 categories (I Need, I Feel, I Want To, Talk, People, Places, How I Like It)
2. **🎵 Sound Explorer** - 46 organized sounds with games and learning activities across 6 categories
3. **💬 Communication Scripts** - 40+ common phrases organized into 5 everyday situation categories
4. **🎙️ Voice Recorder** - Record custom messages in familiar voices with 7 organized categories
5. **😊 My Feelings** - 12 emotion identification and expression options with voice support
6. **✅ Yes or No** - Large binary choice buttons for simple decision making

### **Learning & Development (4 features)**
7. **🎮 Games** - 4 animated character games (Sunny, Luna, Buddy, Splash) with interactive learning
8. **🎯 Cause & Effect** - 4 interactive games (bubbles, colors, sounds, shapes) for early learning
9. **🎨 Art Board** - Full drawing canvas with 11 colors, brush sizes, 10 stamps, undo, and save functionality
10. **📖 Social Stories** - 6 illustrated 7-page stories for preparing for new experiences

### **Structure & Planning (4 features)**
11. **📅 Visual Schedule** - Tap-to-place activity planning with 20 activities, progress tracking, and celebrations
12. **📋 First-Then Board** - Simple two-step task sequencing with 24 activities
13. **⏰ Wait Timer** - Visual countdown timer with 6 presets, custom times, and celebrations
14. **🚨 Transition Warnings** - Countdown alerts before activity changes to reduce anxiety

### **Behavioral & Emotional Support (2 features)**
15. **🌟 Token Board** - Visual reward system with customizable goals and celebration animations
16. **🧘 Calm Down Corner** - 6 self-regulation strategies including breathing exercises and zones of regulation

### **Configuration (1 feature)**
17. **⚙️ Settings** - Full customization of voice (speed, pitch, volume), visuals (text size, themes), and behaviors

---

## 🌐 Browser Compatibility

### ✅ **Fully Compatible:**
- **Chrome** (Desktop & Mobile) - Recommended
- **Safari** (iOS/iPad/Mac) - Recommended for Apple devices
- **Microsoft Edge** (Desktop & Mobile)
- **Samsung Internet** (Android)
- **Firefox** (Desktop & Mobile)

### ⚠️ **Limited Compatibility:**
- **Older browsers** (pre-2015) - Most features work, Voice Recorder may not
- **Internet Explorer** - Not supported (use Edge instead)

### 🧪 **Test Your Browser:**
Visit the [Browser Compatibility Checker](https://benwah81.github.io/Kaidens-World/browser-check.html) to verify all features work on your device. Tests include:
- Text-to-speech support
- Microphone access
- Canvas drawing
- Touch events
- Local storage
- Audio playback

---

## 📱 How to Access on Tablet

### **Method 1: Direct Web Access (Easiest)**
1. Open your browser (Safari on iOS, Chrome on Android)
2. Go to: **https://benwah81.github.io/Kaidens-World/**
3. Start using immediately!

### **Method 2: Add to Home Screen (Recommended)**

**iPad/iPhone (Safari):**
1. Open the website
2. Tap the Share button (square with arrow)
3. Tap "Add to Home Screen"
4. Name it "Kaiden's World" and tap "Add"
5. ✅ App icon appears on home screen like a native app!

**Android (Chrome):**
1. Open the website
2. Tap Menu (⋮) in top right
3. Tap "Add to Home Screen"
4. Name it "Kaiden's World" and tap "Add"
5. ✅ App icon appears on home screen!

**Result:** Access the app instantly with one tap, just like any other app!

See the complete [Tablet Access Guide](TABLET-ACCESS-GUIDE.md) for detailed setup instructions.

---

## 👨‍👩‍👧‍👦 For Parents & Caregivers

### **Getting Started:**
1. **Test first** - Use the [Browser Check](https://benwah81.github.io/Kaidens-World/browser-check.html) to verify compatibility
2. **Review features** - Explore each section to understand what's available
3. **Customize settings** - Adjust voice, text size, and visuals for your child's needs
4. **Practice together** - Introduce features in a calm, supportive environment
5. **Use consistently** - Regular daily use provides the best communication gains

### **Tips for Success:**
- **Start simple** - Begin with 1-2 features your child enjoys (Choice Board is great for beginners)
- **Be consistent** - Daily use builds familiarity and communication skills
- **Customize voice** - Record common phrases in your own voice for comfort and recognition
- **Adjust settings** - Make text larger, adjust voice speed, change themes as needed
- **Celebrate progress** - Use reward features (Token Board) to motivate and encourage
- **Follow the child's lead** - Let them explore at their own pace

### **Complete Testing Guide:**
Before regular use, complete the [Tablet Testing Checklist](TABLET-TESTING-CHECKLIST.md) to ensure:
- All features work properly on your device
- Touch interactions are responsive
- Audio is clear and appropriate volume
- No crashes or major bugs
- Microphone permission granted (for Voice Recorder)

---

## 💻 For Developers

### **Technology Stack:**
- **Pure vanilla JavaScript** - No frameworks or libraries
- **HTML5 & CSS3** - Semantic markup with modern styling
- **Responsive design** - Works on all screen sizes (mobile-first approach)
- **Touch-optimized** - Tap events instead of drag-and-drop for tablet accessibility
- **Web Speech API** - Text-to-speech for voice output
- **MediaRecorder API** - Voice recording functionality
- **Canvas API** - Drawing and graphics
- **LocalStorage API** - Settings and data persistence
- **Audio Context API** - Sound generation and playback

### **Architecture:**

**Modular Standalone Design:**
Each feature is a completely standalone HTML file with embedded CSS and JavaScript. This architecture provides:
- **Easy maintenance** - Update one feature without affecting others
- **Simple debugging** - Isolated code for each feature
- **No build process** - Just edit and reload
- **Fast loading** - No framework overhead
- **Easy deployment** - Simple file structure

**Key Files:**
```
Kaidens-World/
├── index.html                    # Main hub with 17 feature cards
├── browser-check.html            # Compatibility testing tool
│
├── choice-board.html             # Core communication - 72 choices
├── sound-explorer.html           # Sound learning - 46 sounds
├── visual-schedule.html          # Activity planning - 20 activities
├── first-then-board.html         # Task sequencing - 24 activities
├── games.html                    # Interactive games - 4 characters
├── social-stories.html           # Illustrated stories - 6 stories
├── wait-timer.html               # Visual countdown timer
├── emotion-chart.html            # Feeling identification - 12 emotions
├── yes-no-cards.html             # Binary choices
├── token-board.html              # Reward system
├── calm-corner.html              # Self-regulation - 6 strategies
├── transition-warnings.html      # Activity warnings
├── communication-scripts.html    # Common phrases - 40+ scripts
├── cause-effect.html             # Interactive games - 4 games
├── art-board.html                # Drawing canvas
├── voice-recorder.html           # Custom voice messages
├── settings.html                 # App configuration
│
├── README.md                     # This file
├── TABLET-TESTING-CHECKLIST.md   # Complete QA checklist
├── TABLET-ACCESS-GUIDE.md        # Setup instructions
│
└── .github/workflows/            # GitHub Pages deployment
```

### **Project Structure:**

**index.html** - Central hub that links to all features. Includes:
- Animated cards for each feature
- Session tracking and statistics
- Floating particle effects
- Responsive grid layout
- Direct navigation to all 17 features

**Individual Feature Files** - Each is a complete standalone app:
- Full HTML structure
- Embedded CSS in `<style>` tags
- All JavaScript in `<script>` tags
- Back button to return to home
- Consistent color scheme per feature

### **Design Decisions:**

**1. No Dependencies:**
- Zero external libraries or frameworks
- Faster initial load time
- No breaking changes from updates
- Works offline after first visit
- Simpler codebase for maintenance

**2. Modular Architecture:**
- Each feature is completely independent
- Easy to add new features
- Easy to remove features if needed
- Simple to test individual components
- Clear separation of concerns

**3. Tablet-First Approach:**
- Touch events, never mouse events
- Large tap targets (minimum 44x44px)
- Tap-to-select instead of drag-and-drop
- No hover-required interactions
- Forgiving touch areas
- Visual feedback on all interactions

**4. Progressive Enhancement:**
- Core features work on all browsers
- Advanced features (voice recording) degrade gracefully
- Clear error messages when features unavailable
- Fallbacks for unsupported APIs

**5. Accessibility:**
- High contrast colors
- Large, readable fonts
- Voice feedback on all actions
- Visual feedback (animations, color changes)
- Simple, intuitive navigation
- ARIA labels where appropriate

### **Local Development:**

```bash
# Clone the repository
git clone https://github.com/Benwah81/Kaidens-World.git

# Navigate to directory
cd Kaidens-World

# No build step needed! Just open in browser:
# Option 1: Open index.html directly in browser

# Option 2: Use a simple HTTP server (recommended for testing)
# Python 3:
python -m http.server 8000

# Python 2:
python -m SimpleHTTPServer 8000

# Node.js (if you have http-server installed):
npx http-server -p 8000

# Then visit: http://localhost:8000
```

**Development Workflow:**
1. Edit HTML file for the feature you're working on
2. Refresh browser to see changes (Ctrl+R or Cmd+R)
3. Test on multiple browsers and devices
4. Commit changes to Git
5. Push to GitHub (auto-deploys to GitHub Pages)

### **Contributing:**
This is a personal project, but suggestions and improvements are welcome! Guidelines:
1. **Focus on evidence-based AAC features** - Research therapeutic value
2. **Maintain tablet compatibility** - Test on actual tablets
3. **Keep it simple** - No frameworks, vanilla JS only
4. **Preserve modularity** - Each feature should be standalone
5. **Follow existing patterns** - Match the style of current features
6. **Test thoroughly** - Use the testing checklist

### **Adding a New Feature:**
1. Create a new HTML file (e.g., `new-feature.html`)
2. Copy structure from existing feature
3. Implement feature with embedded CSS and JS
4. Add feature card to `index.html`
5. Update README.md feature count and descriptions
6. Add to testing checklist
7. Test on multiple browsers and tablets

---

## 🧪 Testing & Quality Assurance

### **Automated Compatibility Check:**
[Browser Compatibility Checker](https://benwah81.github.io/Kaidens-World/browser-check.html) tests:
- Web Speech API support
- MediaRecorder API support
- Canvas API support
- Touch event support
- LocalStorage support
- Audio playback support

### **Manual Testing Checklist:**
Complete [TABLET-TESTING-CHECKLIST.md](TABLET-TESTING-CHECKLIST.md) covers:
- All 17 features individually tested
- Touch responsiveness verification
- Audio and voice testing
- Performance and stability checks
- Offline functionality
- Microphone permissions
- Observation notes for improvements

### **Cross-Browser Testing:**
Tested on:
- iOS Safari (iPad & iPhone)
- Android Chrome (tablets & phones)
- Desktop Chrome, Firefox, Edge, Safari
- Samsung Internet (Android)

---

## 🎨 Design Philosophy

### **Accessibility First:**
- **Visual:** High contrast colors, large clear fonts, simple navigation
- **Audio:** Voice feedback on all interactions, adjustable speech settings
- **Motor:** Large touch targets, forgiving interactions, no precision required
- **Cognitive:** Consistent patterns, clear visual hierarchy, minimal distractions

### **Evidence-Based Features:**
Research-backed tools from:
- AAC (Augmentative and Alternative Communication) research
- Speech-language pathology best practices
- Applied Behavior Analysis (ABA) strategies
- Occupational therapy recommendations
- Special education methodologies

### **User-Centered Design:**
- **Designed for motor skill challenges** - Extra-large tap targets
- **Forgiving interactions** - Can't make mistakes
- **Positive reinforcement** - Celebrations and rewards for all actions
- **Customizable** - Adjust to individual sensory needs
- **Predictable** - Consistent behavior across all features

---

## 📊 Technical Specifications

### **Browser APIs Used:**
- **Web Speech API** - Text-to-speech for voice output across all features
- **MediaRecorder API** - Voice recording in Voice Recorder feature
- **Canvas API** - Drawing in Art Board, graphics in games
- **LocalStorage API** - Persistent settings and voice recordings
- **Touch Events API** - Tablet and mobile interaction
- **Audio Context API** - Sound generation in Sound Explorer
- **Fullscreen API** - Immersive mode support

### **Responsive Breakpoints:**
- **Mobile:** < 768px (portrait phones)
- **Tablet:** 768px - 1024px (iPads, Android tablets)
- **Desktop:** > 1024px (computers, large tablets)

### **Performance Targets:**
- **Initial Load:** < 2 seconds on 4G connection
- **Feature Load:** < 0.5 seconds
- **Touch Response:** < 100ms (imperceptible lag)
- **Animation Frame Rate:** 60fps
- **Total File Size:** ~2MB for all pages combined

### **Accessibility Standards:**
- Large touch targets (44px minimum)
- Color contrast ratio > 4.5:1
- Font size minimum 16px (adjustable to 32px)
- Semantic HTML structure
- Keyboard navigation support
- Screen reader compatible

---

## 🔒 Privacy & Data Security

### **Local-Only Storage:**
- **All data stored locally** on device browser storage
- **No external servers** - data never leaves the device
- **No tracking** - zero analytics or monitoring
- **No accounts** - completely anonymous use
- **No cookies** - except browser essential cookies

### **What's Stored Locally:**
- App settings (voice speed, text size, color themes)
- Voice recordings (only in browser localStorage)
- Token board progress
- Visual schedule data
- Art board saved images
- User preferences

### **Data Removal:**
To completely remove all stored data:
1. Clear browser data (Settings → Privacy → Clear browsing data)
2. Or delete browser app and reinstall
3. Or use Settings page → Reset All Settings button

### **Microphone Privacy:**
- Voice Recorder requests microphone permission
- Permission prompt appears first time feature is used
- Can revoke permission in browser settings anytime
- Recordings stored locally only, never uploaded

---

## 🆘 Troubleshooting Guide

### **Voice not working:**
**Symptoms:** No speech when tapping buttons
**Solutions:**
1. Check device volume is turned up
2. Test with [Browser Compatibility Checker](https://benwah81.github.io/Kaidens-World/browser-check.html)
3. Refresh the page (swipe down or press reload button)
4. Check browser has permission for audio
5. Try a different browser (Safari on iOS, Chrome on Android)
6. Update browser to latest version

### **Microphone not working:**
**Symptoms:** Voice Recorder can't record
**Solutions:**
1. Allow microphone permission when browser prompts (critical!)
2. Check device microphone in another app (test in voice memos)
3. Check browser settings: Settings → Safari/Chrome → Microphone → Allow
4. Try a different browser
5. Check device microphone isn't physically blocked/damaged

### **Touch not responding:**
**Symptoms:** Buttons don't respond to taps
**Solutions:**
1. Clean tablet screen thoroughly
2. Remove screen protector if damaged or bubbling
3. Restart browser app (close completely and reopen)
4. Restart tablet device
5. Check for tablet software updates
6. Try different finger/hand if one isn't responding

### **Features won't load:**
**Symptoms:** Blank page or spinning loader
**Solutions:**
1. Check WiFi connection is stable
2. Refresh the page (swipe down or press reload)
3. Clear browser cache: Settings → Safari/Chrome → Clear Cache
4. Try a different browser
5. Check website address is correct (no typos)
6. Try on different device to isolate issue

### **App seems slow or laggy:**
**Symptoms:** Animations stutter, buttons delayed
**Solutions:**
1. Close other apps running in background
2. Restart browser
3. Restart tablet
4. Check WiFi speed (slow internet can affect loading)
5. Reduce screen brightness (can improve performance)
6. Update tablet OS to latest version

### **Saved data disappeared:**
**Symptoms:** Lost recordings, settings reset
**Solutions:**
1. Check if using same browser (data is browser-specific)
2. Don't clear browser data/cache if you want to keep recordings
3. Check Settings → Voice recordings are still there
4. Settings persist per browser, not per device
5. Consider backing up important recordings (play and record elsewhere)

---

## 📚 Documentation & Resources

### **Complete Documentation:**
- **[README.md](README.md)** - This file - complete project overview
- **[TABLET-TESTING-CHECKLIST.md](TABLET-TESTING-CHECKLIST.md)** - Comprehensive QA checklist for all 17 features
- **[TABLET-ACCESS-GUIDE.md](TABLET-ACCESS-GUIDE.md)** - Step-by-step setup instructions for different devices
- **[Browser Check Tool](https://benwah81.github.io/Kaidens-World/browser-check.html)** - Automated compatibility testing

### **Quick Reference:**
**Live App:** https://benwah81.github.io/Kaidens-World/
**Browser Check:** https://benwah81.github.io/Kaidens-World/browser-check.html
**GitHub Repository:** https://github.com/Benwah81/Kaidens-World

### **Support:**
For technical issues or questions:
1. Check troubleshooting section above
2. Review documentation files
3. Open a GitHub issue with details
4. Include device type, browser, and feature with issue

---

## 📜 License & Usage

**Open Source - Personal, Educational, and Therapeutic Use**

This project is freely available for:
- Personal use by families
- Educational use in schools
- Therapeutic use by speech therapists
- Research and study
- Adaptation for similar projects

**Attribution:**
While not required, attribution is appreciated if you use or adapt this project.

**No Warranty:**
This software is provided "as is" without warranty of any kind. Use at your own discretion.

---

## 💙 Acknowledgments

This application was created with love for Kaiden and all children who communicate differently.

**Special Thanks To:**
- **Speech-language pathologists** for AAC research and methodologies
- **The assistive technology community** for sharing best practices
- **Open source developers** for tools and inspiration
- **Families navigating communication challenges** for their strength and perseverance
- **Therapists and educators** who work tirelessly to help children communicate

**Inspiration:**
Every child deserves to be heard. This app is our contribution to making that possible.

---

## 🚀 Version History & Roadmap

### **Current Version: 1.0.0 (November 2025)**
✅ **17 Complete Features:**
- 6 Core Communication Tools
- 4 Learning & Development Features
- 4 Structure & Planning Tools
- 2 Behavioral & Emotional Support Features
- 1 Configuration System

✅ **Infrastructure:**
- Full tablet optimization (tap-based, no drag-and-drop)
- Browser compatibility checker
- Comprehensive documentation (3 guides)
- GitHub Pages deployment
- Modular standalone architecture

### **What's Working Great:**
- Touch interactions are smooth and responsive
- Voice feedback is clear and customizable
- All features are completely standalone
- Zero dependencies (pure vanilla JS)
- Works offline after first load
- No accounts or tracking

### **Future Enhancements Being Considered:**
*Based on therapeutic research and user feedback*
- Additional evidence-based AAC features
- More social stories for common situations
- Expanded communication scripts
- Additional sensory-based activities
- Parent/therapist dashboard for tracking progress
- Multi-language support
- Custom activity creation tools
- Import/export settings capability

---

## 📞 Quick Links

### **Essential Links:**
- **🌐 Live Application:** https://benwah81.github.io/Kaidens-World/
- **🔍 Browser Compatibility Checker:** https://benwah81.github.io/Kaidens-World/browser-check.html
- **📁 GitHub Repository:** https://github.com/Benwah81/Kaidens-World
- **📋 Testing Checklist:** [TABLET-TESTING-CHECKLIST.md](TABLET-TESTING-CHECKLIST.md)
- **📱 Setup Guide:** [TABLET-ACCESS-GUIDE.md](TABLET-ACCESS-GUIDE.md)

### **Direct Feature Links:**
All features accessible from main page, or direct links:
- https://benwah81.github.io/Kaidens-World/choice-board.html
- https://benwah81.github.io/Kaidens-World/sound-explorer.html
- https://benwah81.github.io/Kaidens-World/visual-schedule.html
- *(and 14 more - see index.html for complete list)*

---

## 💬 Contact & Feedback

**Found a bug?** Open a GitHub issue with:
- Device type (iPad Pro, Android tablet, etc.)
- Browser and version
- Feature where issue occurred
- Steps to reproduce

**Have a suggestion?** Open a GitHub issue with:
- Feature description
- Therapeutic value/reasoning
- Target age group
- Similar features in professional tools

**Want to contribute?** Review contributing guidelines in developer section above.

---

## 🎊 Ready to Use!

**Quick Start (1 minute):**
1. Open tablet browser
2. Go to: https://benwah81.github.io/Kaidens-World/
3. Allow microphone when prompted (for Voice Recorder)
4. Tap any feature to begin
5. ✅ Start communicating!

**For Best Experience:**
- Add to home screen (feels like native app)
- Adjust settings for your child's needs
- Start with Choice Board or Sound Explorer
- Use daily for consistent progress

---

**Built with ❤️ for Kaiden and all children who deserve to be heard.**

*Every tap is a voice. Every choice is progress. Every child deserves to communicate.*

---

*Last Updated: November 2025*
*Version 1.0.0 - 17 Features - Fully Tablet Optimized*
*No frameworks • No tracking • No cost • Just communication*
