# JSONPlaceholder API User Fetcher

This Flutter app demonstrates how to fetch and display user data from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/). It uses HTTP requests to retrieve user information and displays it in a user-friendly list view.

## Features

- Fetches user data from the JSONPlaceholder API.
- Displays user information (name, email) in a list view.
- Handles loading state with a progress indicator while data is being fetched.

## Getting Started

### Prerequisites

- Flutter SDK installed (see [official Flutter documentation](https://flutter.dev/docs/get-started/install))
- A compatible IDE (e.g., Android Studio, VS Code) with Flutter and Dart plugins

### Clone the Repository

```bash
git clone https://github.com/yourusername/jsonplaceholder_user_fetcher.git
cd jsonplaceholder_user_fetcher
```

## Install Dependencies

```
flutter pub get
```

## Run the app
```
flutter run
```
This will launch the app on your connected device or emulator.

## API Usage
This app uses the JSONPlaceholder API to fetch user data. Specifically, it makes a GET request to https://jsonplaceholder.typicode.com/users to retrieve a list of users in JSON format.

## Libraries Used
`http:` For making HTTP requests to the JSONPlaceholder API.
`flutter/material.dart:` Flutter's material design widgets for building the UI.

## Contributions
Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


