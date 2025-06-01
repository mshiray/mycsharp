# My C# Console App

This is a simple C# console application that demonstrates the basic structure of a C# project.

## Purpose

The purpose of this application is to output "Hello World" to the console. It serves as a starting point for learning C# and building console applications.

## How to Run

1. Ensure you have the .NET SDK installed on your machine.
2. Open a terminal and navigate to the project directory.
3. Run the following command to build the project:
   ```
   dotnet build
   ```
4. After building, run the application using:
   ```
   dotnet run
   ```

  # VS Code build and clean key bindings:

   Copy below bindings to keybindings.json:

   Open the Command Palette (Ctrl+Shift+P), type Keyboard Shortcuts (JSON), and select Preferences: Open Keyboard Shortcuts (JSON).

   Add these two entries:

         [
         {
            "key": "ctrl+alt+c",
            "command": "workbench.action.tasks.runTask",
            "args": "clean"
         },
         {
            "key": "ctrl+alt+b",
            "command": "workbench.action.tasks.runTask",
            "args": "build"
         }
      ]

VS Code Build, run, clean, debug:

   Clean proejct: Ctrl+Alt+c
   Build: ctrl+Alt+B
   Run without debug: Ctrl+F5
   Debug and Run : F5
  

You should see the output:
```
Hello World
```