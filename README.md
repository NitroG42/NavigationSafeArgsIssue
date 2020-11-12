# Navigation Safe Args Kotlin + Kotlin 1.4.20 fails

When using Kotlin 1.4.20 (RC or M version) with the plugin androidx.navigation.safeargs.kotlin, the expression analysis fails inexorably if we use the 1.4.20-RC Kotlin Intellij Plugin.
Two simple workaround :

    Keep Kotlin 1.4.20 on the project but stay on 1.4.10 Intellij plugin. (but we lack the new version)
    Switch to standard safeargs plugin androidx.navigation.safeargs. (we lack the automatic generation of code)


See
https://youtrack.jetbrains.com/issue/KT-43137