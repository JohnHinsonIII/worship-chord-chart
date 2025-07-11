# worship-chord-chart
Worship Chord Chart
# 🎹 Worship Chord Chart - Keyboard Accompaniment Flow #1

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge)](https://yourusername.github.io/worship-chord-chart)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

An interactive, responsive web application designed for worship musicians to learn and practice keyboard accompaniment patterns. Features a dynamic progression builder with visual piano keyboards and color-coded fingering patterns.

![Worship Chord Chart Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=Worship+Chord+Chart+Preview)

## ✨ Features

### 🎵 **Core Functionality**
- **8-Position Chord Progression**: Complete 1 - 2m - 1/3 - 4 - 5 - 6m - 5/7 - 1 pattern
- **Interactive Piano Keyboards**: Visual representation with color-coded hand positions
- **Dynamic Progression Builder**: Create custom chord sequences with stacked keyboards
- **Real-time Fingering Display**: Instant visual feedback for left and right hand positions

### 🎹 **Piano Keyboard Features**
- **Color-Coded Hand Positions**:
  - 🔵 Blue: Left hand notes
  - 🔴 Red: Right hand notes  
  - 🟣 Purple: Both hands
- **Note Labels**: Every key shows its note name
- **Responsive Scaling**: Adapts to screen size (mobile to desktop)
- **3+ Octave Range**: Complete fingering patterns from C3 to C6

### 🚀 **Dynamic Progression Builder**
- **Click to Add**: Select any chord to add to your custom progression
- **Stacked Keyboards**: Each selected chord displays with its own piano keyboard
- **Visual Sequence**: See your chord progression with numbered sequence
- **Play Feature**: Highlight progression sequence with timing
- **Easy Management**: Remove individual chords or clear entire progression

### 📱 **Responsive Design**
- **Mobile (< 480px)**: 2-column chord grid, touch-optimized controls
- **Tablet (481-768px)**: 4-column layout with medium elements
- **Desktop (769-1024px)**: 8-column grid with side-by-side panels
- **Large Screens (1025px+)**: Expanded layout with optimal spacing

## 🎯 Chord Progressions Included

### Key of C Major - Complete Fingering Patterns

| Position | Chord | Roman | Type | Formula | Left Hand | Right Hand | Description |
|----------|-------|-------|------|---------|-----------|------------|-------------|
| **I** | C | I | Major | 1.3.5 | C3 | C4-E4-G4 | Major triad - tonic |
| **ii** | C4/D | ii | Minor11 | 1.4.5 | D3 | C4-F4-G4 | Minor with 11th |
| **I/3** | C/E | I/3 | Major | 1.3.5 | E3 | C4-E4-G4 | Major with 3rd in bass |
| **IV** | C4/F | IV | SUS2 | 1.4.5 | F3 | C4-F4-G4 | Suspended 2nd |
| **V** | C2/G | V | SUS4 | 1.2.5 | G3 | C4-D4-G4 | Suspended 4th |
| **vi** | C/Am | vi | Minor7 | 1.3.5 | A3 | C4-E4-G4 | Minor 7th |
| **V/7** | G/B | V/7 | Add11/7th | 1.2.5 | B3 | C4-D4-G4 | Add 11th with 7th in bass |
| **I** | C | I | Major | 1.3.5 | C3 | C4-E4-G4 | Resolution to tonic |

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Visit the live application: **[https://yourusername.github.io/worship-chord-chart](https://yourusername.github.io/worship-chord-chart)**

### Option 2: Download and Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/worship-chord-chart.git

# Navigate to the directory
cd worship-chord-chart

# Open index.html in your browser
# Or start a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📖 How to Use

### 1. **Basic Chord Selection**
- Click any of the 8 chord boxes to view detailed fingering
- Selected chord appears in dark theme with piano keyboard below
- View complete chord analysis including formula and hand positions

### 2. **Building Custom Progressions**
- Click chord boxes to add them to your custom progression
- Chords turn green when added to progression
- Each chord appears with its own piano keyboard in the progression section
- Remove chords by clicking the ❌ button on progression chips

### 3. **Playing Your Progression**
- Use the **▶️ Play Sequence** button to highlight each chord in order
- Each chord is highlighted for 1.5 seconds with visual effects
- Auto-scroll keeps the current chord in view

### 4. **Keyboard Shortcuts**
- **Numbers 1-8**: Quick select specific chords
- **Escape**: Deselect current chord
- **Ctrl/Cmd + P**: Play progression sequence
- **Ctrl/Cmd + C**: Clear entire progression

## 🎨 Design Features

### **Visual Design System**
- **Glass Morphism**: Modern frosted glass effect with backdrop blur
- **Gradient Backgrounds**: Purple-to-blue atmospheric gradient
- **Smooth Animations**: Hover effects and transitions throughout
- **Color Psychology**: Intuitive color coding for different functions

### **Accessibility Features**
- **ARIA Labels**: Screen reader compatible
- **Keyboard Navigation**: Full keyboard control support
- **Touch Optimized**: 44px minimum touch targets
- **High Contrast**: Clear visual hierarchy and readability

## 🔧 Technical Details

### **Technologies Used**
- **HTML5**: Semantic structure and modern web standards
- **CSS3**: Grid, Flexbox, Custom Properties, clamp() functions
- **Vanilla JavaScript**: No external dependencies
- **Responsive Design**: Mobile-first approach with breakpoints

### **Key Technical Features**
```javascript
// Core functionality includes:
- Dynamic DOM manipulation for progression building
- Responsive piano keyboard generation
- State management for multiple chord selections
- Touch and keyboard event handling
- Debounced resize handlers for performance
- CSS Grid and Flexbox for responsive layouts
```

### **Browser Compatibility**
- ✅ Chrome 88+
- ✅ Firefox 85+
- ✅ Safari 14+
- ✅ Edge 88+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Device Compatibility

| Device Type | Layout | Features |
|-------------|--------|----------|
| **📱 Mobile** | 2-column grid | Touch-optimized, auto-scroll |
| **📲 Tablet** | 4-column grid | Medium elements, gesture support |
| **💻 Desktop** | 8-column grid | Side-by-side panels, hover effects |
| **🖥️ Large Screen** | Expanded layout | Optimal spacing, full features |

## 🎵 Educational Value

### **For Worship Musicians**
- **Learn Proper Fingering**: Visual guide for keyboard accompaniment
- **Understand Chord Function**: Roman numeral analysis and chord relationships
- **Practice Progressions**: Build and practice custom chord sequences
- **Muscle Memory**: Repetitive visual and kinesthetic learning

### **For Music Teachers**
- **Visual Teaching Tool**: Show students exact finger positions
- **Progression Analysis**: Demonstrate chord function and relationships
- **Interactive Learning**: Engage students with hands-on exploration
- **Flexible Practice**: Create custom exercises for different skill levels

## 🚧 Future Enhancements

### **Planned Features**
- [ ] **All 12 Keys**: Transpose to any major key
- [ ] **Audio Playback**: MIDI or audio synthesis for chord sounds
- [ ] **Bass Guitar Tab**: Visual bass guitar fingering patterns
- [ ] **Export Options**: Save progressions as MIDI or chord charts
- [ ] **Additional Patterns**: More accompaniment styles and variations
- [ ] **Metronome**: Built-in timing for practice
- [ ] **Recording**: Save and playback custom progressions

### **Advanced Features**
- [ ] **Minor Key Progressions**: Relative minor and modal patterns
- [ ] **Jazz Extensions**: 7ths, 9ths, and altered chords
- [ ] **User Accounts**: Save personal progressions
- [ ] **Sharing**: Share chord progressions with others
- [ ] **Mobile App**: Native iOS/Android applications

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### **Ways to Contribute**
1. **Report Bugs**: Open an issue with detailed bug reports
2. **Suggest Features**: Share ideas for new functionality
3. **Improve Documentation**: Help make instructions clearer
4. **Code Contributions**: Submit pull requests for enhancements

### **Development Setup**
```bash
# Fork the repository
git clone https://github.com/yourusername/worship-chord-chart.git
cd worship-chord-chart

# Make your changes to index.html
# Test locally with a simple server
python -m http.server 8000

# Submit a pull request with your improvements
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### **MIT License Summary**
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ No warranty or liability

## 🙏 Acknowledgments

- **Worship Musicians**: For inspiring the need for better learning tools
- **Music Theory**: Based on standard keyboard accompaniment patterns
- **Web Technologies**: Built with modern web standards
- **Open Source Community**: For providing the foundation and inspiration

## 📞 Support

### **Getting Help**
- 📧 **Email**: [your.email@example.com](mailto:your.email@example.com)
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/yourusername/worship-chord-chart/issues)
- 💡 **Feature Requests**: [GitHub Discussions](https://github.com/yourusername/worship-chord-chart/discussions)
- 📖 **Documentation**: Check this README and code comments

### **FAQ**

**Q: Does this work offline?**
A: Yes! Once loaded, the application works completely offline.

**Q: Can I use this on mobile devices?**
A: Absolutely! The app is fully responsive and touch-optimized.

**Q: Are there plans for other keys?**
A: Yes, support for all 12 major keys is planned for future releases.

**Q: Can I contribute chord progressions?**
A: Yes! We welcome contributions of new patterns and progressions.

---

## 🌟 Star This Repository

If you find this project helpful, please consider giving it a star ⭐ to help others discover it!

---

**Made with ❤️ for the worship music community**

*Empowering musicians with visual learning tools for better worship experiences*
