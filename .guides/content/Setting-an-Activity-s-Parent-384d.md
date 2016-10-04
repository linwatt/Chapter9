The Up button enables the user to navigate up a hierarchy of activities in the app. You declare this hierarchy in *AndroidManifest.xml* by specifying the parent of each activity. 

As an example, we want the user to be able to navigate from `OrderActivity` to `MainActivity` when they press the Up button, so this means that `MainActivity` is the parent of `OrderActivity`.

From API level 16, you specify the parent activity using the `android:parentActivityName` attribute. For older versions of Android, you need to include a `<meta-data>` element that includes the name of the parent activity. Here are both approaches in our *AndroidManifest.xml*:

![](.guides/img/51.png)

Now we need to enable the Up button in `OrderActivity`.