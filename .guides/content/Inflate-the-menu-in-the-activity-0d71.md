### Inflate the menu in the activity with the onCreateOptionsMenu() method

Once you’ve created a menu resource file, you add the items it contains to the action bar by implementing the activity’s `onCreateOptionsMenu()` method. It runs when the action bar’s menu gets created and takes one parameter, a `Menu` object representing the action bar.

Here's our `onCreateOptionsMenu()` method:

![](.guides/img/31.png)

You add items to the action bar using
![](.guides/img/32.png)

This takes the menu items in the *menu_main.xml* menu resource file, and adds them to the action bar `Menu` object.
