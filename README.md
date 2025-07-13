# 🌤️ Weather Condition App

A modern, responsive weather application that provides real-time weather information including wind direction for any location worldwide.

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city, state, or village
- **Wind Direction**: Displays wind direction with cardinal directions (N, NNE, NE, ENE, etc.)
- **Temperature Units**: Toggle between Celsius (°C) and Fahrenheit (°F)
- **Comprehensive Weather Info**: 
  - Temperature and feels like temperature
  - Humidity and pressure
  - Wind speed and direction
  - Visibility
  - Sunrise and sunset times
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dynamic Backgrounds**: Background changes based on weather conditions
- **Local Storage**: Remembers your last location and preferred units

## 🚀 Live Demo

Visit the live application: [Weather Condition App](https://weather-condition-app.vercel.app)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **JavaScript (ES6+)**: Dynamic functionality and API integration
- **OpenWeatherMap API**: Real-time weather data
- **Vercel**: Hosting and deployment

## 📦 Installation & Setup

### Prerequisites
- A modern web browser
- OpenWeatherMap API key (free)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/taramalaAravind/weather-condition-app.git
   cd weather-condition-app
   ```

2. **Get an API Key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Get your API key from your account dashboard

3. **Update the API Key**
   - Open `weather-app.html`
   - Replace `'YOUR_API_KEY_HERE'` with your actual API key
   ```javascript
   const API_KEY = 'your_actual_api_key_here';
   ```

4. **Run locally**
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Or using Node.js
   npx serve .
   
   # Or simply open weather-app.html in your browser
   ```

5. **Access the app**
   - Open your browser and go to `http://localhost:8000`

## 🚀 Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up/Login with your GitHub account
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect the configuration

### Option 3: Drag & Drop Deployment

1. **Prepare your files**
   - Make sure all files are in the root directory
   - Ensure `vercel.json` is present

2. **Deploy**
   - Go to [vercel.com](https://vercel.com)
   - Drag and drop your project folder
   - Vercel will automatically deploy it

## 📁 Project Structure

```
weather-condition-app/
├── weather-app.html      # Main application file
├── index.html           # Redirect page
├── vercel.json          # Vercel configuration
├── package.json         # Project metadata
├── README.md           # This file
├── DEPLOYMENT.md       # Deployment guide
└── LICENSE             # MIT License
```

## 🔧 Configuration

### Vercel Configuration (`vercel.json`)
- **Static Site**: Configured for static HTML deployment
- **Routing**: All routes redirect to the main weather app
- **Headers**: Security headers for better protection
- **Caching**: Optimized caching for better performance

### API Configuration
The app uses OpenWeatherMap API with the following endpoints:
- **Current Weather**: `https://api.openweathermap.org/data/2.5/weather`
- **Free Tier**: 1000 calls per day
- **Units**: Metric (°C, km/h) and Imperial (°F, mph)

## 🌟 Features in Detail

### Wind Direction
- **16-Point Compass**: N, NNE, NE, ENE, E, ESE, SE, SSE, S, SSW, SW, WSW, W, WNW, NW, NNW
- **Degree Conversion**: Automatically converts wind degrees to cardinal directions
- **Visual Display**: Clear, easy-to-read wind direction indicators

### Responsive Design
- **Mobile-First**: Optimized for mobile devices
- **Flexible Layout**: Adapts to different screen sizes
- **Touch-Friendly**: Large buttons and inputs for mobile use

### Dynamic Backgrounds
- **Weather-Based**: Background changes based on weather conditions
- **Smooth Transitions**: Animated background changes
- **Visual Feedback**: Immediate visual response to weather data

## 🔒 Security

- **API Key Protection**: API key is client-side (consider environment variables for production)
- **CORS Headers**: Proper cross-origin resource sharing configuration
- **Security Headers**: XSS protection, content type options, frame options

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **OpenWeatherMap**: For providing the weather API
- **Vercel**: For hosting and deployment platform
- **Weather Icons**: OpenWeatherMap weather icons

## 📞 Support

If you encounter any issues or have questions:

1. Check the [OpenWeatherMap API documentation](https://openweathermap.org/api)
2. Verify your API key is valid and activated
3. Check your internet connection
4. Open an issue on GitHub

---

**Made with ❤️ by taramalaAravind** 