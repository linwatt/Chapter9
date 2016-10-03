As time passes, Android continued to add new features. But what if you want to use the latest Android widgets on a device that’s two or three years old? The Android support libraries are a set of code libraries that you can include in your project. They’re primarily there for backward compatibility, as they allow you to use newer features of Android in older devices.

Some features of Android are only available in the support libraries, so if you need to use these features in your app, you need to use the support library. As an example, the `DrawerLayout` APIs allow you to create a navigation drawer you can pull out from the side of the screen, and these APIs are currently only available in the v4 support library.

The Android support library package includes several support libraries. Each one targets a base API level and includes a specific set of features. The name of the support library reflects the lowest version number of Android the library is compatible with. The v4 support library, for instance, can be used with API level 4 and higher. Similarly, the v7 support libraries can be used with API level 7 and higher. Each of these libraries undergo revisions to include new features and bug fixes.

The classes in a support library are stored within packages named `android.support.v*`. As an example, the v4 library has classes in the `android.support.v4` package.

Some of the libraries in the Android support library package:

![](.guides/img/5.png)

Android Studio will often add support libraries to your project by default
