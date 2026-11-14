# StridePulse-MaterialYou-Pedometer
a simple pedometer app
👟 StridePulse

StridePulse is a modern, privacy-focused Android pedometer and fitness tracking application engineered entirely in Kotlin using Jetpack Material 3 design principles.

Designed for performance, battery efficiency, and aesthetic customizability, StridePulse operates 100% offline with local data persistence via SharedPreferences, utilizing the device's hardware step counter sensor for pinpoint step accuracy.

🌟 Comprehensive Feature Set

1. Adaptive Material You & 13+ Theme Engine set minimum SDK to android 13 


Material You Auto (Android 12+): Automatically synchronizes card surfaces, progress indicators, and backgrounds with your device wallpaper and system Dark/Light mode state.

Curated & Surprise Palettes: Includes 9 distinct color themes (Emerald Forest, Crimson Pulse, Ocean Deep, Solar Gold, Royal Amethyst, Cyber Cyan, Sunset Ember, Rose Quartz, Midnight Mono) plus a Surprise Me! random palette generator.

2. Flexible Profile Calibration & Units

Imperial & Metric Support: Toggle seamlessly between centimeters (cm) / feet-and-inches (ft/in) for height, and kilograms (kg) / pounds (lb) for weight.

Smart Stride Calculation: Dynamically calculates stride length and active calories burned based on user body parameters.

3. Advanced Step Tracking & Interactive UI

Live Google-Style Progress Bar: Smooth animated LinearProgressIndicator with rounded tracks and live percentage counters.

Tap-Card Quick Insights: Tap the main dashboard card to cycle through 4 live data views:

Standard progress & remaining goal estimate

Calibrated stride length & active minutes

Lifetime step count & goal streak record

Smart coaching motivation tips

Milestone Haptics: Subtle haptic feedback pulses upon crossing 25%, 50%, 75%, and 100% daily goal milestones.

4. Timed Walk Workouts & Analytics

Dedicated Workout Mode: Launch walking sessions to track exact duration, active steps, workout distance, calories, and real-time cadence (spm).

7-Day Trend Summaries: View text-based visual activity charts (█░░) tracking weekly totals, daily averages, best performance days, and goal hit ratios.

Unlockable Badges: Automatically unlock 8 lifetime achievement badges as your step count, walking pace, and consistency streaks grow.

One-Tap Sharing: Export your complete daily fitness breakdown instantly via Android's native share sheet.

Multi-Language Support: Fully localized across English, Español, and Français.

🛠️ Architecture & Tech Stack

Language: Kotlin (AppCompatActivity, SensorEventListener)

UI Architecture: Programmatic XML Layouts + Jetpack Material 3 (MaterialCardView, LinearProgressIndicator, MaterialButton, AlertDialog)

Sensors: Android SensorManager (Sensor.TYPE_STEP_COUNTER

Data Persistence: Offline SharedPreferences with automatic midnight day-rollover and 14-day history rolling buffer.

📜 License

Distributed under the MIT License. See the LICENSE file for details.









