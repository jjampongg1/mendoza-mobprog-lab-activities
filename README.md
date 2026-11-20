# mendoza_mobprog
# Laboratory Activity 0A: Flutter Installation and Project Setup

## Laboratory Discussion

**1. What challenges did you encounter while installing or configuring Flutter?**

One challenge I encountered was downloading the Dart SDK because my computer initially couldn't connect to Google's download server. I also encountered an issue where Windows could not recognize the Flutter command because its directory was not yet properly configured in PATH.

**2. Did you encounter any errors when running flutter doctor?**

Yes. Initially, Flutter could not download the Dart SDK. After successfully installing and configuring Flutter, `flutter doctor` reported that the Android SDK and Visual Studio were missing.

**3. How did you resolve installation, dependency, SDK, or device-related issues?**

I added the Flutter SDK's bin directory to my Windows PATH environment variable. After restarting VS Code, I was able to execute Flutter commands successfully. Since Android Studio was not yet installed, I used Chrome as my testing device and successfully launched the application.

**4. What did you learn about configuring a Flutter development environment?**

I learned how to install the Flutter SDK, configure environment variables, use VS Code, and verify the development environment through the `flutter doctor` command. I also learned that Flutter applications can be tested using different supported devices and platforms.

**5. What practices will you follow to make future Flutter development easier?**

I will make sure that my Flutter SDK and dependencies are properly configured, regularly check my development environment using `flutter doctor`, organize my project files properly, and test my applications regularly to identify possible errors early.