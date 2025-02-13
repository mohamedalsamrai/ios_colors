# 🌈 IosColors

`IosColors` is a sleek and modern Flutter package that brings the elegance of iOS system colors to your applications. Whether you're designing a seamless iOS experience or just love Apple's aesthetic, this package ensures your app looks and feels native.

## ✨ Features

✅ A rich palette of official iOS system colors 🌟  
✅ Supports light, dark, and custom shades 🎨  
✅ Helps maintain a polished and consistent UI experience 🔥  
✅ Easily accessible as static color constants 🏆  

## 🚀 Getting Started

To integrate `IosColors` into your project, simply add the file and import it:

```dart
import 'package:ios_colors/ios_colors.dart';
```

## 🎯 Usage

Effortlessly access predefined iOS colors:

```dart
import 'package:flutter/material.dart';
import 'package:ios_colors/ios_colors.dart';

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

## 📌 Additional Information

💡 Want to contribute? Check out our repository for more details. Contributions, feedback, and suggestions are always welcome! 🎉

