# First-Flutter-App

https://codelabs.developers.google.com/codelabs/flutter-codelab-first#2

<h1>Installing Flutter SDK:</h1>

https://docs.flutter.dev/get-started/install/windows

or

git clone https://github.com/flutter/flutter.git -b stable


<h2>Envaironment Variables</h2>

"$PATH = C:\src\flutter"

<h2>Windows Version (Unable to confirm if installed Windows version is 10 or greater)</h2>

```
flutter channel master
flutter upgrade

```

<h2>Android toolchain - develop for Android devices (Android SDK version 31.0.0)
    X cmdline-tools component is missing
      Run `path/to/sdkmanager --install "cmdline-tools;latest"`
      See https://developer.android.com/studio/command-line for more details.
    X Android license status unknown.
      Run `flutter doctor --android-licenses` to accept the SDK licenses.
      See https://flutter.dev/docs/get-started/install/windows#android-setup for more details.
</h2>


https://stackoverflow.com/questions/68236007/i-am-getting-error-cmdline-tools-component-is-missing-after-installing-flutter


<h2>Android toolchain - develop for Android devices (Android SDK version 31.0.0)     ! Some Android licenses not accepted. To resolve this, run: flutter doctor --android-licenses</h2>


```
flutter doctor --android-licenses

```

