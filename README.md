This Flutter project was developed as part of an internship cycle covering Weeks 4 to 6. It includes real-world UI components, form validation, API integration, state management, and persistent data storage using SharedPreferences. The app focuses on user interaction, basic authentication, and task management using clean UI principles and minimal third-party packages.

📱 App Features
✅ Login Screen
Local form validation for username and password.

Displays error messages on incorrect input.

Hardcoded valid credentials for demo login:

Username: ahmadtask@gmail.com

Password: 123456

👤 Profile Screen
Displays static user profile info (like name, email, and picture).

Uses a hardcoded model to represent user data.

🌐 User List (API Integration)
Fetches and displays users using a real REST API.

Utilizes DummyJSON API: https://dummyjson.com/users

Parses and renders user details in a scrollable list.

📋 To-Do List
Allows users to:

Add new tasks.

Delete tasks.

Tasks are saved locally using SharedPreferences.

Simple UI for managing daily tasks.

✔️ Final Task Screen
An advanced to-do screen with:

Task completion (mark as done).

Persistent local storage.

Clean, elegant UI using Flutter widgets.

🔁 State Management
Used Provider for managing and updating app state.

Smooth navigation between screens with consistent state behavior.

🧑‍💻 Technologies Used
Flutter (Stable version)

Dart

Provider (for state management)

SharedPreferences (for local data)

DummyJSON API (for fetching real user data)

Material Design (Flutter widgets)

🚀 How to Run the App
Clone this repo:
git clone https://github.com/your_username/flutter-internship-task.git
cd flutter-internship-task

Install dependencies:
flutter pub get

Run the app:
flutter run
Make sure your device/emulator is connected and Flutter is properly set up (flutter doctor).

📂 Project Structure (Simplified)
lib/
├── main.dart
├── login_screen.dart
├── profile_screen.dart
├── user_list_screen.dart
├── todo_list_screen.dart
└── final_task_screen.dart

👨‍🎓 Developed By
Ahmad Raza

Computer Science Graduate

Beginner in Flutter, strong in HTML/CSS

Created this app for internship learning purposes

