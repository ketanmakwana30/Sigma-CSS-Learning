# Sigma-CSS-Learning
This is my CSS Learning Repository ! (Sigma 10 -MERN Stack Development)

## CSS Notes

### 1. What is CSS?
CSS (Cascading Style Sheets) is used to style and design a webpage — colors, layout, fonts, spacing, and overall appearance.

### 2. Why CSS is Important?
CSS makes web pages look attractive, responsive, and user-friendly.  
It separates **content (HTML)** and **styling (CSS)**, making code cleaner and easier to manage.

### 3. Ways to Apply CSS
- **Inline CSS** – Inside the HTML tag using the `style` attribute.  
- **Internal CSS** – Inside `<style>` tag in `<head>`.  
- **External CSS** – In a separate `.css` file (best method).

### 4. Selectors
Used to target HTML elements for styling.  
- Element selector → `p {}`  
- Class selector → `.title {}`  
- ID selector → `#main {}`  
- Universal selector → `* {}`  
- Attribute selector → `input[type="text"]`

### 5. Colors in CSS
You can apply colors using:  
- Color name → `red`  
- HEX → `#ff0000`  
- RGB → `rgb(255,0,0)`  
- HSL → `hsl(0, 100%, 50%)`

### 6. CSS Units
Used for size, spacing, fonts:  
- Absolute units → `px`  
- Relative units → `em`, `rem`  
- Viewport units → `vh`, `vw`  
- Percentage → `%`

### 7. Box Model
Every HTML element is a box with:  
- **Content**  
- **Padding**  
- **Border**  
- **Margin**  

### 8. Display Property
Controls how elements behave:  
- `block`  
- `inline`  
- `inline-block`  
- `none`

### 9. Position Property
Controls element placement:  
- `static`  
- `relative`  
- `absolute`  
- `fixed`  
- `sticky`

### 10. Flexbox
One-dimensional layout system used to align items easily.  
Useful properties:  
- `display: flex`  
- `justify-content`  
- `align-items`  
- `flex-direction`

### 11. CSS Grid
Two-dimensional layout system using rows and columns.  
Perfect for complex page layouts.

### 12. Typography
Controls text appearance:  
- `font-size`  
- `font-family`  
- `font-weight`  
- `line-height`  
- `letter-spacing`

### 13. Backgrounds
Used to add colors and images:  
- `background-color`  
- `background-image`  
- `background-size`  
- `background-repeat`

### 14. Transitions
Smooth changes between styles (hover animations).  
Example: `transition: all 0.3s ease;`

### 15. Transforms
Rotate, scale, move elements:  
- `transform: scale()`  
- `transform: rotate()`  
- `transform: translate()`

### 16. Animations (Keyframes)
Create full custom animations using `@keyframes`.

### 17. Responsive Design
Makes website fit all screens (mobile, tablet, desktop).  
Done using **media queries**:  
```css
@media (max-width: 600px) {
  body {
    background: lightblue;
  }
}
