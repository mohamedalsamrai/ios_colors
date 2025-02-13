# IosColors

`IosColors` is a Flutter package that provides a collection of iOS system colors, allowing developers to easily implement Apple's system color palette in their Flutter applications.

## Features

- Provides a wide range of iOS system colors, including light, dark, and custom shades.
- Helps maintain a consistent look and feel with iOS system themes.
- Easily accessible static color constants.

## Getting Started

To use this package, add `IosColors.dart` to your project and import it:

```dart
import 'package:your_package_name/ios_colors.dart';
```

## Usage

Access iOS system colors by using the predefined constants:

```dart
import 'package:flutter/material.dart';
import 'package:your_package_name/ios_colors.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        backgroundColor: IosColors.systemBackground,
        appBar: AppBar(
          title: Text('IosColors Example'),
          backgroundColor: IosColors.systemBlue,
        ),
        body: Center(
          child: Text(
            'Hello, iOS Colors!',
            style: TextStyle(color: IosColors.label),
          ),
        ),
      ),
    );
  }
}
```

## Additional Information

For more information, contributions, or issue reporting, please check the repository. Contributions are always welcome!
