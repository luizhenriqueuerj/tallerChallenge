# 📱 Appium Mobile UI Test Report

## ✅ App Name
**Wikipedia App (org.wikipedia)**  
Automated UI test executed using Appium on an Android emulator.

## 🎯 Purpose of the Test
Validate that the search field is functional and the app responds correctly with results after searching for “Appium”.

---

## 📱 Device/Emulator and OS

- **Device Name:** emulator-5554
- **Platform Name:** Android
- **Platform Version:** 11
- **Automation Engine:** UiAutomator2
- **Appium Server URL:** http://127.0.0.1:4723
- **App Package:** org.wikipedia
- **App Activity:** org.wikipedia.main.MainActivity
- **App Path:** `./apps/wikipedia.apk`

---

## 🧪 Summary of Test Steps

1. Launch the Wikipedia app using Appium
2. Tap the “SKIP” button during onboarding (if present)
3. Wait for the main screen to load
4. Tap on the search button
5. Type "Appium" into the search input field
6. Validate that at least one search result is displayed
7. Capture and save a screenshot after performing the search
