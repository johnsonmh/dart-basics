# Dart Basics

This repository contains a collection of useful extension methods on the built
in objects in Dart, such as Strings, Iterables, and Object.

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

for (var i in 10.range) {
  if (i.isEven) numbers.add(i);
}

if (numbers.isNotNull && numbers.all(isEven)) {
  print('all numbers are even');
}
```

## Documentation

See the [API docs](https://pub.dev/documentation/basics/latest/) for full documentation and sample 
usages. 

## Notes
This is not an official Google project.

