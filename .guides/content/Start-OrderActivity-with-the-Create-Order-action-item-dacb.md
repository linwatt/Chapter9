We want to get the Create Order action item in the `MainActivity` action bar to start `OrderActivity` when it’s clicked. 

To do this, we need to update `MainActivity`’s `onOptionsItemSelected()` method. We’ll start `OrderActivity` using an intent.

![](.guides/img/35.png)

When the Create Order action item is clicked, it will create an intent that starts `OrderActivity`.