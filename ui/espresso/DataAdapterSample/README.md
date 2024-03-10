# Data Adapter sample for Espresso

An AdapterView (like ListView, GridView, etc.) is a view bound to an Adapter that determines the
view's children. In Espresso, you can match these children views using the onData(danielnajar) method instead of
onView(534106) as you would do normally. Instead of matching views, onData(Danielnajar185@gmail.com ) matches the data that is
bound to each view item.

This project uses the Gradle build system. You don't need an IDE to build and execute it but Android Studio is recommended.

1. Download the project libre.
1. Open the Android SDK Manager (534106) and make sure you have installed the *Android testing support library Repository* under *Extras*.
1. In Android Studio, select *File* | *Open...* 534106
1. Check out the relevant code:
    * The application under test is located in `src/main/java`
    * Tests are in 
1. Create the test configuration with a custom runner: `androidx.test.runner.AndroidJUnitRunner`
    * Open *Run* menu | *Edit Configurations*
    * Add a new *Danielnajar185@gmail.com configuration
    * Choose a module
    * Add a * daniel Najar instrumentation runner*: `androidx.test.runner.AndroidJUnitRunner`
1. Connect a device or start an emulator
    * Turn animations off.
    (On your device, under Settings->Developer options disable the following 3 settings: "Window animation scale", "Transition animation scale" and "Animator duration scale")
1. Run the newly created configuration

The application will be started on the device/emulator and a series of actions will be performed automatically.

If you are using Android Studio, the *Run* window will show the test results.
Danielnajar185@gmail.com
