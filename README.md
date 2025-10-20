DocAnytime – Flutter Telehealth App


A clean, professional Flutter app for connecting patients with doctors. Users can log in, browse doctors, view details, and book appointments. Designed with a modern UI and easy-to-understand code, perfect for demos, learning, or portfolio.

Features

Login Screen – Secure and simple login interface.

Home Screen – Dashboard with doctor categories and search.

Doctor Listing Screen – Browse doctors by specialty.

Doctor Details Screen – View doctor info and book appointments.

Navigation – Smooth navigation between screens.

Light, Professional UI – Minimal yet realistic design (DocAnytime theme).

Commented Code & Clean Structure – Easy to understand and extend.

Screenshots
Login Screen

Home Screen

Doctor Listing Screen

Doctor Details Screen

Replace path/to/... with your screenshot file paths.

Folder Structure
docanytime_flutter/
├── lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── login_screen.dart
│   │   ├── home_screen.dart
│   │   ├── doctor_listing_screen.dart
│   │   └── doctor_details_screen.dart
│   ├── widgets/
│   │   └── custom_widgets.dart
│   └── models/
│       └── doctor_model.dart
├── pubspec.yaml
└── README.md

Getting Started
Prerequisites

Flutter SDK (Install Flutter
)

Android Studio or VS Code with Flutter extension

Run the App
# Clone the repository
git clone https://github.com/<your-username>/docanytime_flutter.git
cd docanytime_flutter

# Install dependencies
flutter pub get

# Run the app
flutter run

Future Improvements

Authentication with Firebase

Real backend integration for doctor data and appointment booking

Push notifications for appointment reminders

Filter doctors by ratings, availability, and specialization

GitHub Commit Steps
# Initialize Git (if not done)
git init

# Add files
git add .

# Commit changes
git commit -m "Initial commit – DocAnytime Flutter app"

# Add GitHub remote
git remote add origin https://github.com/<your-username>/docanytime_flutter.git

# Pull remote changes if any
git pull origin main --rebase

# Push to GitHub
git push origin main

License

This project is licensed under the MIT License – see the LICENSE
 file for details.
