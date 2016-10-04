You enable the Up button from within your activity code. You first get a reference to the action bar using the activity’s `getActionBar()` method. You then call the action bar’s `setDisplayHomeAsUpEnabled()` method, passing it a value of `true`.


![](.guides/img/52.png)

We want to enable the Up button in `OrderActivity`, so we’ll add the code to the `onCreate()` method in *OrderActivity.java*. Here’s our full activity code:

![](.guides/img/53.png)