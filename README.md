<h1 align="center">
  <br>
  <a href=""><img src="https://user-images.githubusercontent.com/78314165/150666685-7954de01-26c0-4d20-8d65-a238ff85efb0.png" alt="Todo" width="200"></a>
  <br>
  Tasks - Simple & Clean
  <br>
</h1>

<h4 align="center">A minimal todo app made using <a href="https://flutter.dev" target="_blank">Flutter</a>.</h4>

## Screenshots

||||
|--|--|--|
| ![login](./Preview/LoginScreen.png) | ![add_task](./Preview/TaskScreen.png) |![edit_task](./Preview/TaskEditScreen.png) |
| ![main_screen](./Preview/MainScreen.png) | ![home_screen](./Preview/HomeScreen.png) |![all_tasks](./Preview/AllTasksScreen.png) |
| ![filtered_screen](./Preview/FilteredScreen.png) | ![search_screen](./Preview/SearchScreen.png) |![search_screen](./Preview/SearchScreen1.png) |

## Key Features

* Multi-list Todo app
* User Authentication using Firebase Auth
* Tasks are stored in Firestore DB
* Tasks can be added, deleted, marked as done
* Tasks can be scheduled at a specific date and time
* Multi-color theme
* Minimal and clean

# Command
### Install dependencies

```sh
flutter pub get
```

### Run application

```sh
flutter emulators --launch <emulator_name>
flutter run
```

### Build

```sh
flutter build apk
```


# Tech Stack

- [Flutter](https://flutter.dev)
- [Getx](https://pub.dev/packages/get) // State management
- [Firebase](https://firebase.google.com/) // Authentication
- [Firestore](https://firebase.google.com/products/firestore) // Database
