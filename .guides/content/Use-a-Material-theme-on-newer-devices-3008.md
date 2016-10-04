You can use different folder structures to get your app to use different resources at runtime. As an example, you saw how to get your app to use different layout files depending on the size of the device screen.

Here, we need the app to use a different style resource depending on the API level the app’s running on. To get the app to use a particular resource if the app’s running on API level 21, we can create a new *values-v21* resource file and add the resource to this folder.

![](.guides/img/16.png)

To do this, create a new folder in the *app/src/main/res* folder called *values-v21*. Then copy the file *styles.xml* from the *values* folder, and paste it in the *values-v21* folder.

We want the app to use a Material theme if it’s running on API level 21, so edit *styles.xml* in the *values-v21* folder so that it uses a theme of `Theme.Material.Light`:


![](.guides/img/17.png)

The style name we’re using in each style resource file should be the same, because this enables an appropriate theme to be used at runtime. Let’s see how.
