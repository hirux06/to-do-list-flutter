### Simple Flutter To-Do App

This is a basic to-do list application built with Flutter. It allows you to add and delete tasks in a simple and clean interface.

-----

### Features

  - **Add Tasks:** Type a task in the text field and click the "Add" button to add it to the list.
  - **Delete Tasks:** Click the trash icon next to a task to remove it from the list.
  - **Responsive Layout:** The UI adapts to different screen sizes.

-----

### How to Run

#### Prerequisites

  * **Flutter SDK:** Make sure you have the Flutter SDK installed on your machine.
  * **IDE:** An IDE with Flutter support, such as VS Code or Android Studio.

#### Steps

1.  **Clone the repository:**
    ```bash
    git clone [your-repository-url]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd simple_todo_app
    ```
3.  **Get dependencies:**
    ```bash
    flutter pub get
    ```
4.  **Run the application:**
    ```bash
    flutter run
    ```

-----

### Code Overview

The application is structured around a single `StatefulWidget` named `TaskInputScreen`.

  * `_TaskInputScreenState`: Manages the state of the to-do list.
      * `_controller`: A `TextEditingController` to manage the input text field.
      * `taskList`: A `List<String>` to store the to-do items.
  * `build` method: Lays out the user interface, including the app bar, the text input field, the "Add" button, and the list of tasks.
  * `ListView.builder`: Efficiently creates a scrollable list of tasks, each with a delete button.

Feel free to modify the code to add more features like editing tasks, marking tasks as complete, or persistent storage\!
