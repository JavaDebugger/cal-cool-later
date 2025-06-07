# Divide & Conquer Calculator

<div align="center">
  <img src="public/images/main-logo-use.svg" alt="Divide & Conquer Calculator" width="120" height="120">
  <h3>A Modern, Feature-Rich Calculator with Advanced Mathematical Functions</h3>
</div>

## 📖 Project Description

**Divide & Conquer Calculator** is a sophisticated web-based calculator application that combines traditional arithmetic operations with specialized mathematical functions. Built with a modern 2.5D metallic design aesthetic, this calculator offers an intuitive user experience across all devices.

### ✨ Key Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Special Mathematical Functions**:
  - **Length & Breadth (L/B)**: Calculate rectangular areas
  - **Circumference (C)**: Convert circumference to radius
  - **Area to Radius (A)**: Convert circular area to radius
- **Advanced User Interface**:
  - Responsive 2.5D metallic styling with interactive hover effects
  - Toast notifications for user feedback
  - Modal interfaces for history and help
  - Smooth slide animations and visual transitions
- **Comprehensive Input Methods**:
  - Full keyboard support (including numpad)
  - Mobile touch gestures (long press, double tap)
  - Cross-platform keyboard layout compatibility
- **Smart Features**:
  - Calculation history with local storage
  - Visual button highlighting for keyboard input
  - Error handling with user-friendly messages
  - Responsive design for mobile, tablet, and desktop

## 🚀 Installation & Usage

### Quick Start
1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. Start calculating immediately - no installation required!

### Browser Compatibility
- **Recommended**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Mobile**: iOS Safari 14+, Chrome Mobile 90+
- **Features**: Supports modern CSS Grid, Flexbox, and ES6+ JavaScript

## ⌨️ Keyboard Shortcuts & Button Mapping

### Basic Input
- **Numbers (0-9)**: Type any number key or use Numpad0-9
- **Decimal Point (.)**: Period key or NumpadDecimal
- **Operators**: `+` `-` `*` `/` (also supports numpad operators)

### Functions
- **Calculate**: `Enter` or `NumpadEnter`
- **Clear**: `Escape` or `C`
- **Backspace**: `Backspace` (deletes last digit)

### Special Functions
- **Length (L)**: Set length value for area calculation
- **Breadth (B)**: Set breadth value for area calculation
- **Circumference (C)**: Convert circumference to radius
- **Area to Radius (A)**: Convert circular area to radius

### Navigation
- **History Modal**: `H` key
- **Help Modal**: `Ctrl + ?` or `Shift + /`
- **Close Modals**: `Escape`

### Mobile Touch Alternatives
- **Help Modal**: Long press help icon (800ms)
- **History Modal**: Double tap calculator display
- **Visual Feedback**: Button highlighting and toast notifications

## 🤝 Contributors

We extend our gratitude to the following organizations for their contributions to this project:

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <img src="public/images/contributor1-logo.svg" alt="IT Varsity" width="100" height="100">
        <br>
        <strong>IT Varsity</strong>
      </td>
      <td align="center" width="50%">
        <img src="public/images/contributor2-logo.svg" alt="FNB App Academy" width="100" height="100">
        <br>
        <strong>FNB App Academy</strong>
      </td>
    </tr>
  </table>
</div>

## 👨‍💻 Developer Information

<div align="center">
  <img src="public/images/nanitech-logo.svg" alt="NaniTech Logo" width="120" height="120">
  <br>
  <h3>Project Phaki Krwele</h3>
  <p><strong>Development Company:</strong> NaniTech</p>
</div>

### About the Project
**Project Phaki Krwele** represents our commitment to creating innovative, user-friendly mathematical tools. Developed by **NaniTech**, this calculator showcases modern web development practices combined with intuitive design principles.

### Development Philosophy
- **User-Centric Design**: Every feature is designed with the end-user experience in mind
- **Responsive Excellence**: Seamless functionality across all devices and screen sizes
- **Accessibility First**: Comprehensive keyboard support and mobile touch alternatives
- **Performance Optimized**: Lightweight, fast-loading, and efficient code architecture

## 🛠️ Technical Documentation

