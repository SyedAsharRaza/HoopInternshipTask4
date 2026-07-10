```markdown
# Food Delivery App 🍔

A modern, highly responsive, and pixel-perfect Food Delivery UI built using Flutter. This project focuses on adaptive layouts, clean state management boundaries, and robust keyboard handling for a seamless user experience.

---

## 📱 App Gallery

| Login Screen | Home Screen | Food Detail Screen |
| :---: | :---: | :---: |
| <img src="screenshots/login_screen.jpeg" width="250" alt="Login Screen" /> | <img src="screenshots/home_screen.jpeg" width="250" alt="Home Screen" /> | <img src="screenshots/food_detail_screen.jpeg" width="250" alt="Food Detail Screen" /> |

---

## 🚀 Key Engineering Features

* **Adaptive Architecture:** Fully dynamic grid-splitting layout using `LayoutBuilder` and flexible constraint bounds to handle multiple device aspect ratios perfectly.
* **Proportional Layout Scaling:** Utilizes structured `MediaQuery` constraints across primary structural elements to prevent UI clipping on small or oversized displays.
* **Defensive Input Design:** Implements clean layout isolation using `SingleChildScrollView` pairing and explicit `resizeToAvoidBottomInset: false` bounds to completely eliminate viewport overflow errors when the soft keyboard invokes.
* **Optimal Rendering Boundaries:** Strict adherence to explicit column sizing metrics (`MainAxisSize.min`) to guarantee unpredictable dynamic content builds exactly to size without throwing unconstrained layout crashes.

## 🛠️ Tech Stack & Architecture

* **Framework:** Flutter (Dart)
* **Pattern:** Clean UI/Widget Separation (Decoupled, reusable layout components isolated from primary feature view trees).

---

## 🏃‍♂️ Getting Started

Follow these steps to get a local copy of the project up, running, and ready for development.

### Prerequisites
Ensure you have the Flutter SDK installed and configured on your machine.
```bash
flutter --version

```

### Installation & Run

1. **Clone the repository:**

```bash
git clone [https://github.com/SyedAsharRaza/HoopInternshipTask4.git](https://github.com/SyedAsharRaza/HoopInternshipTask4.git)
cd HoopInternshipTask4

```

2. **Fetch dependencies:**

```bash
flutter pub get

```

3. **Verify the test suite passes:**

```bash
flutter test

```

4. **Launch the application:**

```bash
flutter run

```

```

```
