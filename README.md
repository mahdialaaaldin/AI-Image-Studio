# AI Image Generator Pro 🎨

A modern, feature-rich AI image generator powered by Pollinations.ai. Create stunning AI-generated artwork with an intuitive interface, style presets, and advanced customization options.

<img width="879" height="623" alt="image" src="https://github.com/user-attachments/assets/5ec8bc75-6b20-4120-9aee-956f3318eb2d" />


## 🌟 Live Demo

[**Try it live here →**](https://mahdialaaaldin.github.io/AI-Image-Studio/)

## ✨ Features

### Core Features
- **🖼️ AI-Powered Image Generation** - Create unique images from text descriptions using Pollinations.ai
- **🎲 Smart Random Prompts** - Get creative AI-generated prompts or fallback to curated suggestions
- **🎨 Style Presets** - Quick access to popular styles:
  - Photorealistic
  - Digital Art
  - Oil Painting
  - Anime/Manga
  - Studio Ghibli
  - 3D Render

### Advanced Features
- **📐 Multiple Aspect Ratios** - Choose from 16:9, 9:16, 3:2, 2:3, or default square
- **🎯 Seed Control** - Use custom seeds for reproducible results
- **🔄 Smart Regeneration** - Automatically randomizes seed when regenerating with same prompt
- **💾 Download Images** - Save your creations with one click
- **📋 Copy Prompts** - Easily copy prompts to clipboard
- **📚 Generation History** - Access your last 12 creations
- **⌨️ Keyboard Shortcuts** - Press Enter to generate

### UI/UX Features
- **🌈 Modern Glassmorphism Design** - Beautiful gradient backgrounds with blur effects
- **✨ Smooth Animations** - Hover effects, transitions, and loading states
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **🔔 Smart Notifications** - Real-time feedback for user actions

## 🚀 Getting Started

### Option 1: Direct Use
Simply visit the [live demo](https://mahdialaaaldin.github.io/AI-Image-Studio/) and start generating!

### Option 2: Local Development
1. Clone the repository:
```bash
git clone https://github.com/mahdialaaaldin/AI-Image-Studio.git
cd AI-Image-Studio
```

2. Open `index.html` in your browser

## 💡 How to Use

1. **Enter a Prompt**: Describe the image you want to create
2. **Choose a Style** (Optional): Select from preset art styles
3. **Set Advanced Options** (Optional): Choose aspect ratio or set a seed
4. **Generate**: Click the generate button or press Enter
5. **Download/Share**: Save your creation or copy the prompt

### Pro Tips
- Leave the seed field empty to get different variations of the same prompt
- Click the 🎲 Random button for AI-generated creative prompts
- Use the inspiration suggestions for quick ideas
- Browse your history to revisit previous generations

## 🛠️ Technical Details

### Technologies Used
- **Frontend**: Pure HTML, CSS, JavaScript
- **Styling**: Tailwind CSS (via CDN)
- **API**: Pollinations.ai (Image & Text Generation)
- **Storage**: LocalStorage for history persistence

### API Endpoints
- Image Generation: `https://image.pollinations.ai/prompt/[prompt]`
- Text Generation: `https://text.pollinations.ai/[prompt]`

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📂 Project Structure
```
AI-Image-Studio/
├── index.html          # Main application file
├── README.md          # Documentation
└── LICENSE           # MIT License
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 🙏 Acknowledgments

- [Pollinations.ai](https://pollinations.ai/) for providing the AI generation API
- [Tailwind CSS](https://tailwindcss.com/) for the styling framework
- The open-source community for inspiration

## 📞 Contact

Created by [@mahdialaaaldin](https://github.com/mahdialaaaldin)

---

⭐ If you find this project useful, please consider giving it a star on GitHub!

---

# LICENSE

MIT License

Copyright (c) 2025 Mahdi Alaa Aldin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
