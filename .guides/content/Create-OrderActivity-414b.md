We need to create a new activity called `OrderActivity` so our Create Order action item can launch it.

Start by creating a new blank activity. Give it a name of “OrderActivity”, a layout name of “activity_order”, a title of “Create Order”, and a menu resource name of “menu_order”.


Here’s the code for *OrderActivity.java*, make sure that `OrderActivity` extends the `Activity` class and not `ActionBarActivity`. This is because you can only use one of the `Theme.AppCompat` themes with `ActionBarActivity`, and we want to use the Holo and Material themes .

![](.guides/img/34.png)

We’ve not included the `onCreateOptionsMenu()` and `onOptionsItemSelected()` methods in our `OrderActivity` code, as we don’t need `OrderActivity` to display menu items from the menu resource file in its action bar. These methods would need to be added if we ever did want to display menu items.

Now that we’ve created `OrderActivity`, let’s get the Create Order action item in `MainActivity` to start it.
