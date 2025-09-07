<<<<<<< HEAD
# RideRite

## Overview
RideRite is a mobile application built with Flutter that helps users manage their vehicles, track maintenance, monitor driving behavior, and provide helpful vehicle-related services.

## Features
- Vehicle management and registration
- Maintenance tracking and scheduling
- User authentication and profile management
- Vehicle specifications and details viewing
- Quick lookup functionality for vehicle information
- Driving statistics and speed monitoring
- Product recommendations for vehicle care
- Store locator for service centers
- Theme customization options


## Project Structure
```
RideRite/
├── .dart_tool
├── .idea
├── android/            # Android platform-specific code
├── assets/             # Application assets
│   ├── animations/     # Animation files
│   └── images/         # Image resources
├── build/              # Build outputs
├── ios/                # iOS platform-specific code
├── lib/                # Main application code
│   ├── models/         # Data models
│   │   └── vehicle.dart
│   ├── pages/          # UI screens
│   │   ├── auth screens (login, register)
│   │   ├── vehicle screens
│   │   ├── settings screens
│   │   └── other application screens
│   ├── providers/      # State management
│   │   └── theme_provider.dart
│   ├── services/       # Business logic and API services
│   │   ├── api_service.dart
│   │   ├── notification_service.dart
│   │   ├── product_rec_service.dart
│   │   ├── token_service.dart
│   │   └── vehicle_service.dart
│   ├── widgets/        # Reusable UI components
│   │   ├── main.dart
│   │   └── MainPage.dart
│   └── main.dart       # Application entry point
├── test/               # Unit and widget tests
├── .flutter-plugins
├── .flutter-plugins-dependencies
├── .gitignore
├── .metadata
├── analysis_options.yaml
└── pubspec.yaml        # Project dependencies
```


## Getting Started

### Prerequisites
- Flutter SDK (latest stable version)
- Dart SDK
- Android Studio or VS Code with Flutter extensions
- iOS development tools (for iOS deployment)

