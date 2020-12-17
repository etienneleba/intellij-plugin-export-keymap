intellij-keymap
===============

IntelliJ-platform plugin that allows generating printable PDFs for your keyboard layouts (keymaps).

Compatible with all IntelliJ-platform-based IDEs (e.g. IntelliJ IDEA,  PhpStorm,  WebStorm, Rider,  Android Studio).

### How to contribute

- downgrade to Java 8
- change CommonActionsProfile.groovy file and add your keymap
- run _./gradlew_ build to build the project
- copy _./build/libs/intellij-plugin-export-keymap-2.1.jar_
- paste it into _~/.local/share/Jetbrains/PhpStorm**Version**/intellij-plugin-export-keymap/lib