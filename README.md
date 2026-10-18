# 📖 Poems App

<p align="center">
  <b>A beautiful sanctuary for poetry lovers on Android.</b>
</p>

<p align="center">
  <em>"A modern Android application built in Java to read, browse, and enjoy a curated collection of poems with a clean, elegant user interface."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Java-orange" alt="Language">
  <img src="https://img.shields.io/badge/UI-Material%20Design-blue" alt="UI">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

**Poems App** is a beautifully designed Android application built for poetry enthusiasts. Built entirely in **Java**, it provides a seamless and visually appealing way to read and explore a collection of poems. 

The app features a smooth onboarding experience, a personalized user section, and a well-organized list of poems, making it a delightful reading companion for literature lovers.

---

## ✨ Key Features

* **🚀 Splash Screen (`SplashActivity.java`):** A welcoming startup screen that sets the mood for a great reading experience.
* **👤 User Profile (`UserActivity.java`):** A dedicated section for the user to personalize their experience.
* **📜 Poems List (`PoemsListActivity.java`):** Browse through a beautifully formatted list of all available poems.
* **📖 Poem Detail View (`PoemDetailActivity.java`):** Read individual poems in a distraction-free, elegantly designed layout.
* **🧩 Base Activity (`BaseActivity.java`):** Ensures consistent UI elements and navigation across the entire app.
* **🎨 Custom Styling:** Features custom drawables like `gradient_background.xml`, `gradient_button.xml`, and `gradient_card.xml` for a modern, polished look.

---

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|---|---|
| **Language** | Java |
| **IDE** | Android Studio |
| **UI Components** | XML Layouts, RecyclerView, Custom Drawables |
| **Architecture** | Activity-based |
| **Styling** | Gradient Backgrounds, Material Cards |

---

## 📂 Project Structure

```text
android-poems-app/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── kotlin+java/com/example/poemsapp/
│   │   │   │   ├── BaseActivity.java            # Base class for common UI
│   │   │   │   ├── MainActivity.java            # Main Dashboard
│   │   │   │   ├── PoemDetailActivity.java      # Single Poem View
│   │   │   │   ├── PoemListAdapter.java         # RecyclerView Adapter
│   │   │   │   ├── PoemsApplication.java        # Application class
│   │   │   │   ├── PoemsListActivity.java       # List of Poems
│   │   │   │   ├── SplashActivity.java          # App Startup
│   │   │   │   └── UserActivity.java            # User Profile
│   │   │   ├── res/
│   │   │   │   ├── drawable/                    # Gradients & Icons
│   │   │   │   │   ├── gradient_background.xml
│   │   │   │   │   ├── gradient_button.xml
│   │   │   │   │   └── gradient_card.xml
│   │   │   │   ├── layout/                      # UI Layouts
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── activity_poem_detail.xml
│   │   │   │   │   ├── activity_poems_list.xml
│   │   │   │   │   ├── activity_splash.xml
│   │   │   │   │   ├── activity_user.xml
│   │   │   │   │   └── item_poem.xml            # RecyclerView Item Layout
│   │   │   │   ├── mipmap/                      # App Icons
│   │   │   │   └── values/                      # Colors, Strings, Themes
│   │   │   └── AndroidManifest.xml
│   │   └── build.gradle
│   ├── proguard-rules.pro
│   └── gradle/
├── build.gradle
├── settings.gradle
└── README.md
```

---

## 🚀 How to Build and Run

### Prerequisites
* **Android Studio** (Latest Version)
* **JDK 11** or higher
* **Android SDK** (API 21+)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/iqramaaqsoodmughal363/android-poems-app.git
   ```
2. **Open in Android Studio**
   Open Android Studio → **File** → **Open** → Select the `android-poems-app` folder.
3. **Sync Gradle**
   Wait for Gradle to sync. Click **"Sync Now"** if prompted.
4. **Build and Run**
   Connect your Android device or start an emulator, then click the **Run** button (green play icon).

---

## ⚙️ How It Works (Behind the Scenes)

### 1. Smooth Navigation
The app uses a logical flow starting from the `SplashActivity`, leading into the `MainActivity` or `PoemsListActivity`. The `BaseActivity` ensures that core UI elements (like toolbars or navigation) remain consistent throughout.

### 2. Dynamic Poem List (`PoemListAdapter.java`)
The list of poems is displayed using a `RecyclerView`. The custom `PoemListAdapter` binds the poem data (titles, snippets) to the `item_poem.xml` layout, ensuring smooth scrolling.

### 3. Elegant Reading Experience (`PoemDetailActivity.java`)
When a user taps on a poem, the `PoemDetailActivity` opens. It uses a clean, minimal layout to display the full text of the poem, free from distractions, allowing the user to focus purely on the literature.

---

## 🎯 Key Takeaways

* **UI/UX Focus:** Demonstrates how custom gradients and cards can elevate a simple app to look premium.
* **Clean Java Code:** Solid use of Java for Activity lifecycle management and data binding.
* **Reading App Architecture:** A great template for any text-based or e-book style application.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { 
    learn(); 
    build(); 
    innovate(); 
}
```

---

## 📅 Date

October 18, 2026

---

## 📄 License

This project is intended for educational and personal use purposes.
