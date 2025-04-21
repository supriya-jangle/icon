import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: IconButtonDemo(),
 );
 }
}
class IconButtonDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('IconButton Example')),
 body: Center(
 child: IconButton(
 icon: Icon(Icons.favorite), // The icon you want to show
 color: Colors.red, // Icon color
 onPressed: () {
 print('IconButton Pressed!');
 },
 ),
 ),
 );
 }
}
