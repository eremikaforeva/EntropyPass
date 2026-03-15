# EntropyPass 🔐
**Your passwords. Your device. Your entropy.**

EntropyPass is a high-security, privacy-first password manager for Android that generates truly random passwords by harvesting raw physical chaos from your device's sensors. Unlike standard generators that rely purely on software algorithms, EntropyPass mixes "true entropy" from the real world into its cryptographic seed.

---

## 🌟 Key Features

### 🎲 Physical Entropy Harvesting
Generate unguessable passwords by enabling multiple physical entropy sources:
- **Camera Noise:** Analyzes thermal noise and light variations from the camera sensor.
- **Touch Pattern:** Records precise X/Y coordinates, pressure, and nanosecond timestamps from your unique touch gestures.
- **Motion Sensor:** Captures micro-vibrations and rotation data from the accelerometer and gyroscope.
- **System Entropy:** Draws from the Android OS cryptographic pool (hardware interrupts, network events).

### 🛡️ Military-Grade Encryption
- **AES-256-GCM:** Authenticated encryption for all stored passwords.
- **PBKDF2 Hardening:** 600,000 iterations (OWASP standard) used for key derivation from your master password.
- **Zero-Knowledge Architecture:** No data ever leaves your device. We have no servers and no access to your vault.

### 📱 Premium UX/UI
- **Modern Aesthetic:** Clean, Apple-inspired interface with 16dp rounded corners and smooth teal gradients.
- **Full Dark Mode:** A deep navy and slate palette optimized for security and eye comfort.
- **Haptic Intelligence:** Tactile feedback for every interaction, from copying passwords to security warnings.
- **Educational:** Integrated info buttons explaining the "science" behind every entropy source.

### 💾 Data Portability
- **Import from CSV:** Easily migrate your existing passwords.
- **Encrypted Backups:** Export your entire vault as a secure, transportable string.
- **Vault Restore:** Restore your backups instantly on any device with your master password.

---

## 🔒 Security Philosophy

EntropyPass is built on the principle that **true randomness is physical**. By mixing camera noise, motion vibrations, and touch patterns, the app creates a "cryptographic soup" that is unique to you and your surroundings. 

**Privacy Protections:**
- **Screen Protection:** Screenshorts and screen recordings are blocked globally within the app.
- **Smart Auto-Lock:** Automatically locks your vault after 1 minute in the background.
- **Biometric Security:** Optional Fingerprint/Face unlock integrated with Android's BiometricPrompt.
- **Insecure Mode Detection:** Generates a "weak" warning password if no entropy sources are enabled, educating users on the importance of randomness.

---

## 🛠️ Technical Stack
- **Language:** 100% Kotlin
- **Architecture:** MVVM / Navigation Component
- **Camera Engine:** CameraX
- **Crypto:** Java Cryptography Architecture (JCA)
- **UI:** Material Components 3 (DayNight)

---

## 🚀 Getting Started
1. Clone the repository.
2. Build the project in Android Studio (Giraffe or newer).
3. Set your Master Password (make it strong!).
4. Start generating high-entropy passwords.

---

## 👤 Author
**eremikaforeva**  
*"Your Privacy Partner"*

[github.com/eremikaforeva](https://github.com/eremikaforeva)

---
*Disclaimer: EntropyPass is an offline-only tool. You are responsible for keeping your Master Password and backups safe. If you lose your Master Password, your data cannot be recovered.*
