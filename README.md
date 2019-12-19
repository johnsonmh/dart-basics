# Dart Basics

This repository contains a collection of useful extension methods on the built
in objects in Dart, such as Strings, Collections, and Object.

## Usage
Import the basics library.

```dart
import 'package:basics/basics.dart';
```

Then use the methods directly on objects in your dart code.

```dart
List<int> numbers;

if (numbers.isNull) {
  print('numbers is uninitialized').
}

numbers = [2, 4, 8];

if (numbers.isNotNull && numbers.all(isEven)) {
  print('all numbers are even');
}
```

## Notes
This is not an official Google project.

