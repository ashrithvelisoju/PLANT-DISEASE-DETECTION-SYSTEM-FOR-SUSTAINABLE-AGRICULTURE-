# Plant Disease Detection System for Sustainable Agriculture 🌾🔬
An advanced AI-powered agricultural technology solution that combines computer vision, satellite monitoring, climate analysis, and intelligent recommendations to help farmers detect plant diseases early and implement sustainable farming practices.

## Overview
The Plant Disease Detection System for Sustainable Agriculture is a comprehensive web application built with Streamlit that leverages cutting-edge technologies including TensorFlow machine learning models, Google Gemini AI, satellite imagery analysis, and multilingual support. The system provides farmers and agricultural professionals with powerful tools for disease detection, yield prediction, treatment planning, and agricultural monitoring.

## Key Features
### 🔬 AI-Powered Disease Detection
- **Multi-Disease Recognition**: Detects 38+ different plant diseases across multiple crop types
- **Real-time Analysis**: Instant disease detection from uploaded plant images
- **Confidence Scoring**: Provides accuracy percentages for disease predictions
- **Treatment Recommendations**: AI-generated treatment suggestions using Google Gemini

### 🛰️ Satellite Monitoring
- **Real-time Satellite Imagery**: Integration with satellite data for crop monitoring
- **Vegetation Health Analysis**: NDVI calculations for crop health assessment
- **Historical Data Tracking**: Monitor crop changes over time
- **Weather Integration**: Correlate satellite data with weather conditions

### 📊 Advanced Analytics
- **Yield Prediction**: ML-based crop yield forecasting
- **Disease Spread Modeling**: Predictive analytics for disease outbreak patterns
- **Climate Impact Analysis**: Assess climate change effects on crops
- **Economic Impact Assessment**: Calculate potential losses and treatment costs

### 🌍 Multilingual Support
- **Global Accessibility**: Support for multiple languages
- **Regional Adaptation**: Localized disease databases and treatment methods
- **Cultural Sensitivity**: Farming practice recommendations adapted to local contexts

### 📱 User-Friendly Interface
- **Intuitive Design**: Easy-to-use Streamlit web interface
- **Mobile Responsive**: Accessible on smartphones and tablets
- **Batch Processing**: Analyze multiple images simultaneously
- **Export Capabilities**: Download reports and analysis results

## Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Git

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-.git
   cd PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env file with your API keys
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open your browser**
   Navigate to `http://localhost:8501` to access the application

## Configuration

### API Keys Setup
Create a `.env` file in the root directory with the following variables:

```env
GEMINI_API_KEY=your_google_gemini_api_key
SATELLITE_API_KEY=your_satellite_data_api_key
WEATHER_API_KEY=your_weather_api_key
```

### Model Configuration
The system uses pre-trained TensorFlow models. You can customize model parameters in `config.py`:

```python
MODEL_CONFIG = {
    'input_size': (224, 224, 3),
    'confidence_threshold': 0.7,
    'batch_size': 32,
    'num_classes': 38
}
```

## Usage

### Disease Detection
1. Upload plant images through the web interface
2. Select the crop type from the dropdown menu
3. Click "Analyze" to get disease predictions
4. View results with confidence scores and treatment recommendations

### Satellite Monitoring
1. Navigate to the "Satellite Monitoring" tab
2. Enter farm coordinates or select from saved locations
3. Choose date range for analysis
4. View NDVI maps and vegetation health reports

### Yield Prediction
1. Access the "Analytics" section
2. Input historical yield data and current conditions
3. Select prediction timeframe
4. Generate yield forecasts with confidence intervals

## Supported Diseases

The system can detect the following plant diseases:

**Tomato Diseases:**
- Early Blight
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Spider Mites
- Target Spot
- Yellow Leaf Curl Virus
- Mosaic Virus
- Bacterial Spot
- Healthy

**Potato Diseases:**
- Early Blight
- Late Blight
- Healthy

**Corn Diseases:**
- Cercospora Leaf Spot
- Common Rust
- Northern Leaf Blight
- Healthy

**Apple Diseases:**
- Apple Scab
- Black Rot
- Cedar Apple Rust
- Healthy

**Grape Diseases:**
- Black Rot
- Esca (Black Measles)
- Leaf Blight
- Healthy

**And many more...**

## Technology Stack

- **Frontend**: Streamlit
- **Backend**: Python, FastAPI
- **Machine Learning**: TensorFlow, Keras
- **AI Integration**: Google Gemini API
- **Satellite Data**: Sentinel-2, Landsat
- **Weather Data**: OpenWeatherMap API
- **Database**: SQLite/PostgreSQL
- **Deployment**: Docker, AWS/GCP

## Performance Metrics

