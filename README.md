# flutter_inherited_notifier

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

InheritedWidget holds on its own value but InheritedNotifier doesn't

What is BuildContext?
BuildContext is a locator that is used to track each widget 
in a tree and locate them and their position in the tree.
The BuildContext of each widget is passed to
their build method. Remember that the build method returns the widget tree a widget renders.
Each BuildContext is unique to a widget.
This means that the BuildContext of a widget
is not the same as the BuildContext of the widgets returned by the widget.