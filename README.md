# 🚀 AI Story Generator

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Nitzan94/ai-story-generator)

An AI-powered web application that transforms your images into captivating stories using Google's Gemini AI. Simply upload an image and watch as creativity unfolds before your eyes!

## ✨ Features

- 📸 **Image Upload**: Drag & drop or click to upload images
- 🤖 **AI Story Generation**: Powered by Google's Gemini AI
- 🎨 **Beautiful UI**: Modern design with purple/blue gradients
- 📱 **Responsive**: Works perfectly on mobile, tablet, and desktop
- ⚡ **Lightning Fast**: Generate stories in seconds
- 📋 **Copy to Clipboard**: Easy story sharing
- 🎭 **Smooth Animations**: Delightful user experience

## 🎯 How It Works

1. **Upload an Image** - Drag and drop or click to select an image
2. **Generate Story** - Our AI analyzes your image and creates a unique story
3. **Enjoy & Share** - Read your personalized story and copy it to share

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3 (Tailwind CSS), Vanilla JavaScript
- **AI**: Google Gemini API
- **Icons**: Lucide Icons
- **Fonts**: Inter (Google Fonts)
- **Deployment**: Vercel

## 🚀 Live Demo

[View Live Demo](https://ai-story-generator-nitzan94.vercel.app) *(Coming Soon)*

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nitzan94/ai-story-generator.git
   cd ai-story-generator
   ```

2. **Set up your Gemini API Key**
   - Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Replace the API key in `index.html` (line with `GEMINI_API_KEY`)

3. **Run locally**
   ```bash
   # Using Python
   python3 -m http.server 3000
   
   # Using Node.js
   npx serve .
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

## 🔑 API Configuration

To use this application, you'll need a Google Gemini API key:

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Replace the `GEMINI_API_KEY` variable in `index.html`

## 📱 Screenshots

### Desktop View
![Desktop View](https://via.placeholder.com/800x600/6366f1/ffffff?text=Desktop+View)

### Mobile View
![Mobile View](https://via.placeholder.com/400x800/8b5cf6/ffffff?text=Mobile+View)

## 🎨 Design System

- **Primary Colors**: Purple (`#6366f1`) to Blue (`#3b82f6`) gradient
- **Typography**: Inter font family
- **Spacing**: 8pt grid system
- **Border Radius**: Consistent rounded corners
- **Shadows**: Subtle elevation with purple tints

## 🌟 Features in Detail

### Image Upload
- Drag and drop functionality
- File validation (image types only)
- Size limits (max 10MB)
- Real-time preview with clear option

### AI Story Generation
- Hebrew language support
- Creative and engaging narratives
- 200-300 word stories
- Contextual analysis of image content

### User Experience
- Loading states with shimmer effects
- Success/error notifications
- Typing animation for story display
- Responsive design breakpoints

## 🔄 Development

### Project Structure
```
ai-story-generator/
├── index.html          # Main application file
├── README.md           # Project documentation
└── assets/             # Future assets directory
```

### Key Components
- **Upload Zone**: Handles image upload with drag & drop
- **Image Preview**: Shows uploaded image with clear option
- **Story Generator**: Connects to Gemini AI API
- **Story Display**: Shows generated story with typing effect
- **Copy Functionality**: Clipboard integration

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Deploy with zero configuration
3. Automatic deployments on every push

### Manual Deployment
1. Build the project (static files only)
2. Deploy to any static hosting service
3. Configure environment variables if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini AI** for powerful image analysis and story generation
- **Tailwind CSS** for rapid UI development
- **Lucide Icons** for beautiful iconography
- **Vercel** for seamless deployment

---

**Made with ❤️ and AI** | Powered by **Gemini**

[GitHub](https://github.com/Nitzan94/ai-story-generator) • [Live Demo](https://ai-story-generator-nitzan94.vercel.app)