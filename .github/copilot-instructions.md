# Copilot Instructions for Tugas Pola Angka

## Project Overview
This is an educational project for the "Layanan dan Aplikasi Internet" (Internet Application Services) course. The project demonstrates JavaScript programming skills through interactive number pattern visualizations.

## Project Structure
- **Main HTML File**: `Tugas  Layanan dan Aplikasi Internet_Bintang Arya_5024231058.html` - Contains all HTML, CSS, and JavaScript code in a single file
- **Assets**: `b201.png` - Logo image used for background animation

## Technologies Used
- Pure HTML5
- Vanilla JavaScript (ES6+)
- CSS3 with animations and responsive design
- No external frameworks or build tools

## Code Patterns

### Pattern 1: Triangle Numbers (Tugas 1)
- Function: `tugas1_segitigaAngka()`
- Creates a symmetric number triangle pattern (0 to 8 and back)
- Uses nested loops for spacing and number generation

### Pattern 2: Pascal's Triangle (Tugas 2)
- Function: `tugas2_segitigaPascal()`
- Generates a 15-row Pascal's triangle
- Uses dynamic programming approach with 2D array

### Pattern 3: Matrix Infection Animation (Tugas 3)
- Functions: `generateOriginalMatrix()`, `tugas3_efekInfeksi()`, `updateInfection()`
- Creates an animated effect showing "infection" spreading through a number matrix
- Uses emojis (🧟, ☠️, ☣️, 🤖) to represent infected cells
- Updates every 500ms using `setInterval()`

## Coding Standards

### JavaScript Style
- Use camelCase for function names and variables
- Prefer `const` and `let` over `var`
- Use arrow functions for callbacks where appropriate
- Keep functions focused and single-purpose

### HTML/CSS Style
- Maintain consistent indentation (4 spaces)
- Use semantic HTML where possible
- Keep styles organized by component
- Use CSS variables for colors and repeated values when refactoring

### Animation Guidelines
- Use CSS animations for visual effects (not JavaScript when possible)
- Keep animation durations reasonable (not too fast or slow)
- Ensure animations don't cause performance issues

## Common Tasks

### Adding New Patterns
1. Create a new function following the naming convention `tugasN_patternName()`
2. Add a new `pattern-container` div in the HTML
3. Initialize and update the output in the `window.onload` function

### Modifying Styling
- Background color: `#111` (dark)
- Primary color: `#FFD700` (gold)
- Use rgba with low opacity for overlay effects
- Maintain consistent border-radius and padding

### Performance Considerations
- Be mindful of matrix size (currently 20x10)
- Avoid excessive DOM updates
- Use `innerHTML` sparingly, prefer `textContent` when possible
- Consider animation frame rate for smooth performance

## Testing Approach
Since this is a visual demonstration project:
1. Open the HTML file in a browser
2. Verify all three patterns display correctly
3. Check that Pattern 3 animation runs smoothly
4. Test responsive design on different screen sizes
5. Verify background logo animation works properly

## Language and Documentation
- Comments can be in Indonesian (Bahasa Indonesia) as this is an Indonesian university project
- Variable names should be descriptive and in English or Indonesian
- The target audience is Indonesian students and instructors

## Best Practices
- Keep all code in the single HTML file (as per project structure)
- Maintain readability with proper spacing and comments
- Test cross-browser compatibility (Chrome, Firefox, Safari, Edge)
- Ensure mobile responsiveness
- Optimize images before adding them to the repository
