# Women Safety Alert System

## 📱 Project Overview

The **Women Safety Alert System** is an Android application designed to enhance personal safety by providing quick emergency alert capabilities. The app enables users to send emergency alerts to pre-configured contacts and authorities with a single tap, including location information for faster response times.

## ✨ Key Features

- **Quick SOS Alert**: One-tap emergency alert system to notify designated contacts
- **Location Sharing**: Automatic GPS location tracking and sharing during emergencies
- **Contact Management**: Manage emergency contacts easily
- **Real-time Notifications**: Receive alerts and updates in real-time
- **User-Friendly Interface**: Intuitive design for quick access during critical moments
- **Background Service**: Maintains alert functionality even when the app is in the background

## 🛠️ Technology Stack

- **Language**: Java
- **Platform**: Android
- **Build System**: Gradle
- **Android Gradle Plugin**: v8.11.2
- **Target SDK**: Android 8.0 or higher

## 📋 Project Structure

```
WomenSafetyAlertSystem/
├── app/                          # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Java source code
│   │   │   ├── res/             # Resources (layouts, drawables, strings)
│   │   │   └── AndroidManifest.xml
│   │   └── test/                # Unit tests
│   └── build.gradle             # App module configuration
├── build.gradle                 # Root project configuration
├── settings.gradle              # Gradle settings
├── gradle.properties            # Gradle properties
└── README.md                    # This file
```

## 🚀 Getting Started

### Prerequisites

- Android Studio (Latest version recommended)
- JDK 11 or higher
- Android SDK with API level 24+
- Gradle 8.0+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aslamak05/WomenSafetyAlertSystem.git
   cd WomenSafetyAlertSystem
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the cloned folder and select it

3. **Sync Gradle**
   - Android Studio will automatically sync the Gradle files
   - Wait for the build to complete

4. **Configure local properties** (if needed)
   - Update `local.properties` with your Android SDK path if required:
     ```
     sdk.dir=/path/to/android/sdk
     ```

### Building the Project

```bash
# Build debug version
./gradlew build

# Build release version
./gradlew assembleRelease

# Run tests
./gradlew test
```

### Running the App

- **Via Android Studio**: Click the "Run" button (Shift + F10)
- **Via Gradle**: 
  ```bash
  ./gradlew installDebug
  ```

## 🔧 Configuration

### Permissions Required

The app requires the following permissions (declared in `AndroidManifest.xml`):
- `ACCESS_FINE_LOCATION` - For GPS location tracking
- `ACCESS_COARSE_LOCATION` - For network-based location
- `SEND_SMS` - For alert messaging
- `INTERNET` - For data transmission
- `CAMERA` - For optional video recording features

### API Integration

The app may integrate with:
- Google Maps API for location services
- SMS/Messaging services for alert delivery
- Firebase for real-time notifications (if configured)

## 📝 Usage Guide

### For Users

1. **Initial Setup**
   - Launch the app
   - Add emergency contacts
   - Enable location services

2. **Sending an Alert**
   - Press the emergency alert button (prominently displayed)
   - Confirm the alert
   - Your contacts will receive immediate notification with your location

3. **Manage Contacts**
   - Navigate to Settings
   - Add/Edit/Delete emergency contacts
   - Set contact preferences

## 🐛 Known Issues & Limitations

- Location accuracy depends on GPS signal availability
- Alert delivery may vary based on network connectivity
- Some features may require specific Android versions

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Aslam**
- GitHub: [@Aslamak05](https://github.com/Aslamak05)

## 📞 Support & Contact

For support or questions regarding this project:
- Open an issue on GitHub
- Contact the developer through GitHub profile

## 🙏 Acknowledgments

- Android Documentation
- Open-source community contributions
- All contributors and users

---

**Stay Safe! 🛡️**

*This app is designed with the mission to enhance personal safety and reduce emergency response times.*