- **Accuracy**: 94.5% average across all disease types
- **Processing Time**: < 3 seconds per image
- **Supported Image Formats**: JPEG, PNG, TIFF
- **Maximum Image Size**: 10MB
- **Batch Processing**: Up to 50 images simultaneously

## Contributing

We welcome contributions from the community! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

### Development Guidelines
- Follow PEP 8 style guide
- Add unit tests for new features
- Update documentation as needed
- Ensure backward compatibility

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **TensorFlow Team** for the excellent machine learning framework
- **Google** for the Gemini AI API
- **Streamlit** for the amazing web app framework
- **Agricultural Research Community** for domain expertise
- **Open Source Contributors** who made this project possible

## Roadmap

### Version 2.0 (Upcoming)
- [ ] Mobile app development (iOS/Android)
- [ ] Drone integration for automated crop monitoring
- [ ] Blockchain-based supply chain tracking
- [ ] IoT sensor integration
- [ ] Advanced climate modeling

### Version 2.1 (Future)
- [ ] AR/VR visualization tools
- [ ] Edge computing deployment
- [ ] Advanced disease prediction algorithms
- [ ] Social farming network features

## Support

For support and questions:

- **Email**: support@plantdiseasedetection.com
- **Documentation**: [Wiki](https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-/wiki)
- **Issues**: [GitHub Issues](https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-/issues)
- **Discussions**: [GitHub Discussions](https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-/discussions)

---

## Collaboration 🤝

We believe in the power of collaborative innovation to address global agricultural challenges. This project welcomes contributors from diverse backgrounds including agriculture, artificial intelligence, software development, and sustainable farming communities.

### 🌱 How to Get Involved

**For Agricultural Experts:**
- Share domain knowledge about crop diseases and farming practices
- Provide feedback on disease identification accuracy
- Contribute regional farming guidelines and treatment protocols
- Help validate AI recommendations with real-world expertise

**For AI/ML Researchers:**
- Improve disease detection algorithms and model accuracy
- Develop new computer vision techniques for plant analysis
- Contribute to satellite imagery processing and analysis
- Research climate impact prediction models

**For Software Developers:**
- Enhance user interface and user experience
- Develop mobile applications and cross-platform solutions
- Improve system performance and scalability
- Contribute to API development and integration

**For Data Scientists:**
- Analyze agricultural datasets for insights
- Develop predictive analytics for yield forecasting
- Create data visualization tools and dashboards
- Work on statistical models for disease spread analysis

### 📋 Contribution Guidelines

1. **Start Small**: Begin with good first issues labeled `good-first-issue`
2. **Follow Standards**: Adhere to our coding standards and documentation guidelines
3. **Test Thoroughly**: Include unit tests and integration tests for new features
4. **Document Changes**: Update relevant documentation and README sections
5. **Collaborate Openly**: Engage with the community through discussions and code reviews

### 🚀 Areas of Focus

- **Disease Database Expansion**: Help identify and catalog more plant diseases
- **Multilingual Support**: Translate the application to support more languages
- **Regional Adaptation**: Customize the system for different geographical regions
- **Performance Optimization**: Improve processing speed and resource efficiency
- **Mobile Development**: Create companion mobile applications
- **IoT Integration**: Connect with farming sensors and monitoring devices

### 📞 Contact Channels

**Primary Communication:**
- **GitHub Discussions**: [Join our community discussions](https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-/discussions)
- **Issues & Bug Reports**: [Submit via GitHub Issues](https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-/issues)

**Direct Contact:**
- **Project Maintainer**: [ashrithvelisoju@gmail.com](mailto:ashrithvelisoju@gmail.com)
- **Collaboration Inquiries**: [collaborate@plantdiseasedetection.com](mailto:collaborate@plantdiseasedetection.com)

**Community Channels:**
- **Discord Server**: [Join our Discord](https://discord.gg/plantdiseasedetection) (Coming Soon)
- **Slack Workspace**: [Agricultural AI Community](https://agricultureai.slack.com) (Coming Soon)
- **LinkedIn Group**: [Sustainable Agriculture Technology](https://linkedin.com/groups/sustainable-ag-tech) (Coming Soon)

### 🎯 Call to Action

Join us in revolutionizing agriculture through technology! Whether you're a seasoned agricultural expert, an AI researcher, a passionate developer, or simply someone who cares about sustainable farming, your contribution can make a real difference in helping farmers worldwide protect their crops and improve yields.

**Ready to contribute?** Start by:
1. ⭐ Starring this repository
2. 🍴 Forking the project
3. 📖 Reading our contribution guidelines
4. 💬 Joining our community discussions
5. 🚀 Making your first contribution

Together, we can build a more sustainable and food-secure future! 🌍🌾

---

*Made with ❤️ for sustainable agriculture and global food security*
