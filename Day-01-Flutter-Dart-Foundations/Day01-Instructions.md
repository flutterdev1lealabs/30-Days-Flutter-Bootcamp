# 3. Step-by-Step Explanation to Complete the Task

### Step 1 — Create the Flutter Project

Create a new Flutter project named:

```text
day1_flutter_profile
```

Open the project in your preferred IDE.

The students should identify:

```text
day1_flutter_profile/
│
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── web/
├── pubspec.yaml
└── ...
```

For today's task, the most important file is:

```text
lib/main.dart
```

---

### Step 2 — Open `main.dart`

Students should understand that this is where their Flutter application starts.

The basic structure should look similar to:

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text('Hello Flutter'),
        ),
      ),
    ),
  );
}
```

Do not focus heavily on UI concepts yet.

The important idea is:

```text
main()
   ↓
runApp()
   ↓
Flutter application starts
```

---

### Step 3 — Create Basic Dart Variables

Above `main()`, create variables such as:

```dart
String name = 'Alex';
int age = 22;
bool learningFlutter = true;

List<String> technologies = [
  'Flutter',
  'Dart',
  'Git',
];
```

Explain what each one represents.

For example:

```dart
String
```

stores text.

```dart
int
```

stores whole numbers.

```dart
bool
```

stores:

```text
true
false
```

And:

```dart
List<String>
```

stores multiple strings.

---

### Step 4 — Create a Simple Function

Ask students to create a function that returns a short introduction.

For example:

```dart
String getIntroduction() {
  return 'My name is $name and I am learning Flutter.';
}
```

Explain that a function is a reusable block of code.

Also explain:

```dart
$name
```

as Dart string interpolation.

---

### Step 5 — Use the Variables in the Flutter Application

Students should use their variables in the application instead of writing everything directly as hard-coded text.

For example:

```dart
Text(name)
```

and:

```dart
Text('Age: $age')
```

and:

```dart
Text(
  learningFlutter
      ? 'Currently learning Flutter'
      : 'Not currently learning Flutter',
)
```

They can also display their technologies.

At this stage, the UI can remain extremely simple.

**The objective is understanding the code, not designing a professional interface.**

---

### Step 6 — Add Comments

Students must add comments explaining important parts.

For example:

```dart
// Entry point of the Dart application.
void main() {
```

and:

```dart
// Starts the Flutter application.
runApp(
```

The comments should be written by the students themselves so that you can check whether they understand the code.

---

### Step 7 — Run the Application

Start the emulator and run:

```bash
flutter run
```

Students should verify that their profile information appears correctly.

Then make one small change—for example, change their name—and run the application again.

This demonstrates the basic development cycle:

```text
Write Code
    ↓
Run App
    ↓
See Result
    ↓
Modify Code
    ↓
Run Again
```

---

### Step 8 — Create `README.md`

Students should create a simple README containing:

```text
# Day 1 Flutter Profile

## About
A simple Flutter application created during Day 1
of my Flutter development learning.

## What I Learned
- Dart variables
- Dart data types
- Functions
- main()
- runApp()
- Flutter project structure

## Technologies
- Flutter
- Dart
- Git
- GitHub
```

They should add their own information rather than simply copying the example.

---

### Step 9 — Initialize Git

From the project directory:

```bash
git init
```

Then:

```bash
git add .
```

Commit the project:

```bash
git commit -m "Day 1: Create Flutter developer profile"
```

---

### Step 10 — Create the GitHub Repository

Create a GitHub repository named:

```text
day1_flutter_profile
```

Then connect the local project to GitHub and push it.

The final repository should contain:

```text
day1_flutter_profile
│
├── lib/
│   └── main.dart
├── README.md
├── pubspec.yaml
├── android/
├── ios/
└── ...
```

---

### Step 11 — Final Submission

Students submit:

**GitHub Repository Link**

They should also be able to explain these questions verbally:

1. What is Dart?
2. What is Flutter?
3. Where does a Dart application start?
4. What does `main()` do?
5. What does `runApp()` do?
6. Where is the main Flutter code located?
7. What is `pubspec.yaml`?
8. What is a `String`?
9. What is an `int`?
10. What is a `bool`?
11. What is a `List`?
12. What is a function?

This gives you a quick way to check whether they actually understood the task rather than simply copied code.

---
