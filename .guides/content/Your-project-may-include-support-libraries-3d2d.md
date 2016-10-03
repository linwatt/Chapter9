We’re going to build a prototype of the Pizza app that supports API level 17 and above. 

Create a new Android project with a blank activity for an application named “Bits and Pizzas” with a package name of *com.hfad.bitsandpizzas*. The minimum SDK should be API level 17. Specify an activity called “MainActivity”, a layout called “activity_main” and a menu resource called “menu_main”.

We’re going to look at how your new project may be using support libraries by default. First, let’s look at *MainActivity.java*. Here’s the code that Android Studio created for us. By default, `MainActivity` extends the `android.support.v7.app.ActionBarActivity` class. In other words, it’s using a v7 support library:

![](.guides/img/6.png)
