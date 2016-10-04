![](.guides/img/48.png)

If you have an app that contains a hierarchy of activities, you can enable the **Up button** on the action bar to navigate through the app using hierarchical relationships. 

As an example, `MainActivity` in our app includes an action item on its action bar that starts a second activity, `OrderActivity`. If we enable the Up button on `OrderActivity`’s action bar, the user will be able to return to `MainActivity` by clicking on it.

![](.guides/img/49.png)

### Up navigation vs the Back button
Up navigation may sound the same as using the Back button, but it’s different. The Back button allows users to work their way back through the history of activities they’ve been to. The Up button is purely based on the app's hierarchical structure.

![](.guides/img/50.png)


So that you can see this in action, we’re going to enable the Up button on `OrderActivity`’s action bar. When you click on it, it will display `MainActivity`.

**Use the Back button to navigate back to the previous activity.**

**Use the Up button to navigate up the app’s hierarchy.**