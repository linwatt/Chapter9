If you want your apps to run on API level 11 or above, you add an action bar by applying `Theme.Holo` or one of its subclasses. This is what you’ll need to do most of the time. 

For API level 21 or above, you have the added option of using one of the newer `Theme.Material` themes. There are several different themes to choose from depending on what appearance you want your app to have. As an example, applying a theme of `Theme.Material.Light.DarkActionBar` will give you activities with a light background and a dark action bar.


![](.guides/img/4.png)

If you need to support older devices running API level 7 or above, you can still add an action bar but you need to do it slightly differently. You first need to change your activities so that they extend the class `android.support.v7.app.ActionBarActivity` instead of the `android.app.Activity` class. You must then apply one of the `Theme.AppCompat` themes.
