Most of the time, you’ll want to add action items to the action bar. These are buttons or text in the action bar you can click on to make something happen. As an example, we’re going to add a “Create Order” button to our action bar.


![](.guides/img/21.png)

### To add items to the action bar, you do three things:
**1) Define the action items in a menu resource file.**

**2) Get the activity to inflate the menu resource.**
You do this by implementing the `onCreateOptionsMenu()` method.

**3) Add code to say what each item should do when clicked.**
You do this by implementing the `onOptionsItemSelected()` method.
