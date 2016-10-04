- To add an action bar to apps supporting API level 11 or above apply one of the Holo or Material themes.

- Add an action bar to apps supporting API level 7 or above by applying an AppCompat theme and using the `ActionBarActivity` class. If you use `ActionBarActivity`, you must use an AppCompat theme.

- `ActionBarActivity` and the AppCompat themes are in the v7 appcompat support library.

- The `android:theme` attribute in *AndroidManifest.xml* specifies which theme to apply.

- You define styles in a style resource file using the `<style>` element. The `name` attribute gives the style a name. The `parent` attribute specifies where the style should inherit its properties from.

- The default folder for style resource files is *app/src/main/res/values*. Put a style resource file in the *app/src/main/res/values-v21* folder if you want it to be used on API level 21.

- Add action items to your action bar by adding items to a menu resource file.

- Add the items in the menu resource file to the action bar by implementing the activity’s `onCreateOptionsMenu()` method.

- Say what items should do when clicked by implementing the activity’s `onOptionsItemSelected()` method.

- You can share content by adding the share action provider to your action bar. Add it by including it in your menu resource file. Call its `setShareIntent()` method to pass it an intent describing the content you wish to share.

- Add an Up button to your action bar to navigate up the app’s hierarchy. Specify the hierarchy in *AndroidManifest.xml*. Use the `ActionBar setDisplayHomeAsUpEnabled()` method to enable the Up button.