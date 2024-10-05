# 🌱 Soila App

**Soila** is a Flutter-based mobile application that leverages NASA datasets to provide real-time analytics and insights for farmers about soil moisture, precipitation, land temperature, and evapotranspiration. The app integrates APIs to deliver actionable data to help farmers optimize water usage and improve crop yields.

### Demo
![Demo](https://drive.google.com/uc?export=view&id=1LEFvYFV03GurhxvSGDPkigoqfeucZJyH)

## 🚀 Features

- **Soil Moisture Data (SMAP)**: Visualizes soil moisture levels and provides insights for crops like corn and wheat.
- **Rainfall Predictions (IMERG)**: Offers 7-day rainfall forecasts to help plan irrigation and water management.
- **Land Temperature (MODIS)**: Monitors land surface temperature for optimal crop growth.
- **Evapotranspiration (ECOSTRESS)**: Provides data on daily water usage to ensure crops receive the right amount of water.
- **Root Zone Moisture (SMAP)**: Tracks moisture levels in the crop root zone for improved crop health monitoring.
- **Real-time Analytics**: Simplified, easy-to-understand stats like percentages for better decision-making.
- **Google Sign-In**: User authentication using Google accounts.
- **Intuitive Design**: Simple navigation with a clean UI to ensure user-friendliness.

## 📱 Screenshots

1. **Analytics Dashboard**  
   ![Analytics](https://drive.google.com/uc?export=view&id=1SlRJKQ5225xuSBtL4bzKd0QI16jZWtzU) 
2. **Chat with Expert (via Gemini API)**  
   ![Gemini](https://drive.google.com/uc?export=view&id=1-63Ll-ZIxUqdwkXCEnImC_7QXEPCjlgE) 

## 🌍 Technologies Used

- **Flutter**: For building the cross-platform mobile application.
- **Dart**: Programming language for Flutter.
- **NASA APIs**: To access real-time Earth observation data (SMAP, MODIS, ECOSTRESS, IMERG).
- **Gemini API**: Integrated for real-time chat functionality.
- **Provider**: For state management across the app.

## 🛠️ Setup & Installation

To run this project locally, follow these steps:

**Clone the Repository**:
   ```bash
   git clone https://github.com/adham-khalill/soila-app.git
   cd soila-app
   ```
   
   Install Flutter Dependencies:
   
```bash
flutter pub get
```

**Run the App:**
Use the following command to run the app on an emulator or a real device:

```bash
flutter run
```

**📊 Data Sources**
Soila app integrates with several key datasets and APIs for real-time farming analytics:

NASA SMAP: Soil Moisture Active Passive data for soil moisture analysis.
NASA MODIS: Moderate Resolution Imaging Spectroradiometer for land temperature monitoring.
NASA ECOSTRESS: For evapotranspiration and water stress data.
IMERG: Integrated Multi-satellitE Retrievals for GPM (Global Precipitation Measurement) data for rainfall predictions.

**👨‍💻 Authors**
Adham Khalill - adham-khalill

Ahmed Tahan - Ahmed-Tahan7



