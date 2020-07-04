# flutter_web_test_1

Template project to start a new flutter project.

## Getting Started

### Test Run
1. `flutter doctor`
2. Run project again devices that you want to support like iOS, Android, and Chrome.

### Testing Dependencies
Copy from `pubspec.yaml` to your
```
dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_driver:
    sdk: flutter
  test: any
```

### Running Test

#### Unit Test

Copy lib/counter.dart and test/counter_test.dart
Run `flutter test test/counter_test.dart`

#### UI Test

Copy test/widget_test.dart
Run `flutter test test/widget_test.dart`

#### Driver Test

Copy folder test_driver and lib/main.dart
Run `flutter drive --target=test_driver/app.dart`


*Now your development is ready.*

## Support Devices

`flutter device`

`flutter emulator`

## Launch Emulator
`flutter emulator -l [device]`

[device] is the first column of the output from `flutter emulator`

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