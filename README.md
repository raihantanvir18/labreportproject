# On/Off Button HTML Page

A simple, interactive HTML page featuring a modern toggle switch button with smooth animations and visual feedback.

## Features

- **Modern Toggle Switch**: iOS-style toggle button design
- **Smooth Animations**: CSS transitions for button state changes
- **Visual Feedback**: Color changes and sliding animation
- **Status Display**: Real-time ON/OFF status text
- **Responsive Design**: Centered layout that works on all screen sizes
- **Clean UI**: Gradient background with modern card design

## File Structure

```
labreport12/
├── on-off-button.html    # Main HTML file with embedded CSS and JavaScript
└── README.md            # This documentation file
```

## How to Use

1. **Open the HTML file**:
   - Double-click `on-off-button.html` to open it in your default web browser
   - Or right-click and select "Open with" to choose a specific browser

2. **Interact with the button**:
   - Click the toggle switch to change between ON and OFF states
   - Watch the smooth sliding animation and color changes
   - Observe the status text update below the button

## Technical Details

### HTML Structure
- Simple container with a toggle button and status text
- Semantic HTML elements for accessibility

### CSS Features
- **Flexbox layout** for perfect centering
- **CSS transitions** for smooth animations
- **Gradient background** for visual appeal
- **Box shadows** for depth and modern look
- **Responsive design** principles

### JavaScript Functionality
- Toggle state management
- Dynamic class manipulation
- Real-time status updates

## Visual States

### OFF State
- Button background: Gray (#ccc)
- Slider position: Left side
- Status text: "OFF" in red color
- Status: `isOn = false`

### ON State
- Button background: Green (#4CAF50)
- Slider position: Right side
- Status text: "ON" in green color
- Status: `isOn = true`

## Browser Compatibility

This HTML page works in all modern web browsers including:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## Customization

You can easily customize the button by modifying the CSS variables:

- **Button size**: Change `width` and `height` in `.toggle-button`
- **Colors**: Modify background colors in `.toggle-button` and `.toggle-button.on`
- **Animation speed**: Adjust `transition` duration values
- **Button shape**: Modify `border-radius` for different roundness

## License

This project is open source and available under the MIT License.