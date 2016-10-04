## React to action item clicks with the onOptionsItemSelected() method

You get your activity to react to when an action item in the action bar is clicked by implementing the `onOptionsItemSelected()` method. This method runs whenever an item in the action bar is clicked.

The `onOptionsItemSelected()` method takes one attribute, a `MenuItem` object that represents the item on the action bar that was clicked. You can use the `MenuItem`’s `getItemId()` method to get the ID of the item on the action bar that was clicked so that you can perform an appropriate action, such as starting a new activity.

Here's the code for our `onOptionsItemSelected()` method:

![](.guides/img/33.png)

We’re going to get the Create Order action item to start a new activity called `OrderActivity` when it’s clicked.
