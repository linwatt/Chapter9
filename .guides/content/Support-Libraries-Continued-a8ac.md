The `ActionBarActivity` class is used in conjunction with the `Theme.AppCompat` themes to add action bars to apps that support API levels between 7 and 10. If you use the `ActionBarActivity` class as the superclass for your activities, you *have* to use one of these themes or your app won’t run. You *can’t* use more recent themes, such as Material.

Even if you remove references to `ActionBarActivity` from your app, the v7 support library may still be a dependency in your project. You can see this by going to File→Project Structure. When you click on the app module and choose Dependencies, you may find there’s a reference to the v7 appcompat library:

![](.guides/img/7.png)


