You add a share action to the action bar by including it in the menu resource file.

To start, add a new `action_share` string to *strings.xml*. We’ll use it to add a title to the share action in case it appears in the overflow:

![](.guides/img/42.png)
![](.guides/img/41.png)

You add the share action to the menu resource file using the `<item>` element as before. This time, however, you need to specify that you’re using a share action provider. You do this by adding an attribute of `android:actionProviderClass` and setting it to `android.widget.ShareActionProvider`.

![](.guides/img/43.png)

When you add a share action to your menu resource file, there’s no need to include an icon. The share action provider already defines one.

Now that we specify what content to share.
