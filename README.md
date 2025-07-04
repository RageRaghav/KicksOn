# 👟 Kickson - A Flutter Shopping App

Kickson is a beginner-friendly mobile app built using **Flutter** that demonstrates the fundamentals of state management using the **Provider** package. It simulates a shopping experience where users can view shoes, select sizes, and add them to the cart dynamically.

---

## ✨ Features

- 🧾 **Product Listing** - Browse a curated selection of shoes.
- 🔄 **State Management** - Implemented using `Provider` for efficient state updates.
- 📦 **Add to Cart** - Users can add shoes to the cart based on selected size.
- 🗑️ **Remove from Cart** - Supports removing items from the cart by size.
- 🖼️ **Asset Management** - Loads product images locally from `assets/images/`.
- 🧠 **Clean Architecture** - Separation of UI, state, and data for better scalability.

---

## 📸 Screenshots

| Product Detail Screen |
|------------------------|
| ![Product Detail](assets/screenshots/details_screen.png) |

> *(Replace with your actual screenshot file path or image)*

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (>=3.6.0)
- Dart SDK (>=3.0.0)
- A device/emulator

### Run the App

```bash
git clone https://github.com/your-username/kickson.git
cd kickson
flutter pub get
flutter run
```
---
## 📦 Packages Used

| Package         | Description                                |
|-----------------|--------------------------------------------|
| [flutter](https://flutter.dev) | Core UI toolkit for building natively compiled apps |
| [provider](https://pub.dev/packages/provider) | State management using ChangeNotifier |
| [google_fonts](https://pub.dev/packages/google_fonts) | Easily use custom fonts in your UI |
| [cupertino_icons](https://pub.dev/packages/cupertino_icons) | Default iOS-style icons for Flutter apps |
---
## 🧠 Concepts Demonstrated

- ✅ State management using `Provider` and `ChangeNotifier`
- ✅ Dynamic UI updates using `Consumer` and `context.watch()`
- ✅ Cart logic based on shoe size selection
- ✅ Image asset loading from `assets/images/`
- ✅ Theming with custom fonts (`Lato`, `Fredoka`, `PlayfairDisplay`)
- ✅ Responsive UI using widgets like `MediaQuery`, `Flexible`, `Expanded`
- ✅ Modular project structure with clean separation of concerns


