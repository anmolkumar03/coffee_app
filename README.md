# Coffee App

A delightful multi-platform coffee discovery application built with Flutter. This app showcases a list of coffees, featuring a clean, modern UI with both light and dark themes.

## 🌟 Features

- **Cross-Platform:** Single codebase for Android, iOS, Windows, and Linux.
- **State Management:** Efficiently manages app state using the `provider` package.
- **Dynamic Theming:** Supports both light and dark modes, adapting to system settings.
- **Clean Architecture:** Organized project structure for better maintainability and scalability.
- **Asynchronous Data Fetching:** Fetches coffee data from a remote source on startup.

## 📸 Screenshots

*(Add screenshots or a GIF of your app here to showcase the UI)*

| Light Mode | Dark Mode |
| :---: | :---: |
| *Your Light Mode Screenshot* | *Your Dark Mode Screenshot* |

## 🛠️ Technologies Used

- **Framework:** Flutter
- **Language:** Dart
- **State Management:** Provider
- **UI:** Material Design

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have the Flutter SDK installed on your machine. For help, check the official Flutter installation guide.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/anmolkumar03/coffee_app.git
    cd coffee_app
    ```

2.  **Install dependencies:**
    ```sh
    flutter pub get
    ```

3.  **Run the application:**
    ```sh
    flutter run
    ```
    You can also select a specific device or platform to run on.

## 📁 Project Structure

The project follows a standard Flutter project structure, with the core application logic located in the `lib` directory.

```
lib/
├── core/
│   ├── app_theme.dart      # Contains light and dark theme data.
│   └── constants.dart      # Application-wide constants.
├── providers/
│   └── coffee_provider.dart # Manages state for coffee data.
├── screens/
│   └── home_screen.dart    # The main screen of the application.
└── main.dart               # The main entry point of the application.
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.
