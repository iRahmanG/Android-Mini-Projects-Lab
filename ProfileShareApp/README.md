# 📱 Profile Share App

## 🎯 Overview
The **Profile Share App** is a simple Android app built in Kotlin that demonstrates the use of:
- **Explicit Intents** → Pass data between activities.
- **Implicit Intents** → Open websites, share text, make phone calls, send SMS.
- **Activity Result API** → Pick an image from the gallery.

This project is part of the **Android Mini Projects Lab** — a free, open-source learning resource for Android beginners.

---

## 📂 Features
1. **Form Screen (Explicit Intent)**
    - Enter Name, Email, Website, and select a profile image.
    - Pass all data to the Preview screen.

2. **Preview Screen**
    - Displays profile details.
    - Open website in browser.
    - Share profile text with other apps.
    - Make a phone call (via dialer).
    - Send SMS with pre-filled text.

---

## 🛠 Tech Stack
- **Language:** Kotlin
- **UI:** XML Layouts
- **Architecture:** Basic (no MVVM)
- **Android API:** Activity Result API for picking images

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/iRahmanG/Android-Mini-Projects-Lab.git```
2. Open the ProfileShareApp folder in Android Studio.
3. Run on an emulator or a physical Android device (API 21+).
---
## 📚 Learning Outcomes
Understand the difference between explicit and implicit intents.

Pass data between activities using Intent.putExtra().

Use registerForActivityResult to pick images.

Trigger phone calls and send SMS via implicit intents.

Open URLs in the browser from your app.

## 📝 License
This project is part of Android Mini Projects Lab and is free for anyone to use, modify, and learn from.

