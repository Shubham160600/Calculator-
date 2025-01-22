# Calculator

A clean and functional calculator web application with keyboard support.

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Decimal point operations
- Clear and delete functionality
- Keyboard support
- Responsive design
- Error handling for division by zero

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Google Fonts (Roboto)
- Font Awesome icons

## Usage

### Mouse Controls
- Click number buttons (0-9) to input numbers
- Click operation buttons (+, −, ×, ÷) to perform calculations
- Click 'CLEAR' to reset the calculator
- Click 'DELETE' to remove the last digit
- Click '=' to see the result
- Click '.' to input decimal points

### Keyboard Controls
- Numbers (0-9) to input numbers
- Operators (+, -, *, /) for calculations
- Enter or = to evaluate
- Escape to clear
- Backspace to delete
- Decimal point (.) for decimals

## Design Features

- Modern, minimalist interface
- Color-coded buttons for different functions
- Responsive layout that works on various screen sizes
- Clear visual feedback for button interactions
- Two-line display showing current and previous operations

## Project Structure
```
calculator/
│
├── index.html
├── styles.css
└── script.js
```

## Color Scheme

The calculator uses a clean color palette with:
- Light background for better readability
- Distinct colors for clear (red) and delete (blue) buttons
- Hover and active states for button feedback
- High contrast for display text

## Technical Notes

- Results are rounded to 3 decimal places
- Division by zero is prevented with an error message
- Display supports word-wrap for large numbers
- Calculator maintains operation history in top display
