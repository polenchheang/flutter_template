# flutter_web_test_1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Support Devices
`flutter device`

`flutter emulator`

## Launch Emulator
`flutter emulator -l [device]`

[device] is the first column of the output from `flutter emulator`
*You wont*

## Run
`flutter run -d [device]`

[device] second column of the output from `flutter devices`

## Run Test
### Unit Test / Widget Test
`flutter test [test_file]`

eg: `flutter test test/counter_test.dart`

### Integration Test

`flutter drive --target=test_driver/[test_file]`

eg: `flutter drive --target=test_driver/app.dart`