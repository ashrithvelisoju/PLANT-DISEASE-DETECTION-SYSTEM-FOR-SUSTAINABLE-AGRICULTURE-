# Plant Disease Detection System for Sustainable Agriculture 🌾🔬

An advanced AI-powered agricultural technology solution that combines computer vision, satellite monitoring, climate analysis, and intelligent recommendations to help farmers detect plant diseases early and implement sustainable farming practices.

## Overview

The Plant Disease Detection System for Sustainable Agriculture is a comprehensive web application built with Streamlit that leverages cutting-edge technologies including TensorFlow machine learning models, Google Gemini AI, satellite imagery analysis, and multilingual support. The system provides farmers and agricultural professionals with powerful tools for disease detection, yield prediction, treatment planning, and agricultural monitoring.

## Key Features

### 🔬 AI-Powered Disease Detection
- **Multi-Disease Recognition**: Detects 38+ different plant diseases across multiple crop types
- **Real-Time Analysis**: Instant disease identification from uploaded plant images
- **Confidence Scoring**: Provides probability scores for detected diseases
- **Multiple Disease Support**: Identifies and analyzes multiple diseases in a single plant
- **Yield Impact Prediction**: Estimates potential crop loss and economic impact

### 🛰️ Satellite Monitoring & Remote Sensing
- **Sentinel Hub Integration**: Access to high-resolution satellite imagery
- **Vegetation Indices**: NDVI, EVI, and NDMI analysis for crop health monitoring
- **Temporal Analysis**: Historical and real-time vegetation health tracking
- **Geographic Coverage**: Support for any global location with satellite data
- **Interactive Mapping**: Folium-based interactive maps for area selection

### 🌡️ Climate & Environmental Analysis
- **Historical Climate Data**: 5-20 year climate pattern analysis
- **Weather Integration**: Real-time weather data from OpenWeatherMap
- **Soil Analysis**: Comprehensive soil parameter assessment (pH, NPK, organic matter)
- **Disease Risk Assessment**: Climate-based disease risk predictions
- **Seasonal Pattern Recognition**: Long-term agricultural trend analysis

### 🎯 Personalized Treatment Planning
- **Farm-Specific Recommendations**: Customized treatment plans based on farm characteristics
- **Organic & Conventional Options**: Support for different farming methodologies
- **Equipment-Based Planning**: Treatment plans adapted to available equipment
- **Cost Estimation**: Detailed cost analysis per hectare and total farm
- **Timeline Management**: Day-by-day treatment schedules with specific instructions

### 🌍 Multilingual Support
- **13 Indian Languages**: Hindi, Bengali, Telugu, Marathi, Tamil, Urdu, Gujarati, Kannada, Malayalam, Punjabi, Odia, Sanskrit
- **Real-Time Translation**: Dynamic content translation using Google Translator
- **Unicode Font Support**: Proper rendering of Devanagari and other scripts
- **Localized Interface**: Complete UI translation including buttons, labels, and content

### 📊 Advanced Analytics & Reporting
- **Comprehensive Reports**: Downloadable analysis reports in multiple formats
- **Visual Analytics**: Charts, graphs, and maps for data visualization
- **Disease Severity Assessment**: Computer vision-based severity analysis
- **Economic Impact Analysis**: Cost-benefit analysis for treatments
- **Multi-Disease Integration**: Comprehensive reports for multiple detected diseases

## Prerequisites

### System Requirements
- **Operating System**: Windows 10+, macOS 10.14+, or Linux (Ubuntu 18.04+)
- **Python**: 3.8 or higher (3.9+ recommended)
- **Memory**: 8GB RAM minimum (16GB recommended)
- **Storage**: 5GB free space for models and dependencies
- **Internet**: Stable connection for API calls and satellite data

### Required API Keys
- **Google AI API Key**: For Gemini AI analysis ([Get API Key](https://makersuite.google.com/app/apikey))
- **OpenWeatherMap API Key**: For weather data ([Get API Key](https://openweathermap.org/api))
- **Sentinel Hub Credentials**: For satellite imagery ([Get Credentials](https://www.sentinel-hub.com/))
  - Instance ID
  - Client ID
  - Client Secret

### Pre-trained Model
- **TensorFlow Model**: `trained_plant_disease_model.keras` (must be placed in project root)
- **Model Size**: ~50-100MB
- **Format**: Keras/TensorFlow SavedModel format

## Installation

### Method 1: Quick Setup
```bash
# Clone the repository
git clone https://github.com/ashrithvelisoju/PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-.git
cd PLANT-DISEASE-DETECTION-SYSTEM-FOR-SUSTAINABLE-AGRICULTURE-

# Create virtual environment
python -m venv plant_disease_env
source plant_disease_env/bin/activate  # On Windows: plant_disease_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
