# Part C: Short Coding Task — Counter App (+5 Increment)

## Introduction

This Flutter application demonstrates the use of a **button with state management**.  
When the button is pressed, the counter value increases by **5** instead of the default increment of 1.  

---

## How the App Works

### **Single Screen Counter App**
- The app starts with the `main()` function that runs the `MyApp` widget.
- `MyApp` sets up a `MaterialApp` and defines the home screen as `MyHomePage`.
- Inside `MyHomePage`, a counter variable `_counter` is initialized to `0`.
- A method `_incrementCounter()` is defined to increase the counter by **5** each time it is called:
  ```dart
  void _incrementCounter() {
    setState(() {
      _counter = _counter + 5;
    });
  }
- The FloatingActionButton triggers this function when pressed, updating the displayed value.
- The counter value and label text are centered on the screen using a Column widget.

---

- **Developed by:** Janlee Estoy
- **Course:** Computer Engineering
- **Part B:** Short Coding Task — Counter App (+5 Increment)