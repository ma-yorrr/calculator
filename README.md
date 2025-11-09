# mobile-casio

A beautiful, themeable Casio-style calculator built with Flutter.  
This starter contains Basic, Scientific, and a scaffolded Casio Mode (placeholder modules), expression evaluation, and a simple graph demo. It is themeable with multiple skins and ready to be extended for the high-school Casio models (fractions, matrices, statistics, graphing, programming, etc.).

Features in this starter:
- Basic and Scientific modes
- Casio Mode with module placeholders (Fractions, Matrices, Statistics, Graphing, etc.)
- Expression evaluator using math_expressions
- Simple graph preview (sin(x), x^2, etc.) with fl_chart
- Theme chooser (Light, Dark, Colorful)
- Clean, modular code structure for extending modules

Run locally (Android emulator or device)
1. Install Flutter: https://flutter.dev/docs/get-started/install
2. Install Android Studio (Android SDK + AVD manager) and create an Android emulator or enable USB debugging on a real device.
3. From the project root:
   - flutter pub get
   - flutter devices (verify device/emulator is available)
   - flutter run

Build release APK
- flutter build apk --release
- Install: adb install -r build/app/outputs/flutter-apk/app-release.apk

How to push to GitHub (quick)
1. Create a public repo named `mobile-casio` on your GitHub account.
2. Locally:
   - git init
   - git add .
   - git commit -m "Initial commit: mobile-casio Flutter starter"
   - git branch -M main
   - git remote add origin https://github.com/bluesecurity7/mobile-casio.git
   - git push -u origin main

Roadmap suggestions (high school parity)
- Implement high-priority Casio features: Fractions & Complex, Matrices, Statistics/regression, Graphing (trace, table-of-values).
- Add persistent history, memory registers, unit tests for parser and math modules.
- Optionally add a CAS (symbolic) engine or integrate with an existing library for symbolic algebra.

If you want, I will:
- Provide the GitHub Actions workflow file (I included a basic one below) and explain how to enable it.
- Create issue templates for module work and help you break down features into issues.
- After you push, I can open PR templates and suggest branch names for iterative work.

License: MIT
