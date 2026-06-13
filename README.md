# Calculator App

---

## Description

A modern and fully functional web-based calculator application designed for performing basic and advanced mathematical calculations. This application provides a user-friendly interface with both mouse and keyboard input support, making it convenient for users to perform calculations in multiple ways.

The Calculator App combines a clean, intuitive design with robust functionality, featuring real-time calculation display, comprehensive error handling, and seamless keyboard integration. The application is built with modern web standards and provides instant feedback for all mathematical operations.

The primary objective of this project is to provide users with a reliable, accessible, and easy-to-use calculator tool that supports various input methods and delivers accurate mathematical results through an attractive and responsive interface.

---

## Technologies

The following technologies were utilized in the development of this application:

- **HTML5** - Semantic markup and calculator structure
- **CSS3** - Professional styling and responsive layout
- **JavaScript (ES6+)** - Mathematical computation and event handling

---

## Features

- **Basic Arithmetic Operations** - Addition, subtraction, multiplication, and division
- **Keyboard Support** - Full keyboard input for numbers and operations
- **Real-time Display** - Immediate feedback as values are entered
- **Error Handling** - Graceful handling of invalid calculations
- **Delete Function** - Remove last entered character with backspace button
- **Clear Function** - Reset calculator display completely
- **Decimal Support** - Perform calculations with decimal numbers
- **Responsive Design** - Works seamlessly on desktop and mobile devices

---

## Installation

Getting started with Calculator App is simple:

1. **Clone or download** this repository to your computer
2. **Navigate** to the project folder
3. **Open** the `index.html` file in any modern web browser

**No installation or dependencies required** — this is a standalone web application that runs entirely in your browser.

---

## Usage

Using the Calculator App is straightforward:

1. **Open** the calculator in your web browser
2. **Enter numbers** by clicking buttons or using keyboard
3. **Select operation** using operation buttons or keyboard
4. **View result** displayed in real-time on screen
5. **Press equals** to calculate final result
6. **Use controls** for clearing or deleting entries

---

## Button Reference

| Button | Symbol | Function |
|--------|--------|----------|
| **CE** | CE | Clear entire display |
| **C** | C | Clear display |
| **Delete** | ⌫ | Remove last entered character |
| **Divide** | ÷ | Division operation |
| **Multiply** | × | Multiplication operation |
| **Subtract** | − | Subtraction operation |
| **Add** | + | Addition operation |
| **Decimal** | . | Decimal point entry |
| **Equals** | = | Calculate result |
| **0-9** | 0-9 | Number entry |

---

## Keyboard Shortcuts

| Key | Function |
|-----|----------|
| **0-9** | Enter numbers |
| **+** | Addition operation |
| **-** | Subtraction operation |
| **\*** | Multiplication operation |
| **/** | Division operation |
| **.** | Decimal point |
| **Enter** | Calculate result |
| **Backspace** | Delete last character |
| **Escape** | Clear display |

---

## Supported Operations

The calculator supports the following mathematical operations:

- **Addition** - Add two or more numbers
- **Subtraction** - Subtract numbers
- **Multiplication** - Multiply numbers
- **Division** - Divide numbers
- **Decimal Calculations** - Work with decimal numbers
- **Chained Operations** - Perform multiple calculations sequentially

---

## How It Works

The Calculator App operates through the following process:

1. **Input Collection** - Numbers and operations are captured via buttons or keyboard
2. **Display Update** - Entered values appear in real-time on the display screen
3. **Operation Processing** - Mathematical operations are prepared for calculation
4. **Result Computation** - JavaScript evaluates the complete expression
5. **Error Management** - Invalid calculations display error message
6. **Output Display** - Result is shown on calculator display

---

## Technical Architecture

**Core Functions:**

### appendValue(value)
Appends entered value to the display:
- Accepts numbers (0-9), operators (+, -, *, /), and decimal point
- Updates display in real-time
- Supports both button and keyboard input

### clearDisplay()
Clears entire calculator display:
- Resets display to empty state
- Triggered by CE or Escape key

### deleteLast()
Removes last entered character:
- Slices off final character from display
- Triggered by backspace button or Backspace key

### calculate()
Evaluates the mathematical expression:
- Uses JavaScript eval() for computation
- Displays result or error message
- Handles invalid expressions gracefully

---

## Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | Latest | Fully Supported |
| Firefox | Latest | Fully Supported |
| Safari | Latest | Fully Supported |
| Edge | Latest | Fully Supported |

---

## Responsive Design

The calculator is optimized for all screen sizes:

- **Desktop** - Full-featured interface on larger screens
- **Tablet** - Touch-friendly button sizing for tablets
- **Mobile** - Optimized layout for smartphone displays
- **Flexible Grid** - Button layout adapts to viewport width
- **Touch Support** - Responsive to touch input on mobile devices

---

## Error Handling

The application includes comprehensive error management:

- **Invalid Expression** - Displays error message for malformed calculations
- **Division by Zero** - Handles edge case gracefully
- **Special Characters** - Filters out unsupported keyboard input
- **User Feedback** - Clear error messages guide users

---

## Input Validation

The calculator validates all user input:

- **Number Validation** - Only numeric input accepted for numbers
- **Operator Validation** - Only valid mathematical operators accepted
- **Expression Validation** - Complete expression checked before calculation
- **Character Filtering** - Unsupported characters ignored

---

## Performance Characteristics

- **Lightweight** - Minimal file sizes for fast loading
- **Instant Calculation** - Real-time mathematical computation
- **Low Memory Usage** - Efficient resource utilization
- **Smooth Interaction** - Responsive button and keyboard events
- **Fast Loading** - No dependencies or external resources

---

## Use Cases

- **Daily Calculations** - Quick mathematical computations
- **Financial Calculations** - Budget and expense calculations
- **Educational Purpose** - Learning basic mathematics
- **Work Calculations** - Professional numerical operations
- **Development Tool** - Debugging and testing calculations

---

## Customization Options

Users can customize the calculator by:

- Modifying CSS for different colors and themes
- Adding additional mathematical functions
- Changing button layout or symbols
- Adjusting keyboard shortcuts
- Enhancing visual design

---

## File Structure

```
CalculatorApp/
├── index.html    # Main calculator interface
├── css.css       # Styling and layout
└── test.js       # JavaScript functionality
```

---

## Advanced Features

The calculator can be extended with:

- Scientific calculator functions
- Calculation history tracking
- Memory functions (M+, M-, MR, MC)
- Keyboard numpad support
- Theme customization
- Display size adjustment

---

## Troubleshooting

**Calculator not responding:**
- Refresh the web page
- Check browser console for errors
- Verify JavaScript is enabled

**Keyboard input not working:**
- Ensure calculator window is focused
- Check that Num Lock is enabled for numpad
- Verify supported keyboard events

**Display showing error:**
- Check mathematical expression validity
- Verify no division by zero
- Ensure proper operator placement

---

## Browser Console

The application logs no errors under normal operation. If issues occur:
- Open browser developer tools (F12)
- Check Console tab for error messages
- Verify HTML and JavaScript file paths

---

## Author

Developed by İrfan Yiğit for efficient and accessible calculations

---

## License

This project is open source and available for educational and personal use.

---

## Future Enhancements

Planned improvements include:

- Scientific calculator mode
- Calculation history panel
- Advanced mathematical functions
- Memory storage capabilities
- Multiple theme options
- Touch gesture support
- Customizable keyboard layout
