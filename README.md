# IoT Device Knowledge Hub

A comprehensive educational platform for learning IoT microcontrollers including **ESP32**, **Raspberry Pi**, and **Arduino**. This website provides detailed guides, tutorials, and practical examples for beginners and intermediate developers.

## 🌟 Features

### ✨ User Experience
- **Dark Mode Support**: Toggle between light and dark themes with persistent storage
- **Search Functionality**: Quick search to find specific devices and guides
- **Responsive Design**: Fully responsive layout for desktop, tablet, and mobile devices
- **Smooth Animations**: Professional transitions and hover effects
- **Sticky Navigation**: Easy access to navigation from any page

### 📚 Content
- **ESP32 Full Guide**: GPIO pinout, WiFi connectivity, Bluetooth communication
- **Raspberry Pi Guide**: System architecture, GPIO control, Python programming
- **Arduino Guide**: Microcontroller programming, sensors, and projects
- **Code Examples**: Copy-paste ready code snippets with syntax highlighting
- **Best Practices**: Tips and warnings for safe and effective development

### 🔧 Technical Features
- **SEO Optimized**: Meta tags, Open Graph, and structured data
- **Fast Loading**: Optimized images and minimal CSS/JS
- **Accessibility**: Semantic HTML and keyboard navigation
- **Cross-browser**: Works on all modern browsers
- **Mobile First**: Optimized mobile experience

## 📁 File Structure

```
IoT-Knowledge-Hub/
├── index.html              # Main landing page with device cards
├── esp32_details.html      # ESP32 comprehensive guide
├── raspberry_details.html  # Raspberry Pi comprehensive guide
├── arduino_details.html    # Arduino comprehensive guide
├── esp32.webp              # ESP32 device image
├── raspberry.webp          # Raspberry Pi device image
└── README.md               # This file
```

## 🚀 Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/heinzarni04-source/IoT-Knowledge-Hub.git
   cd IoT-Knowledge-Hub
   ```

2. Open in your browser:
   - Simply open `index.html` in any modern web browser
   - Or use a local server:
     ```bash
     python3 -m http.server 8000
     # Then visit http://localhost:8000
     ```

### Deployment
The project is deployed on **Vercel** at: https://iot-knowledge-hub.vercel.app/

To deploy your own version:
1. Push to GitHub
2. Connect to Vercel
3. Deploy automatically on push

## 🎨 Customization

### Changing Colors
Edit the CSS variables in each HTML file:
```css
:root {
    --primary: #2563eb;      /* Main color */
    --secondary: #10b981;    /* Accent color */
    --dark: #0f172a;         /* Dark background */
    --light: #f8fafc;        /* Light background */
}
```

### Adding New Devices
1. Create a new `device_details.html` file
2. Add a new card to `index.html`:
   ```html
   <div class="device-card" data-device="device-name">
       <img src="device.webp" alt="Device Name" class="device-photo">
       <div class="content">
           <span class="tag">DEVICE • Category</span>
           <h3>Device Title</h3>
           <p class="details">Description...</p>
           <div class="btn-group">
               <a href="device_details.html" class="btn btn-primary">Full Guide</a>
               <a href="device_details.html" class="btn btn-dark">Learn More</a>
           </div>
       </div>
   </div>
   ```

### Updating Search
The search functionality automatically indexes device names. To add more searchable items, update the `devices` array in `index.html`:
```javascript
const devices = [
    { name: 'Device Name', keyword: 'keyword', link: 'device_details.html' },
    // Add more devices...
];
```

## 📖 Content Guidelines

### Code Examples
- Use clear, commented code
- Include both simple and advanced examples
- Provide copy buttons for easy use
- Test all code before publishing

### Documentation
- Write in simple, clear language
- Include diagrams and visual aids
- Provide step-by-step instructions
- Add warnings for common mistakes

### SEO Best Practices
- Use descriptive titles and meta descriptions
- Include relevant keywords naturally
- Use heading hierarchy (H1, H2, H3)
- Add alt text to all images

## 🔗 External Resources

- [ESP32 Official Documentation](https://docs.espressif.com/projects/esp-idf/en/latest/)
- [Raspberry Pi Official Website](https://www.raspberrypi.com/)
- [Arduino Official Website](https://www.arduino.cc/)
- [Cirkit Designer](https://app.cirkitdesigner.com/)

## 💡 Tips for Contributors

1. **Code Quality**: Follow consistent naming conventions and formatting
2. **Testing**: Test on multiple devices and browsers
3. **Documentation**: Add comments and explanations
4. **Performance**: Optimize images and minimize CSS/JS
5. **Accessibility**: Ensure keyboard navigation and screen reader support

## 🎓 Learning Path

### Beginners
1. Start with **Arduino** for basic concepts
2. Move to **ESP32** for WiFi/Bluetooth
3. Explore **Raspberry Pi** for advanced projects

### Intermediate
1. Combine multiple devices
2. Build IoT systems
3. Integrate with cloud services

### Advanced
1. Create custom hardware
2. Develop IoT applications
3. Contribute to open source

## 📞 Contact & Support

- **Email**: heinzarni04@gmail.com
- **Phone**: +95 926 493 7374
- **GitHub**: [heinzarni04-source](https://github.com/heinzarni04-source)

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Created by **Hein** for IoT education
- Inspired by the IoT community
- Built with modern web technologies

## 🔄 Version History

### v2.0 (Current)
- ✨ Added Dark Mode support
- 🔍 Implemented Search functionality
- 📱 Enhanced responsive design
- 🎨 Improved UI/UX
- 📚 Added Raspberry Pi and Arduino guides
- 🚀 Better performance and SEO

### v1.0
- Initial release with ESP32 guide
- Basic device card layout
- Contact modal

## 🚀 Future Enhancements

- [ ] Add more microcontroller guides (STM32, PIC, etc.)
- [ ] Interactive circuit simulator
- [ ] Video tutorials
- [ ] Community forum
- [ ] Project showcase gallery
- [ ] Code playground/IDE
- [ ] Mobile app
- [ ] Multi-language support

---

**Happy Learning! 🎉**

For questions or suggestions, please reach out via the contact form on the website.
