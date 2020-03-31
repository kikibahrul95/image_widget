# image_widget
flutter// tidak ada gambar dan pubpecs.yml
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("image"),
        ),
        body: Center(
          child: Container(
              color: Colors.lightBlue,
              width: 200,
              height: 200,
              padding: EdgeInsets.all(3),
              child: Image(
                image: AssetImage(
                    ""),
                    fit: BoxFit.contain,
                    repeat: ImageRepeat.repeat,
              )),
        ),
      ),
    );
  }
}
