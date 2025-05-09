# Health Tracker App

A cross-platform Flutter application to monitor and analyze your daily health metrics. Built entirely in Dart, this app provides real-time step counting, health-metric calculators (BMI, BMR, TDEE), interactive FL Chart visualizations, sleep/nutrition/exercise logging, goal tracking, and more—all wrapped in a polished, customizable UI.

---

## 📝 Description

Health Tracker App helps users keep track of vital health data and habits in one place. Key capabilities include:
- **Real-time Step Counter** powered by the device’s pedometer  
- **Health Calculators** for BMI, BMR (standard & Harris–Benedict), estimated calories burned, sleep efficiency, and advanced gait metrics  
- **Interactive Charts** (bar, line) via FL Chart for weekly/daily trends  
- **Logging Modules** for sleep hours, meals, exercise sessions  
- **Goal Setting** with history tracking  
- **Customizable Dashboard**: drag-and-drop widgets, light/dark themes, color & font selection  
- **One-tap Share** of your daily summary  

---

## 🚀 Features

- **Step Counting** using `pedometer`  
- **Dart Health Calculators** (`calculateBMI`, `calculateBMR`, etc.)  
- **FL Chart Visualizations** (weekly steps, heart rate, calories, water intake)  
- **Sleep, Nutrition & Exercise Logs** with chart outputs  
- **Dashboard Insights**: average/min/max stats per metric  
- **Daily Tips** widget with randomized health advice  
- **Reorderable Dashboard** via Flutter’s `ReorderableListView`  
- **Light & Dark Modes**, plus color/font customization in Settings  
- **Persistent Storage** of steps/logs using Hive  

---

## 🔧 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/health-tracker-app.git
   cd health-tracker-app
2.Install Flutter dependencies
flutter pub get

3.Run the app
flutter run

#📂 Project Structure
health-tracker-app/
├── android/                   # Android native project
├── ios/                       # iOS native project
├── lib/
│   ├── main.dart              # App entry point
│   ├── step_counter.dart      # StepCounter widget
│   ├── health_metrics.dart    # Calculator functions & HealthMetrics widget
│   ├── screens/               # Page widgets
│   │   ├── health_dashboard.dart
│   │   ├── sleep_tracking_page.dart
│   │   ├── nutrition_page.dart
│   │   ├── exercise_tracking_page.dart
│   │   └── goals_page.dart
│   ├── widgets/               # Reusable UI components
│   ├── services/              # Pedometer & storage handlers
│   └── settings_page.dart     # Theme & customization UI
├── assets/                    # Images & fonts
├── pubspec.yaml               # Dependencies & asset definitions
└── README.md                  # Project overview (you are here)

 Dependencies
fl_chart

animations

flutter_staggered_animations

share_plus

pedometer

hive_flutter

path_provider

permission_handler
