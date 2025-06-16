# 📚 Learnify

**Learnify** is a modern Android e-learning app built for students to explore courses, watch YouTube tutorials, take quizzes, follow a structured learning roadmap, and now — **write and run code in an inbuilt code editor**. Designed with an intuitive UI and real-time content fetched from Firebase.

---

## 🚀 Features

- 📺 **Video Courses**: Watch course tutorials via embedded YouTube player.
- 📘 **Roadmaps**: Structured learning paths for various domains.
- 🎯 **Quiz Zone**: Practice quizzes to test your understanding.
- 💻 **Inbuilt Code Editor**: Write, test, and run code directly inside the app.
- 👤 **Profile Section**: View and manage user details.
- 🌗 **Light & Dark Themes**: Seamless day/night mode support.
- 🎨 **Custom Bottom Navigation**: Beautiful gradient nav bar with icon highlights.

---

## 🛠️ Tech Stack

- **Java** – Main programming language
- **XML** – UI layout
- **Firebase Firestore & Storage** – Backend for course data & assets
- **YouTube Player API** – For video streaming
- **Material Components** – For modern UI elements
- **View Binding** – Safer, cleaner view access
- **Ace Editor (via WebView)** – Embedded code editor with syntax highlighting
- **JDoodle API** *(or similar)* – For remote code execution

---

## 🧑‍💻 Project Structure

Learnify/
├── app/
│ ├── java/com.learnify/
│ │ ├── MainActivity.java
│ │ ├── CodeEditorActivity.java <-- NEW
│ │ └── Fragment/
│ │ ├── HomeFragment.java
│ │ ├── QuizFragment.java
│ │ ├── RoadmapFragment.java
│ │ └── ProfileFragment.java
│ └── res/
│ ├── layout/
│ │ ├── activity_code_editor.xml <-- NEW
│ ├── drawable/
│ ├── values/
│ └── menu/
├── screenshots/
│ ├── home.png
│ ├── quiz.png
│ ├── profile.png
│ └── editor.png <-- NEW
└── README.md

## 🖼️ Screenshots

### 🏠 Home Screen
![WhatsApp Image 2025-06-15 at 23 07 33_0b700944](https://github.com/user-attachments/assets/6a5e643b-dbe8-4b87-9e50-f76ac6c6f7ca)
### 📝 Quiz Screen
![WhatsApp Image 2025-06-15 at 23 07 34_2d1ca902](https://github.com/user-attachments/assets/d96cea8f-97fd-44ba-80b2-5cee186b9cf0)

### 👤 Profile Screen
![WhatsApp Image 2025-06-15 at 23 07 34_9c720f95](https://github.com/user-attachments/assets/acd2cad5-2f7c-48ee-9962-9fd733f89468)

---

## 🔧 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/AryantKumar/Learnify-User-App.git
Open the project in Android Studio.

Connect Firebase using the Firebase Assistant:
Tools → Firebase → Connect your app

Add your YouTube API Key in the YouTubePlayerView.

For code execution, set up your JDoodle or Piston API keys inside CodeExecutor.java.

Run the app on your device/emulator.

🙌 Contribution
Pull requests are welcome! If you'd like to improve Learnify or fix bugs, feel free to fork the repo and submit a PR.

📄 License
This project is under the MIT License.

💡 Author
Made with ❤️ by Aryant Kumar
