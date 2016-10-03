We want our prototype app to include action bars. The app supports devices running a minimum of API level 17, so we don’t need to provide backward compatibility by using `ActionBarActivity` and `Theme.AppCompat`. 

Instead, we’ll bring the look more up to date by using a Holo theme by default, and get it to switch to a Material theme if it’s running on API level 21.

To do this, we need to do two things:
**1) Make sure the activity code doesn’t reference `ActionBarActivity`.**
If it does, we’ll only be able to use a `Theme.AppCompat` theme.

**2) Apply the themes.**
We’ll get the app to pick up the right theme for the API level it’s running on.


We’re going to keep the dependency on the v7 appcompat library as this has an impact on the code you’ll write later on.