### File Structure
```
divide-and-conquer-calculator/
├── index.html                 # Main application file
├── README.md                  # Project documentation
├── KEYBOARD_MAPPING_DOCUMENTATION.md  # Detailed keyboard mapping
└── public/
    └── images/
        ├── main-logo-use.svg      # Main application logo
        ├── nanitech-logo.svg      # Developer company logo
        ├── contributor1-logo.svg  # IT Varsity logo
        └── contributor2-logo.svg  # FNB App Academy logo
```

### Dependencies
- **No External Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript
- **Local Storage**: For calculation history persistence
- **SVG Graphics**: Scalable vector graphics for logos and icons

### Features Implementation

#### 🎨 2.5D Metallic Design
- **CSS Gradients**: Multi-layer gradients for metallic appearance
- **Box Shadows**: Inset and outset shadows for depth effect
- **Hover Effects**: Interactive 3D tilt animations
- **Border Radius**: Consistent rounded corners throughout

#### 📱 Responsive Design
- **CSS Grid**: Modern layout system for button arrangement
- **Flexbox**: Flexible container layouts
- **Clamp() Functions**: Fluid typography and spacing
- **Media Queries**: Breakpoints for mobile (480px), tablet (768px), desktop (1024px+)

#### 🔔 Toast Notification System
- **Position**: Bottom-center relative to calculator
- **Types**: Success, error, and info notifications
- **Animation**: Slide-up entrance with fade effects
- **Auto-dismiss**: Configurable duration with manual dismiss option

#### 📊 Modal Interfaces
- **History Modal**: Displays last 50 calculations with timestamps
- **Help Modal**: Comprehensive user guide and keyboard shortcuts
- **Animations**: Smooth slide-in/out transitions
- **Accessibility**: Focus management and keyboard navigation

### Browser Support
| Feature | Chrome | Firefox | Safari | Edge |
|---------|--------|---------|--------|------|
| CSS Grid | 57+ | 52+ | 10.1+ | 16+ |
| CSS Clamp | 79+ | 75+ | 13.1+ | 79+ |
| Local Storage | 4+ | 3.5+ | 4+ | 8+ |
| Touch Events | 22+ | 52+ | 3.2+ | 12+ |

## 🚀 Getting Started

### For Users
1. **Open the Calculator**: Simply open `index.html` in your web browser
2. **Start Calculating**: Use mouse clicks, keyboard input, or touch gestures
3. **Explore Features**: Try the special functions (L, B, C, A) and keyboard shortcuts
4. **View History**: Press 'H' or click the History button to see past calculations
5. **Get Help**: Press 'Ctrl+?' or click the '?' button for detailed help

### For Developers
1. **Clone Repository**: `git clone [repository-url]`
2. **Open in Editor**: Use any code editor (VS Code, Sublime Text, etc.)
3. **Live Server**: Use a local development server for testing
4. **Customize**: Modify CSS for styling, JavaScript for functionality
5. **Test**: Verify across different browsers and devices

## 📋 Usage Examples

### Basic Arithmetic
```
Input: 15 + 25 * 2
Output: 15 + 25 * 2 = 65
```

### Area Calculation
```
Input: 10 L 5 B
Output: 10 L 5 B = 50 sq m
```

### Circumference to Radius
```
Input: 31.4 C
Output: 31.4 C = 5 r
```

### Area to Radius
```
Input: 78.5 A
Output: 78.5 A = 5 r
```

## 🔧 Customization

### Styling
- **Colors**: Modify CSS custom properties for theme changes
- **Fonts**: Update font families in CSS for different typography
- **Animations**: Adjust transition durations and easing functions
- **Layout**: Modify grid templates for different button arrangements

### Functionality
- **Add Operations**: Extend the `calculate()` function for new operations
- **Keyboard Mapping**: Update event listeners for additional shortcuts
- **Storage**: Modify localStorage implementation for different data persistence
- **Validation**: Enhance input validation for specific use cases

## 📄 License

This project is developed as part of **Project Phaki Krwele** by **NaniTech**. All rights reserved.

## 🤝 Contributing

We welcome contributions from the community! Please feel free to:
- Report bugs and issues
- Suggest new features
- Submit pull requests
- Improve documentation

---

<div align="center">
  <p><strong>Divide & Conquer Calculator</strong> - Making Mathematics Accessible and Beautiful</p>
  <p>Developed with ❤️ by <strong>NaniTech</strong></p>
</div>
