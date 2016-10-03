We’re going to change the app so that it uses `Theme.Holo.Light` by default, and switches to using `Theme.Material.Light` if the app’s running on API level 21.

![](.guides/img/15.png)

We’ll start by changing the default theme. To do this, open the style resource file *styles.xml* located in the *app/src/main/res/values* folder. This is the default style resource file. By default, we want to use a theme of `Theme.Holo.Light`, so this needs to be reflected in the `<style>` attribute like this:

![](.guides/img/14.png)
