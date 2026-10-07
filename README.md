# Minecraft Java Launcher v0.2

Android launcher UI prototype focused on performance configuration.

## What is included
- Minecraft version selector
- FPS/Balanced/Quality profiles
- Renderer/backend selector
- Java Runtime selector
- RAM selector
- Render scale
- Optimization toggles
- Landscape interface

## Important
This project does not bundle Minecraft Java Edition, Java runtimes, assets,
or a bypass of Microsoft authentication. Those components must be integrated
legally in a later launcher implementation.

## Building on Android
Use an Android IDE that supports Gradle Android projects. Import/open this
folder as a Gradle project and run the `assembleDebug` task. The APK will be
created at:

app/build/outputs/apk/debug/app-debug.apk

If the IDE cannot resolve the Android Gradle Plugin version, use a newer
Gradle-compatible Android IDE or change the plugin version to one supported
by that IDE.
