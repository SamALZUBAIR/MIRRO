# MIRRO — Android Gallery

This branch imports the source code of [Iris Gallery](https://github.com/MohamadOday/iris-gallery) as the initial technical base for MIRRO.

## Import status
- Source files imported from the upstream repository.
- Machine-specific local.properties intentionally omitted.
- Original upstream README preserved as UPSTREAM_README.md.
- Upstream Apache License 2.0 preserved in LICENSE.
- This is an unmodified source import, not yet rebranded as MIRRO.
- No APK build has been run or verified during the import.

## Build
The upstream project uses Kotlin, Jetpack Compose, Android Gradle Plugin, and the Gradle wrapper. Open it in Android Studio or run ./gradlew assembleDebug in an environment with a compatible JDK and Android SDK installed.

## Before publishing
1. Build and test the untouched imported baseline.
2. Change application label, application ID, icon, splash screen, and visual identity.
3. Review third-party asset/model licenses and keep required notices.
4. Follow the Apache License 2.0 notice and attribution requirements before distributing modified builds; also review third-party asset/model licenses.
