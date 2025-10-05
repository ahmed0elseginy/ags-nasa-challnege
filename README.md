# 🌱 Sustainable Farming with NASA Earth Data

An interactive agricultural platform that helps farmers and researchers make better decisions using NASA Earth Observation data for monitoring soil, vegetation, rainfall, and weather to achieve sustainable farming.

## 🚀 Features

### 🌍 NASA Earth Observation Integration
- **Plant Health (NDVI)**: Monitor crop conditions using NASA MODIS satellite imagery to measure plant health and vegetation density
- **Soil Moisture**: Accurate data from NASA SMAP for soil moisture measurement and optimal irrigation timing
- **Rainfall & Weather**: Track precipitation and weather forecasts from NASA GPM for irrigation planning and weather protection
- **Solar Energy Data**: Comprehensive information on solar radiation and temperatures from NASA POWER for crop productivity optimization

### 🎯 Core Capabilities
- **Interactive Farm Mapping**: Click on map locations to select farm areas and analyze agricultural data
- **Smart Recommendations**: AI-powered irrigation and fertilization recommendations
- **Daily Crop Monitoring**: Real-time crop condition tracking
- **Detailed Productivity Reports**: Comprehensive analysis and reporting
- **IoT Device Integration**: Connect and manage agricultural sensors and devices
- **Predictive Analytics**: Crop yield prediction, harvest time forecasting, and pest risk assessment
- **What-If Simulations**: Scenario planning for different agricultural strategies
- **Data Export**: Export results and statistics in multiple formats

### 👥 Target Users

#### For Farmers
- Select farm location by clicking on the map
- Receive smart irrigation and fertilization recommendations
- Monitor crop conditions daily
- Access detailed productivity reports

#### For Researchers
- Upload GIS files and Shapefiles
- Analyze large land areas
- Compare historical data
- Export results and statistics

## 🛠️ Technology Stack

- **Frontend**: React 19.1.1 with Vite
- **Styling**: Tailwind CSS with Framer Motion animations
- **Mapping**: Leaflet with React-Leaflet
- **Charts**: Chart.js and Recharts for data visualization
- **3D Graphics**: Three.js with React Three Fiber
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **PDF Generation**: jsPDF for report generation

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ags-nasa-challenge
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
src/
├── components/
│   ├── actuators/          # Actuator control dashboard
│   ├── analytics/          # Analytics and reporting components
│   ├── automation/         # Automation rules and configuration
│   ├── iot/               # IoT device management
│   ├── layout/            # Header, sidebar, and layout components
│   ├── map/               # Interactive farm mapping
│   ├── others/            # Landing page components
│   ├── panels/            # Data and visualization panels
│   ├── report/            # Report generation and analysis
│   └── simulation/        # What-if simulation components
├── pages/                 # Main application pages
├── services/              # API services and data management
└── config/               # Configuration files
```

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌐 Application Routes

- `/` - Home page with landing content
- `/login` - User authentication
- `/signup` - User registration
- `/dashboard` - Main dashboard
- `/what-if` - What-if simulation chat
- `/iot-devices` - IoT device management
- `/actuators` - Actuator control dashboard

## 🔧 Configuration

The application uses several configuration files:
- `vite.config.js` - Vite build configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `eslint.config.js` - ESLint rules
- `postcss.config.js` - PostCSS configuration

## 📊 Data Sources

This platform integrates with multiple NASA Earth Observation datasets:
- **MODIS**: Vegetation indices and land surface data
- **SMAP**: Soil moisture measurements
- **GPM**: Global precipitation measurements
- **POWER**: Solar radiation and meteorological data

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is part of the NASA AGS Challenge and follows the challenge guidelines and requirements.

## 🌟 Acknowledgments

- NASA Earth Observation data providers
- The agricultural research community
- Open source contributors and libraries used in this project
