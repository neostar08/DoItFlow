# DoItFlow - To-Do List App

DoItFlow is a simple, user-friendly to-do list app designed to help you manage your tasks efficiently. Built with Android Studio, the app showcases clean architecture, elegant UI, and customizable features to streamline productivity.

---

## Features

- **Add Tasks**: Quickly add tasks with a title, description, and due date.
- **View Tasks**: Display tasks in a neat, scrollable list.
- **Delete Tasks**: Remove completed or unnecessary tasks.
- **In-Memory Data Management**: Tasks are stored temporarily during app runtime for simplicity.
- **Responsive UI**: Built using Material Design principles to ensure a seamless user experience.

---

## Technology Stack

- **Programming Language**: Kotlin
- **Frameworks**: Android SDK
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI**: Material Design
- **Tools**: 
  - Android Studio
  - View Binding

---

## Prerequisites

- Android Studio 2021.3.1 or later
- Android device or emulator running Android 9.0 (Pie) or higher
- Kotlin 1.8.10 or compatible

---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/neostar8/DoItFlow.git
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Select "Open an Existing Project" and navigate to the cloned repository.

3. **Sync Gradle**:
   - Allow Android Studio to sync all Gradle dependencies automatically.

4. **Run the App**:
   - Connect an Android device or launch an emulator.
   - Click the "Run" button in Android Studio.

---

## File Structure

```
DoItFlow/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/doitflow/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── Task.kt
│   │   │   │   ├── TaskAdapter.kt
│   │   │   │   ├── TaskViewModel.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── task_item.xml
│   │   │   │   │   ├── dialog_add_task.xml
```

---

## How to Contribute

We welcome contributions to make DoItFlow even better!

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes**.
4. **Commit and Push**:
   ```bash
   git add .
   git commit -m "Add your message here"
   git push origin feature/your-feature-name
   ```
5. **Create a Pull Request**.

---

## Screenshots

### Main Screen
![Main Screen](https://via.placeholder.com/400x800)

### Add Task Dialog
![Add Task Dialog](https://via.placeholder.com/400x800)

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For further inquiries, feel free to contact:
- **Email**: yourname@example.com
- **GitHub**: [yourusername](https://github.com/yourusername)
