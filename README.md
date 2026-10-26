# 📱 Flutter Lab Programs

### Flutter & Dart Practical Exercises

A collection of Flutter lab programs demonstrating essential mobile application development concepts using **Flutter, Dart, Material Design, reusable widgets, navigation, animations, form validation, and REST API integration**.

This repository is intended for students learning Flutter through practical exercises, with simple implementations that are easy to understand, execute, and modify.

---

## 👨‍💻 About Me

**Vinay Ranjan**

- GitHub: [@Vinay32592](https://github.com/Vinay32592)
- Repository: [Flutter Lab Programs](https://github.com/Vinay32592/Flutter)

## 🎯 Learning Objectives

- Understand Flutter application structure and widget composition.
- Build user interfaces using basic and custom widgets.
- Implement screen navigation using named routes.
- Apply animations to UI elements.
- Create forms with input validation and error handling.
- Fetch and display data from REST APIs.
- Develop interactive applications using Dart and Flutter.

## 📚 Lab Programs

The following programs are covered in this learning collection.

| No. | Program | Concepts Covered |
|---:|---|---|
| 01 | Student Profile Card | `StatelessWidget`, `MaterialApp`, `Scaffold`, `CircleAvatar`, `Container` |
| 02 | Student Information Card | Custom widgets, parameters, widget reusability |
| 03 | Food Ordering Application | Custom `FoodCard`, food icons, prices, buttons |
| 04 | Named Routes Navigation | `initialRoute`, `routes`, `Navigator.pushNamed()`, `Navigator.pop()` |
| 05 | Flutter Animations | Fade, Slide, Scale, Rotation |
| 06 | Student Registration Portal | Forms, email validation, phone validation, dropdowns, checkboxes |
| 07 | REST API Product List | HTTP requests, JSON parsing, product images, loading and error states |
| 08 | Smart Water Intake Tracker | Stateful widgets, water intake calculations, progress indicators, validation, reset confirmation |

*The table represents the lab exercises documented for this collection. Refer to the repository files for the programs currently committed.*

## 🛠️ Technologies Used

- **Flutter** — Cross-platform application development
- **Dart** — Programming language
- **Material Design** — UI components
- **REST API** — Fetching external data
- **JSON** — Processing API responses
- **DartPad** — Online Flutter development and testing

## 🚀 Getting Started

### Option 1: Run Using DartPad

DartPad is suitable for the basic Flutter programs in this collection.

1. Open [DartPad](https://dartpad.dev/).
2. Select Flutter mode.
3. Copy the required program into `main.dart`.
4. Add any required package through DartPad's Packages panel.
5. Click **Run** to execute the application.

**Note:** REST API examples may require the `http` package and internet access. Platform-specific features and local storage packages may require a complete Flutter project.

### Option 2: Run Locally

Install the Flutter SDK and set up an editor such as Visual Studio Code or Android Studio.

Clone the repository:

```bash
git clone https://github.com/Vinay32592/Flutter.git
```

Navigate into the repository:

```bash
cd Flutter
```

If the repository root contains a Flutter project with a `pubspec.yaml` file, install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

If the repository contains separate projects, navigate to the relevant project directory before running these commands.

## 🧩 Key Flutter Concepts

### 1. Widgets and Layouts

Learn how to arrange UI elements using `Column`, `Row`, `Center`, `Container`, `Card`, and other basic widgets.

### 2. Custom and Reusable Widgets

Create reusable components such as `StudentCard` and `FoodCard` by passing values through constructor parameters.

### 3. Navigation

Move between screens using named routes and control the navigation stack with Flutter's `Navigator` API.

### 4. Animations

Use Flutter's animation widgets to create fade, slide, scale, and rotation effects.

### 5. Form Validation

Validate mandatory fields, email addresses, phone numbers, dropdown selections, and terms acceptance before submitting a form.

### 6. REST API Integration

Fetch product information, decode JSON responses, display results in a scrollable list, and handle loading and error states.

### 7. State Management

Use `StatefulWidget` and `setState()` to update the interface when the application data changes.

## 🧪 Testing

Each program can be tested by checking its expected behavior:

- **Student cards:** Verify that different student details appear correctly.
- **Food ordering:** Verify that each food card displays its information and responds to button presses.
- **Navigation:** Verify that all three screens open and return correctly.
- **Animations:** Trigger and reverse the animation effects.
- **Registration form:** Test both valid and invalid input values.
- **REST API:** Check successful data loading, loading indicators, and error handling.
- **Water tracker:** Test water additions, invalid values, entry counts, remaining water, completion percentage, and reset confirmation.

## 📈 Future Enhancements

- Add screenshots and sample outputs for every lab program.
- Organize programs into separate folders with their own source files.
- Add instructions and dependencies for each individual exercise.
- Add automated tests for validation and calculations.
- Extend the water tracker with persistent local storage.
- Improve UI consistency and accessibility across applications.

## 📖 Learning Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Dart Language Documentation](https://dart.dev/guides)
- [Flutter Widget Catalog](https://docs.flutter.dev/ui/widgets)
- [Flutter Cookbook](https://docs.flutter.dev/cookbook)
- [DartPad](https://dartpad.dev/)

## 🤝 Contributions

This repository is primarily intended for learning and practical experimentation. Suggestions, improvements, and educational contributions are welcome.

## 📄 License

No license is specified here. Add an appropriate `LICENSE` file if you want to define the terms under which others may reuse or distribute this code.

---

**Built with Flutter and Dart by Vinay Ranjan.**

⭐ If this repository helps you learn Flutter, consider starring it on GitHub.
