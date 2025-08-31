# Screenshot for this project


# Mechanical Form Animation

A captivating interactive form with mechanical animations powered by GSAP (GreenSock Animation Platform). This project combines form validation with a visually engaging mechanical system that responds to user input.

## Features

- **Interactive Form Elements**: Name and email inputs with real-time validation
- **Mechanical Animations**: 
  - Gear systems that activate upon valid input
  - Spray mechanism that responds to email validation
  - Pull system for checkbox interaction
  - Hand animations that change based on form state
- **Visual Feedback**: Animations provide clear visual cues for form validation states
- **Responsive Design**: Scales to fit different screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- GSAP (GreenSock Animation Platform) v3.12.2
- SVG for all mechanical elements

## How It Works

1. **Name Input**: 
   - Requires at least 4 characters
   - Activates gear animations when valid
   - Deactivates gears when invalid

2. **Email Input**:
   - Validates email format using regex
   - Triggers hammer mechanism and hand animations when valid
   - Reverses animations when invalid

3. **Checkbox**:
   - Controls pull system animation
   - Affects submit button positioning

4. **Submit Button**:
   - Only enabled when all fields are valid
   - Fades in after multiple spray cycles
   - Triggers final animation sequence when clicked

## Project Structure

```
/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── (no external dependencies except GSAP CDN)
```

## Setup and Usage

1. Simply open `index.html` in a modern web browser
2. No build process or additional dependencies required
3. The animation uses GSAP loaded from CDN

## Browser Compatibility

- Modern browsers with ES6+ support
- SVG support required
- CSS Transform support required

## Customization

The animation parameters can be modified in the JavaScript section:
- Gear speeds and sizes
- Animation timings
- Validation criteria
- Visual elements colors and sizes

## Develop

Create by Jerhan, This project is provided as-is for educational and demonstration purposes.